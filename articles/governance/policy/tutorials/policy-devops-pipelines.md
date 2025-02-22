---
title: "Tutorial: Implement Azure Policy with Azure DevOps"
description: In this tutorial, you implement an Azure Policy with an Azure DevOps release pipeline.
ms.date: 03/24/2022
ms.topic: tutorial
ms.author: jukullam
ms.custom: devops-pipelines-deploy
---

# Implement Azure Policy with Azure DevOps release pipelines

**Azure DevOps Services**

Learn how to enforce compliance policies on your Azure resources before and after deployment with Azure Pipelines. Azure Pipelines lets you build, test, and deploy with continuous integration (CI) and continuous delivery (CD) using [Azure DevOps](/azure/devops/). One scenario for adding Azure Policy to a pipeline is when you want to ensure that resources are deployed only to authorized regions and are configured to send diagnostics logs to Azure Log Analytics. 

You'll need a [classic pipeline](/azure/devops/pipelines/release/define-multistage-release-process) to take advantage of Azure Policy. 

For more information, see [What is Azure Pipelines?](/azure/devops/pipelines/get-started/what-is-azure-pipelines)
and [Create your first pipeline](/azure/devops/pipelines/create-first-pipeline). 
## Prepare

1. Create an [Azure Policy](/azure/governance/policy/tutorials/create-and-manage) in the Azure portal.
   There are several [predefined sample policies](/azure/governance/policy/samples/)
   that can be applied to a management group, subscription, and resource group.

1. In Azure DevOps, create a release pipeline that contains at least one stage, or open an existing release pipeline.

1. Add a pre- or post-deployment condition that includes the **Security and compliance assessment** task as a gate.
   [More details](/azure/devops/pipelines/release/deploy-using-approvals.md#configure-gate).

   ![Screenshot of Azure Policy Gate.](../media/devops-policy/azure-policy-gate.png)

## Validate for any violation(s) during a release

> [!NOTE]
> Use the [AzurePolicyCheckGate](/azure/devops/pipelines/tasks/deploy/azure-policy) task to check for policy compliance in YAML. This task can only be used as a gate and not in a build or a release pipeline.  

1. Navigate to your team project in Azure DevOps.

1. In the **Pipelines** section, open the **Releases** page and create a new release.

1. Choose the **In progress** link in the release view to open the live logs page.

1. When the release is in progress and attempts to perform an action disallowed by
   the defined policy, the deployment is marked as **Failed**. The error message contains a link to view the policy violations.

   ![Screenshot of Azure Policy failure message.](../media/devops-policy/azure-policy-02.png)

1. An error message is written to the logs and displayed in the stage status panel in the releases page of Azure Pipelines.

   ![Screenshot of Azure Policy failure in log.](../media/devops-policy/azure-policy-03.png)

1. When the policy compliance gate passes the release, a **Succeeded** status is displayed.

   ![Screenshot of Policy Gates.](../media/devops-policy/policy-compliance-gates.png)

1. Choose the successful deployment to view the detailed logs.

   ![Screenshot of Policy Logs.](../media/devops-policy/policy-logs.png)

## Next steps

To learn more about the structures of policy definitions, look at this article:

> [!div class="nextstepaction"]
> [Azure Policy definition structure](../concepts/definition-structure.md)
