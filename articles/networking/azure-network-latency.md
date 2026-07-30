---
title: Azure network round-trip latency statistics
description: Learn about round-trip latency statistics between Azure regions.
services: networking
author: mbender-ms
ms.service: azure-virtual-network
ms.topic: concept-article
ms.date: 07/30/2026
ms.author: mbender
ms.custom: references_regions,updatedFY24S2
---

# Azure network round-trip latency statistics

This article provides round-trip latency statistics between Azure regions to help you optimize your cloud architecture and deployment decisions. The data comes from continuous network monitoring across Azure's global infrastructure and represents real-world performance measurements.

Use these statistics to:

- **Plan multi-region deployments** for optimal performance
- **Select regions** that minimize latency for your users
- **Design disaster recovery strategies** with latency considerations
- **Benchmark expected performance** between specific region pairs

## What is round-trip latency?

Round-trip latency is the time it takes for a data packet to travel from one point in the network to another and back again. In the context of Azure, it measures the time taken for a packet to travel between two Azure regions. This metric is crucial for applications that require low-latency communication, such as real-time data processing, gaming, and financial transactions.

## How is latency measured?

Azure measures round-trip latency using internal network probes that continuously monitor the performance of the Azure backbone network. These probes send data packets between Azure regions and record the time taken for the packets to travel to their destination and back. The measurements are collected in 1-minute intervals, providing a detailed view of network performance over time.

The latency statistics presented in this article are based on the 95th percentile (P95) of these measurements. This means that 95 percent of the measured round-trip times are at or below this value, providing a reliable indicator of near worst-case network performance.


## Round-trip latency data by region

The monthly Percentile P95 round trip times between Azure regions for a 30-day window are shown in the following tabs. The latency is measured in milliseconds (ms).

The current dataset was taken on *July 30, 2026*, and it covers the 30-day period ending on *July 30, 2026*.

For readability, each table is split into tabs for groups of Azure regions. The tabs are organized by regions, and then by source region in the first column of each table. For example, the *East US* tab also shows the latency from all source regions to the two *East US* regions: *East US* and *East US 2*. 

> [!IMPORTANT]
> Monthly latency numbers across Azure regions do not change on a regular basis. You can expect an update of these tables every 6 to 9 months. Not all public Azure regions are listed in the following tables. When new regions come online, we will update this document as soon as latency data is available.
> 
> You can perform VM-to-VM latency between regions using [test Virtual Machines](../virtual-network/virtual-network-test-latency.md) in your Azure subscription.

#### [North America / South America](#tab/Americas)

Latency tables for Americas regions including US, Canada, and Brazil.

Use the following tabs to view latency statistics for each region.

#### [Europe](#tab/Europe)

Latency tables for European regions.

Use the following tabs to view latency statistics for each region.

#### [Asia-Pacific (APAC)](#tab/APAC)

Latency tables for Australia, Asia, and Pacific regions including and Australia, Japan, Korea, and India.

Use the following tabs to view latency statistics for each region.

#### [Middle East / Africa](#tab/MEA)

Latency tables for Middle East / Africa regions including UAE, South Africa, Israel, and Qatar.

Use the following tabs to view latency statistics for each region.

---

#### [West US](#tab/WestUS/Americas)


| Source | West Central US | West US | West US 2 | West US 3 |
|---|---|---|---|---|
| Australia Central | 170 | 147 | 174 | 184 |
| Australia Central 2 | 183 | 148 | 175 | 183 |
| Australia East | 163 | 141 | 180 | 176 |
| Australia Southeast | 174 | 152 | 191 | 189 |
| Austria East | 149 | 170 | 170 | 170 |
| Belgium Central | 136 | 157 | 156 | 156 |
| Brazil South | 159 | 170 | 179 | 163 |
| Canada Central | 49 | 70 | 68 | 75 |
| Canada East | 58 | 78 | 78 | 89 |
| Central India | 242 | 224 | 218 | 240 |
| Central US | 19 | 41 | 41 | 49 |
| Denmark East | 130 | 154 | 153 | 156 |
| East Asia | 167 | 152 | 146 | 162 |
| East US | 54 | 74 | 75 | 70 |
| East US 2 | 49 | 71 | 71 | 60 |
| France Central | 132 | 152 | 153 | 138 |
| France South | 131 | 182 | 155 | 147 |
| Germany North | 139 | 162 | 160 | 156 |
| Germany West Central | 139 | 157 | 159 | 151 |
| Indonesia Central | 199 | 184 | 177 | 200 |
| Israel Central | 162 | 186 | 185 | 176 |
| Italy North | 146 | 167 | 168 | 167 |
| Japan East | 125 | 109 | 103 | 118 |
| Japan West | 133 | 116 | 109 | 122 |
| Jio India West | 260 | 246 | 239 | 262 |
| Korea Central | 150 | 133 | 127 | 143 |
| Korea South | 147 | 137 | 129 | 142 |
| Malaysia West | 192 | 176 | 169 | 192 |
| Mexico Central | 48 | 53 | 75 | 42 |
| New Zealand North | 158 | 145 | 140 | 159 |
| North Central US | 32 | 53 | 53 | 63 |
| North Europe | 116 | 137 | 136 | 133 |
| Norway East | 138 | 161 | 157 | 156 |
| Norway West | 136 | 158 | 157 | 163 |
| Poland Central | 152 | 168 | 171 | 164 |
| Qatar Central | 203 | 221 | 224 | 222 |
| South Africa North | 264 | 278 | 285 | 270 |
| South Africa West | 246 | 262 | 268 | 252 |
| South Central US | 29 | 44 | 57 | 32 |
| South India | 218 | 203 | 196 | 219 |
| Southeast Asia | 187 | 171 | 165 | 188 |
| Spain Central | 122 | 143 | 144 | 141 |
| Sweden Central | 149 | 168 | 165 | 172 |
| Switzerland North | 142 | 163 | 162 | 164 |
| Switzerland West | 139 | 158 | 158 | 160 |
| UAE Central | 235 | 251 | 254 | 246 |
| UAE North | 236 | 257 | 256 | 248 |
| UK South | 124 | 144 | 145 | 138 |
| UK West | 127 | 146 | 149 | 140 |
| West Central US |  | 27 | 27 | 39 |
| West Europe | 131 | 153 | 153 | 147 |
| West US | 27 |  | 26 | 23 |
| West US 2 | 26 | 25 |  | 44 |
| West US 3 | 36 | 22 | 42 |  |

#### [Central US](#tab/CentralUS/Americas)


| Source | Central US | North Central US | South Central US |
|---|---|---|---|
| Australia Central | 184 | 197 | 179 |
| Australia Central 2 | 187 | 197 | 170 |
| Australia East | 178 | 191 | 194 |
| Australia Southeast | 190 | 202 | 204 |
| Austria East | 136 | 124 | 143 |
| Belgium Central | 125 | 113 | 127 |
| Brazil South | 155 | 142 | 142 |
| Canada Central | 35 | 23 | 58 |
| Canada East | 45 | 33 | 66 |
| Central India | 245 | 234 | 249 |
| Central US |  | 19 | 30 |
| Denmark East | 127 | 112 | 130 |
| East Asia | 181 | 192 | 177 |
| East US | 35 | 26 | 44 |
| East US 2 | 41 | 31 | 33 |
| France Central | 120 | 108 | 118 |
| France South | 117 | 108 | 127 |
| Germany North | 128 | 118 | 133 |
| Germany West Central | 125 | 114 | 131 |
| Indonesia Central | 214 | 228 | 223 |
| Israel Central | 151 | 142 | 158 |
| Italy North | 132 | 120 | 142 |
| Japan East | 139 | 152 | 140 |
| Japan West | 147 | 158 | 137 |
| Jio India West | 274 | 264 | 282 |
| Korea Central | 163 | 175 | 165 |
| Korea South | 160 | 171 | 152 |
| Malaysia West | 206 | 218 | 216 |
| Mexico Central | 48 | 61 | 25 |
| New Zealand North | 172 | 184 | 176 |
| North Central US | 18 |  | 41 |
| North Europe | 107 | 95 | 112 |
| Norway East | 132 | 121 | 136 |
| Norway West | 132 | 121 | 136 |
| Poland Central | 134 | 125 | 143 |
| Qatar Central | 192 | 182 | 196 |
| South Africa North | 251 | 241 | 250 |
| South Africa West | 234 | 223 | 233 |
| South Central US | 29 | 42 |  |
| South India | 232 | 250 | 243 |
| Southeast Asia | 201 | 214 | 203 |
| Spain Central | 110 | 101 | 114 |
| Sweden Central | 142 | 132 | 143 |
| Switzerland North | 133 | 122 | 137 |
| Switzerland West | 125 | 115 | 134 |
| UAE Central | 208 | 203 | 227 |
| UAE North | 212 | 204 | 229 |
| UK South | 112 | 102 | 118 |
| UK West | 115 | 104 | 121 |
| West Central US | 20 | 34 | 30 |
| West Europe | 114 | 106 | 126 |
| West US | 42 | 55 | 38 |
| West US 2 | 41 | 54 | 58 |
| West US 3 | 52 | 59 | 25 |

#### [East US](#tab/EastUS/Americas)


| Source | East US | East US 2 |
|---|---|---|
| Australia Central | 210 | 230 |
| Australia Central 2 | 220 | 229 |
| Australia East | 206 | 224 |
| Australia Southeast | 217 | 236 |
| Austria East | 106 | 110 |
| Belgium Central | 94 | 93 |
| Brazil South | 121 | 121 |
| Canada Central | 21 | 25 |
| Canada East | 28 | 32 |
| Central India | 218 | 220 |
| Central US | 35 | 42 |
| Denmark East | 92 | 96 |
| East Asia | 208 | 209 |
| East US |  | 11 |
| East US 2 | 11 |  |
| France Central | 90 | 89 |
| France South | 92 | 93 |
| Germany North | 100 | 103 |
| Germany West Central | 97 | 98 |
| Indonesia Central | 241 | 244 |
| Israel Central | 126 | 132 |
| Italy North | 107 | 107 |
| Japan East | 165 | 168 |
| Japan West | 171 | 174 |
| Jio India West | 224 | 231 |
| Korea Central | 192 | 192 |
| Korea South | 190 | 187 |
| Malaysia West | 234 | 236 |
| Mexico Central | 66 | 60 |
| New Zealand North | 200 | 202 |
| North Central US | 24 | 29 |
| North Europe | 76 | 79 |
| Norway East | 100 | 104 |
| Norway West | 96 | 101 |
| Poland Central | 112 | 115 |
| Qatar Central | 165 | 181 |
| South Africa North | 225 | 222 |
| South Africa West | 208 | 203 |
| South Central US | 47 | 42 |
| South India | 246 | 248 |
| Southeast Asia | 229 | 232 |
| Spain Central | 84 | 80 |
| Sweden Central | 108 | 114 |
| Switzerland North | 104 | 103 |
| Switzerland West | 96 | 101 |
| UAE Central | 186 | 193 |
| UAE North | 191 | 194 |
| UK South | 80 | 87 |
| UK West | 83 | 89 |
| West Central US | 55 | 51 |
| West Europe | 91 | 94 |
| West US | 72 | 71 |
| West US 2 | 76 | 71 |
| West US 3 | 65 | 60 |

#### [Canada](#tab/Canada/Americas)


| Source | Canada Central | Canada East |
|---|---|---|
| Australia Central | 210 | 221 |
| Australia Central 2 | 210 | 221 |
| Australia East | 207 | 215 |
| Australia Southeast | 218 | 226 |
| Austria East | 112 | 106 |
| Belgium Central | 97 | 92 |
| Brazil South | 133 | 134 |
| Canada Central |  | 14 |
| Canada East | 16 |  |
| Central India | 216 | 212 |
| Central US | 35 | 48 |
| Denmark East | 99 | 92 |
| East Asia | 205 | 219 |
| East US | 22 | 27 |
| East US 2 | 24 | 30 |
| France Central | 91 | 87 |
| France South | 91 | 84 |
| Germany North | 103 | 98 |
| Germany West Central | 100 | 96 |
| Indonesia Central | 238 | 245 |
| Israel Central | 126 | 121 |
| Italy North | 106 | 99 |
| Japan East | 165 | 176 |
| Japan West | 172 | 182 |
| Jio India West | 219 | 215 |
| Korea Central | 189 | 200 |
| Korea South | 183 | 192 |
| Malaysia West | 230 | 239 |
| Mexico Central | 75 | 84 |
| New Zealand North | 192 | 206 |
| North Central US | 22 | 31 |
| North Europe | 80 | 75 |
| Norway East | 105 | 100 |
| Norway West | 98 | 96 |
| Poland Central | 114 | 110 |
| Qatar Central | 166 | 161 |
| South Africa North | 235 | 231 |
| South Africa West | 216 | 211 |
| South Central US | 57 | 65 |
| South India | 244 | 240 |
| Southeast Asia | 226 | 237 |
| Spain Central | 93 | 88 |
| Sweden Central | 112 | 109 |
| Switzerland North | 102 | 97 |
| Switzerland West | 99 | 93 |
| UAE Central | 184 | 177 |
| UAE North | 187 | 183 |
| UK South | 84 | 78 |
| UK West | 86 | 80 |
| West Central US | 49 | 57 |
| West Europe | 93 | 88 |
| West US | 71 | 78 |
| West US 2 | 69 | 77 |
| West US 3 | 81 | 90 |

#### [South America](#tab/SouthAmerica/Americas)


| Source | Brazil South | Mexico Central |
|---|---|---|
| Australia Central | 302 | 184 |
| Australia Central 2 | 301 | 185 |
| Australia East | 298 | 210 |
| Australia Southeast | 310 | 202 |
| Austria East | 206 | 162 |
| Belgium Central | 196 | 148 |
| Brazil South |  | 159 |
| Canada Central | 132 | 74 |
| Canada East | 134 | 81 |
| Central India | 320 | 267 |
| Central US | 154 | 48 |
| Denmark East | 190 | 147 |
| East Asia | 315 | 197 |
| East US | 119 | 63 |
| East US 2 | 121 | 50 |
| France Central | 192 | 132 |
| France South | 194 | 141 |
| Germany North | 200 | 142 |
| Germany West Central | 199 | 145 |
| Indonesia Central | 349 | 232 |
| Israel Central | 228 | 171 |
| Italy North | 206 | 158 |
| Japan East | 275 | 147 |
| Japan West | 271 | 153 |
| Jio India West | 318 | 277 |
| Korea Central | 296 | 172 |
| Korea South | 283 | 162 |
| Malaysia West | 342 | 227 |
| Mexico Central | 158 |  |
| New Zealand North | 309 | 183 |
| North Central US | 141 | 59 |
| North Europe | 176 | 121 |
| Norway East | 199 | 143 |
| Norway West | 195 | 153 |
| Poland Central | 212 | 150 |
| Qatar Central | 265 | 213 |
| South Africa North | 326 | 268 |
| South Africa West | 309 | 245 |
| South Central US | 142 | 24 |
| South India | 334 | 252 |
| Southeast Asia | 337 | 220 |
| Spain Central | 185 | 133 |
| Sweden Central | 204 | 161 |
| Switzerland North | 202 | 154 |
| Switzerland West | 198 | 150 |
| UAE Central | 285 | 222 |
| UAE North | 288 | 231 |
| UK South | 183 | 132 |
| UK West | 188 | 135 |
| West Central US | 159 | 48 |
| West Europe | 189 | 135 |
| West US | 171 | 54 |
| West US 2 | 179 | 74 |
| West US 3 | 166 | 43 |

#### [Western Europe](#tab/WesternEurope/Europe)


| Source | Belgium Central | France Central | France South | Spain Central | Switzerland North | Switzerland West | West Europe |
|---|---|---|---|---|---|---|---|
| Australia Central | 252 | 248 | 263 | 261 | 246 | 245 | 266 |
| Australia Central 2 | 253 | 248 | 237 | 251 | 247 | 245 | 257 |
| Australia East | 285 | 280 | 273 | 265 | 286 | 289 | 282 |
| Australia Southeast | 267 | 287 | 254 | 276 | 294 | 267 | 292 |
| Austria East | 22 | 23 | 27 | 39 | 19 | 22 | 24 |
| Belgium Central |  | 11 | 20 | 26 | 17 | 20 | 10 |
| Brazil South | 197 | 193 | 193 | 184 | 204 | 202 | 191 |
| Canada Central | 96 | 92 | 90 | 92 | 101 | 97 | 92 |
| Canada East | 93 | 88 | 84 | 88 | 97 | 94 | 88 |
| Central India | 150 | 147 | 134 | 149 | 146 | 143 | 153 |
| Central US | 122 | 120 | 117 | 110 | 130 | 126 | 118 |
| Denmark East | 21 | 27 | 33 | 40 | 25 | 27 | 16 |
| East Asia | 214 | 279 | 224 | 229 | 237 | 235 | 279 |
| East US | 93 | 90 | 90 | 83 | 104 | 96 | 89 |
| East US 2 | 93 | 89 | 93 | 79 | 103 | 101 | 93 |
| France Central | 10 |  | 15 | 21 | 18 | 16 | 15 |
| France South | 20 | 17 |  | 19 | 15 | 13 | 24 |
| Germany North | 19 | 21 | 28 | 37 | 18 | 23 | 16 |
| Germany West Central | 12 | 14 | 21 | 30 | 12 | 17 | 14 |
| Indonesia Central | 181 | 176 | 154 | 214 | 178 | 174 | 182 |
| Israel Central | 65 | 62 | 45 | 59 | 55 | 58 | 66 |
| Italy North | 23 | 26 | 18 | 39 | 12 | 16 | 28 |
| Japan East | 244 | 245 | 240 | 227 | 254 | 255 | 242 |
| Japan West | 228 | 247 | 227 | 233 | 256 | 239 | 246 |
| Jio India West | 153 | 148 | 126 | 149 | 138 | 134 | 163 |
| Korea Central | 248 | 266 | 234 | 262 | 276 | 280 | 267 |
| Korea South | 216 | 263 | 201 | 215 | 211 | 209 | 261 |
| Malaysia West | 173 | 179 | 146 | 187 | 170 | 164 | 186 |
| Mexico Central | 136 | 141 | 144 | 121 | 154 | 150 | 145 |
| New Zealand North | 282 | 272 | 280 | 283 | 279 | 274 | 273 |
| North Central US | 110 | 109 | 106 | 98 | 120 | 114 | 106 |
| North Europe | 24 | 22 | 30 | 35 | 32 | 37 | 19 |
| Norway East | 28 | 32 | 39 | 47 | 30 | 35 | 24 |
| Norway West | 24 | 28 | 39 | 42 | 33 | 37 | 26 |
| Poland Central | 30 | 34 | 39 | 50 | 30 | 33 | 28 |
| Qatar Central | 124 | 87 | 74 | 122 | 85 | 84 | 94 |
| South Africa North | 174 | 165 | 163 | 149 | 174 | 171 | 171 |
| South Africa West | 150 | 148 | 152 | 129 | 153 | 151 | 154 |
| South Central US | 123 | 122 | 127 | 108 | 136 | 134 | 127 |
| South India | 142 | 164 | 152 | 169 | 162 | 158 | 169 |
| Southeast Asia | 228 | 175 | 157 | 228 | 173 | 172 | 181 |
| Spain Central | 26 | 23 | 19 |  | 29 | 27 | 30 |
| Sweden Central | 35 | 40 | 47 | 54 | 34 | 39 | 31 |
| Switzerland North | 19 | 19 | 15 | 29 |  | 10 | 20 |
| Switzerland West | 19 | 18 | 11 | 26 | 10 |  | 23 |
| UAE Central | 118 | 114 | 102 | 117 | 102 | 106 | 114 |
| UAE North | 118 | 117 | 104 | 118 | 105 | 110 | 124 |
| UK South | 16 | 13 | 21 | 26 | 25 | 22 | 12 |
| UK West | 20 | 17 | 26 | 30 | 30 | 27 | 17 |
| West Central US | 135 | 132 | 131 | 122 | 142 | 138 | 128 |
| West Europe | 10 | 15 | 23 | 29 | 21 | 23 |  |
| West US | 154 | 152 | 163 | 138 | 162 | 157 | 151 |
| West US 2 | 155 | 153 | 154 | 142 | 161 | 156 | 147 |
| West US 3 | 146 | 137 | 146 | 127 | 152 | 147 | 145 |

#### [Central Europe](#tab/CentralEurope/Europe)


| Source | Austria East | Germany North | Germany West Central | Italy North | Poland Central |
|---|---|---|---|---|---|
| Australia Central | 262 | 259 | 254 | 254 | 271 |
| Australia Central 2 | 262 | 260 | 253 | 253 | 271 |
| Australia East | 295 | 293 | 291 | 286 | 300 |
| Australia Southeast | 280 | 301 | 299 | 295 | 307 |
| Austria East |  | 21 | 16 | 20 | 18 |
| Belgium Central | 23 | 19 | 13 | 26 | 29 |
| Brazil South | 208 | 200 | 201 | 208 | 211 |
| Canada Central | 112 | 101 | 101 | 105 | 114 |
| Canada East | 109 | 98 | 97 | 101 | 111 |
| Central India | 150 | 158 | 151 | 146 | 169 |
| Central US | 133 | 126 | 125 | 133 | 134 |
| Denmark East | 28 | 14 | 18 | 32 | 23 |
| East Asia | 245 | 242 | 244 | 245 | 247 |
| East US | 106 | 97 | 97 | 105 | 104 |
| East US 2 | 112 | 103 | 100 | 107 | 114 |
| France Central | 24 | 19 | 14 | 25 | 33 |
| France South | 29 | 28 | 23 | 22 | 39 |
| Germany North | 23 |  | 14 | 26 | 21 |
| Germany West Central | 17 | 12 |  | 21 | 26 |
| Indonesia Central | 179 | 203 | 186 | 195 | 215 |
| Israel Central | 51 | 65 | 60 | 54 | 61 |
| Italy North | 19 | 23 | 18 |  | 31 |
| Japan East | 258 | 251 | 250 | 256 | 260 |
| Japan West | 262 | 255 | 253 | 261 | 264 |
| Jio India West | 153 | 153 | 152 | 150 | 171 |
| Korea Central | 286 | 278 | 271 | 276 | 285 |
| Korea South | 250 | 224 | 245 | 219 | 235 |
| Malaysia West | 181 | 184 | 178 | 187 | 207 |
| Mexico Central | 153 | 153 | 151 | 160 | 162 |
| New Zealand North | 284 | 283 | 294 | 290 | 294 |
| North Central US | 122 | 118 | 115 | 121 | 125 |
| North Europe | 39 | 29 | 29 | 42 | 38 |
| Norway East | 36 | 22 | 26 | 39 | 30 |
| Norway West | 40 | 27 | 30 | 42 | 35 |
| Poland Central | 20 | 21 | 26 | 32 |  |
| Qatar Central | 131 | 97 | 93 | 99 | 110 |
| South Africa North | 184 | 186 | 174 | 179 | 198 |
| South Africa West | 166 | 160 | 157 | 160 | 173 |
| South Central US | 140 | 136 | 132 | 142 | 145 |
| South India | 177 | 178 | 168 | 161 | 181 |
| Southeast Asia | 187 | 236 | 179 | 182 | 202 |
| Spain Central | 41 | 37 | 32 | 37 | 50 |
| Sweden Central | 39 | 28 | 31 | 45 | 28 |
| Switzerland North | 20 | 18 | 12 | 13 | 30 |
| Switzerland West | 24 | 21 | 16 | 17 | 32 |
| UAE Central | 126 | 119 | 120 | 114 | 129 |
| UAE North | 127 | 127 | 122 | 117 | 138 |
| UK South | 31 | 24 | 20 | 32 | 34 |
| UK West | 37 | 24 | 25 | 37 | 37 |
| West Central US | 148 | 140 | 140 | 147 | 149 |
| West Europe | 26 | 17 | 14 | 29 | 28 |
| West US | 170 | 162 | 158 | 166 | 167 |
| West US 2 | 169 | 159 | 160 | 166 | 167 |
| West US 3 | 160 | 155 | 150 | 161 | 166 |

#### [Nordic Countries](#tab/Nordic/Europe)


| Source | Denmark East | Norway East | Norway West | Sweden Central |
|---|---|---|---|---|
| Australia Central | 271 | 271 | 268 | 284 |
| Australia Central 2 | 267 | 270 | 268 | 281 |
| Australia East | 288 | 294 | 280 | 307 |
| Australia Southeast | 291 | 283 | 258 | 311 |
| Austria East | 30 | 34 | 38 | 41 |
| Belgium Central | 25 | 29 | 24 | 38 |
| Brazil South | 195 | 200 | 196 | 209 |
| Canada Central | 100 | 104 | 96 | 115 |
| Canada East | 96 | 100 | 96 | 112 |
| Central India | 159 | 170 | 162 | 179 |
| Central US | 127 | 131 | 130 | 142 |
| Denmark East |  | 15 | 19 | 25 |
| East Asia | 225 | 257 | 204 | 265 |
| East US | 95 | 98 | 96 | 110 |
| East US 2 | 100 | 104 | 102 | 115 |
| France Central | 29 | 32 | 26 | 43 |
| France South | 39 | 40 | 38 | 50 |
| Germany North | 18 | 21 | 27 | 31 |
| Germany West Central | 20 | 24 | 29 | 34 |
| Indonesia Central | 248 | 204 | 186 | 226 |
| Israel Central | 72 | 78 | 81 | 84 |
| Italy North | 37 | 37 | 41 | 45 |
| Japan East | 248 | 254 | 252 | 260 |
| Japan West | 251 | 256 | 244 | 266 |
| Jio India West | 157 | 171 | 159 | 179 |
| Korea Central | 275 | 280 | 262 | 286 |
| Korea South | 233 | 235 | 232 | 267 |
| Malaysia West | 202 | 194 | 179 | 213 |
| Mexico Central | 140 | 155 | 153 | 161 |
| New Zealand North | 286 | 289 | 277 | 300 |
| North Central US | 116 | 121 | 118 | 132 |
| North Europe | 26 | 30 | 28 | 40 |
| Norway East | 18 |  | 11 | 18 |
| Norway West | 24 | 12 |  | 22 |
| Poland Central | 28 | 30 | 35 | 30 |
| Qatar Central | 136 | 110 | 106 | 121 |
| South Africa North | 190 | 189 | 192 | 196 |
| South Africa West | 166 | 171 | 166 | 182 |
| South Central US | 129 | 138 | 135 | 146 |
| South India | 156 | 183 | 170 | 194 |
| Southeast Asia | 235 | 243 | 186 | 256 |
| Spain Central | 44 | 48 | 42 | 57 |
| Sweden Central | 26 | 15 | 19 |  |
| Switzerland North | 29 | 31 | 33 | 39 |
| Switzerland West | 32 | 34 | 36 | 42 |
| UAE Central | 131 | 127 | 116 | 145 |
| UAE North | 131 | 140 | 134 | 149 |
| UK South | 27 | 26 | 19 | 36 |
| UK West | 29 | 31 | 23 | 41 |
| West Central US | 134 | 138 | 134 | 146 |
| West Europe | 20 | 25 | 25 | 31 |
| West US | 158 | 161 | 156 | 169 |
| West US 2 | 151 | 156 | 154 | 165 |
| West US 3 | 150 | 160 | 154 | 166 |

#### [UK / Northern Europe](#tab/NorthernEurope/Europe)


| Source | North Europe | UK South | UK West |
|---|---|---|---|
| Australia Central | 270 | 266 | 268 |
| Australia Central 2 | 267 | 258 | 259 |
| Australia East | 272 | 277 | 279 |
| Australia Southeast | 281 | 286 | 288 |
| Austria East | 38 | 29 | 34 |
| Belgium Central | 23 | 16 | 20 |
| Brazil South | 176 | 184 | 187 |
| Canada Central | 78 | 83 | 84 |
| Canada East | 74 | 79 | 80 |
| Central India | 159 | 150 | 154 |
| Central US | 107 | 117 | 120 |
| Denmark East | 22 | 23 | 24 |
| East Asia | 265 | 274 | 275 |
| East US | 74 | 80 | 82 |
| East US 2 | 79 | 87 | 87 |
| France Central | 20 | 12 | 16 |
| France South | 31 | 22 | 25 |
| Germany North | 28 | 24 | 24 |
| Germany West Central | 28 | 19 | 24 |
| Indonesia Central | 243 | 198 | 202 |
| Israel Central | 81 | 69 | 70 |
| Italy North | 40 | 32 | 36 |
| Japan East | 232 | 237 | 242 |
| Japan West | 236 | 241 | 246 |
| Jio India West | 171 | 158 | 154 |
| Korea Central | 255 | 262 | 263 |
| Korea South | 248 | 256 | 242 |
| Malaysia West | 231 | 189 | 194 |
| Mexico Central | 131 | 140 | 143 |
| New Zealand North | 265 | 276 | 280 |
| North Central US | 94 | 100 | 102 |
| North Europe |  | 15 | 18 |
| Norway East | 30 | 26 | 30 |
| Norway West | 27 | 19 | 23 |
| Poland Central | 39 | 34 | 37 |
| Qatar Central | 100 | 92 | 95 |
| South Africa North | 178 | 169 | 171 |
| South Africa West | 160 | 152 | 154 |
| South Central US | 113 | 120 | 123 |
| South India | 175 | 163 | 167 |
| Southeast Asia | 236 | 183 | 187 |
| Spain Central | 35 | 27 | 29 |
| Sweden Central | 37 | 34 | 39 |
| Switzerland North | 33 | 25 | 30 |
| Switzerland West | 35 | 21 | 25 |
| UAE Central | 128 | 119 | 123 |
| UAE North | 130 | 122 | 126 |
| UK South | 14 |  | 9 |
| UK West | 18 | 10 |  |
| West Central US | 116 | 124 | 127 |
| West Europe | 20 | 13 | 17 |
| West US | 138 | 144 | 146 |
| West US 2 | 135 | 144 | 148 |
| West US 3 | 132 | 141 | 138 |

#### [Australia / New Zealand](#tab/Australasia/APAC)


| Source | Australia Central | Australia Central 2 | Australia East | Australia Southeast | New Zealand North |
|---|---|---|---|---|---|
| Australia Central |  | 5 | 10 | 19 | 37 |
| Australia Central 2 | 7 |  | 12 | 16 | 41 |
| Australia East | 12 | 11 |  | 16 | 31 |
| Australia Southeast | 19 | 14 | 17 |  | 42 |
| Austria East | 262 | 259 | 292 | 278 | 287 |
| Belgium Central | 253 | 252 | 284 | 266 | 279 |
| Brazil South | 302 | 301 | 298 | 310 | 311 |
| Canada Central | 209 | 208 | 207 | 217 | 197 |
| Canada East | 222 | 221 | 216 | 227 | 210 |
| Central India | 154 | 155 | 152 | 145 | 178 |
| Central US | 185 | 187 | 178 | 188 | 174 |
| Denmark East | 266 | 263 | 279 | 270 | 278 |
| East Asia | 128 | 128 | 128 | 130 | 147 |
| East US | 209 | 213 | 207 | 217 | 198 |
| East US 2 | 230 | 230 | 224 | 234 | 205 |
| France Central | 249 | 246 | 279 | 285 | 268 |
| France South | 263 | 236 | 273 | 254 | 325 |
| Germany North | 261 | 259 | 293 | 301 | 287 |
| Germany West Central | 254 | 252 | 290 | 299 | 296 |
| Indonesia Central | 113 | 111 | 114 | 102 | 138 |
| Israel Central | 276 | 274 | 272 | 267 | 296 |
| Italy North | 253 | 252 | 285 | 292 | 288 |
| Japan East | 111 | 136 | 105 | 115 | 130 |
| Japan West | 116 | 115 | 111 | 122 | 138 |
| Jio India West | 176 | 175 | 177 | 167 | 201 |
| Korea Central | 136 | 133 | 132 | 142 | 157 |
| Korea South | 131 | 124 | 132 | 144 | 150 |
| Malaysia West | 113 | 105 | 125 | 94 | 131 |
| Mexico Central | 184 | 184 | 184 | 194 | 181 |
| New Zealand North | 36 | 40 | 30 | 42 |  |
| North Central US | 194 | 194 | 189 | 199 | 184 |
| North Europe | 270 | 267 | 272 | 281 | 271 |
| Norway East | 272 | 270 | 294 | 284 | 290 |
| Norway West | 270 | 268 | 280 | 258 | 278 |
| Poland Central | 272 | 270 | 300 | 306 | 298 |
| Qatar Central | 190 | 188 | 190 | 179 | 215 |
| South Africa North | 280 | 278 | 348 | 340 | 340 |
| South Africa West | 295 | 294 | 341 | 340 | 315 |
| South Central US | 175 | 174 | 172 | 183 | 172 |
| South India | 134 | 131 | 134 | 122 | 158 |
| Southeast Asia | 101 | 99 | 98 | 89 | 123 |
| Spain Central | 252 | 251 | 272 | 276 | 275 |
| Sweden Central | 279 | 277 | 303 | 307 | 300 |
| Switzerland North | 248 | 246 | 286 | 274 | 279 |
| Switzerland West | 245 | 242 | 288 | 264 | 275 |
| UAE Central | 181 | 179 | 181 | 170 | 206 |
| UAE North | 182 | 179 | 182 | 171 | 206 |
| UK South | 266 | 262 | 277 | 286 | 281 |
| UK West | 270 | 261 | 280 | 288 | 296 |
| West Central US | 171 | 175 | 164 | 174 | 161 |
| West Europe | 256 | 255 | 282 | 291 | 275 |
| West US | 148 | 148 | 142 | 152 | 155 |
| West US 2 | 173 | 174 | 179 | 190 | 145 |
| West US 3 | 172 | 181 | 169 | 185 | 165 |

#### [Japan](#tab/Japan/APAC)


| Source | Japan East | Japan West |
|---|---|---|
| Australia Central | 111 | 117 |
| Australia Central 2 | 137 | 116 |
| Australia East | 105 | 113 |
| Australia Southeast | 116 | 124 |
| Austria East | 261 | 251 |
| Belgium Central | 248 | 228 |
| Brazil South | 265 | 273 |
| Canada Central | 165 | 171 |
| Canada East | 177 | 182 |
| Central India | 129 | 130 |
| Central US | 141 | 149 |
| Denmark East | 253 | 246 |
| East Asia | 53 | 52 |
| East US | 165 | 173 |
| East US 2 | 167 | 174 |
| France Central | 241 | 247 |
| France South | 240 | 228 |
| Germany North | 249 | 256 |
| Germany West Central | 246 | 252 |
| Indonesia Central | 87 | 89 |
| Israel Central | 250 | 250 |
| Italy North | 256 | 260 |
| Japan East |  | 14 |
| Japan West | 15 |  |
| Jio India West | 151 | 151 |
| Korea Central | 36 | 27 |
| Korea South | 30 | 22 |
| Malaysia West | 78 | 80 |
| Mexico Central | 147 | 154 |
| New Zealand North | 131 | 138 |
| North Central US | 150 | 158 |
| North Europe | 232 | 238 |
| Norway East | 252 | 256 |
| Norway West | 252 | 244 |
| Poland Central | 258 | 264 |
| Qatar Central | 172 | 165 |
| South Africa North | 255 | 257 |
| South Africa West | 310 | 273 |
| South Central US | 140 | 146 |
| South India | 108 | 109 |
| Southeast Asia | 74 | 76 |
| Spain Central | 238 | 235 |
| Sweden Central | 258 | 263 |
| Switzerland North | 254 | 245 |
| Switzerland West | 256 | 241 |
| UAE Central | 156 | 156 |
| UAE North | 155 | 155 |
| UK South | 235 | 241 |
| UK West | 240 | 246 |
| West Central US | 125 | 133 |
| West Europe | 240 | 246 |
| West US | 110 | 118 |
| West US 2 | 102 | 110 |
| West US 3 | 121 | 124 |

#### [Korea](#tab/Korea/APAC)


| Source | Korea Central | Korea South |
|---|---|---|
| Australia Central | 145 | 135 |
| Australia Central 2 | 141 | 124 |
| Australia East | 137 | 133 |
| Australia Southeast | 149 | 145 |
| Austria East | 282 | 248 |
| Belgium Central | 248 | 216 |
| Brazil South | 289 | 283 |
| Canada Central | 190 | 182 |
| Canada East | 201 | 192 |
| Central India | 127 | 122 |
| Central US | 165 | 162 |
| Denmark East | 264 | 231 |
| East Asia | 43 | 38 |
| East US | 191 | 188 |
| East US 2 | 192 | 187 |
| France Central | 267 | 262 |
| France South | 235 | 201 |
| Germany North | 280 | 224 |
| Germany West Central | 272 | 245 |
| Indonesia Central | 83 | 76 |
| Israel Central | 245 | 239 |
| Italy North | 278 | 219 |
| Japan East | 35 | 29 |
| Japan West | 26 | 21 |
| Jio India West | 146 | 141 |
| Korea Central |  | 10 |
| Korea South | 11 |  |
| Malaysia West | 71 | 65 |
| Mexico Central | 172 | 161 |
| New Zealand North | 157 | 150 |
| North Central US | 174 | 170 |
| North Europe | 255 | 248 |
| Norway East | 280 | 235 |
| Norway West | 262 | 232 |
| Poland Central | 288 | 235 |
| Qatar Central | 162 | 154 |
| South Africa North | 255 | 243 |
| South Africa West | 302 | 260 |
| South Central US | 164 | 159 |
| South India | 104 | 100 |
| Southeast Asia | 72 | 68 |
| Spain Central | 262 | 215 |
| Sweden Central | 284 | 262 |
| Switzerland North | 277 | 211 |
| Switzerland West | 279 | 208 |
| UAE Central | 152 | 164 |
| UAE North | 153 | 161 |
| UK South | 261 | 256 |
| UK West | 264 | 243 |
| West Central US | 150 | 147 |
| West Europe | 267 | 260 |
| West US | 134 | 136 |
| West US 2 | 128 | 128 |
| West US 3 | 144 | 141 |

#### [India](#tab/India/APAC)


| Source | Central India | Jio India West | South India |
|---|---|---|---|
| Australia Central | 153 | 170 | 132 |
| Australia Central 2 | 155 | 170 | 132 |
| Australia East | 151 | 167 | 132 |
| Australia Southeast | 145 | 161 | 123 |
| Austria East | 146 | 154 | 172 |
| Belgium Central | 148 | 152 | 143 |
| Brazil South | 320 | 320 | 349 |
| Canada Central | 216 | 218 | 248 |
| Canada East | 212 | 215 | 244 |
| Central India |  | 41 | 24 |
| Central US | 247 | 272 | 231 |
| Denmark East | 150 | 154 | 155 |
| East Asia | 96 | 112 | 75 |
| East US | 214 | 226 | 244 |
| East US 2 | 219 | 231 | 251 |
| France Central | 147 | 150 | 165 |
| France South | 134 | 126 | 156 |
| Germany North | 159 | 151 | 180 |
| Germany West Central | 150 | 152 | 169 |
| Indonesia Central | 74 | 95 | 51 |
| Israel Central | 157 | 173 | 169 |
| Italy North | 144 | 149 | 160 |
| Japan East | 129 | 151 | 107 |
| Japan West | 129 | 146 | 108 |
| Jio India West | 41 |  | 49 |
| Korea Central | 126 | 146 | 103 |
| Korea South | 122 | 136 | 100 |
| Malaysia West | 65 | 87 | 43 |
| Mexico Central | 269 | 277 | 251 |
| New Zealand North | 180 | 202 | 157 |
| North Central US | 232 | 261 | 248 |
| North Europe | 160 | 171 | 181 |
| Norway East | 170 | 172 | 190 |
| Norway West | 158 | 159 | 169 |
| Poland Central | 169 | 170 | 195 |
| Qatar Central | 47 | 78 | 66 |
| South Africa North | 134 | 151 | 156 |
| South Africa West | 154 | 172 | 175 |
| South Central US | 246 | 282 | 242 |
| South India | 25 | 49 |  |
| Southeast Asia | 58 | 76 | 39 |
| Spain Central | 148 | 151 | 166 |
| Sweden Central | 174 | 177 | 191 |
| Switzerland North | 145 | 137 | 162 |
| Switzerland West | 142 | 134 | 157 |
| UAE Central | 35 | 53 | 57 |
| UAE North | 34 | 53 | 55 |
| UK South | 151 | 161 | 174 |
| UK West | 154 | 156 | 175 |
| West Central US | 242 | 252 | 218 |
| West Europe | 153 | 163 | 174 |
| West US | 224 | 240 | 203 |
| West US 2 | 218 | 233 | 196 |
| West US 3 | 243 | 256 | 220 |

#### [Asia](#tab/Asia/APAC)


| Source | East Asia | Indonesia Central | Malaysia West | Southeast Asia |
|---|---|---|---|---|
| Australia Central | 126 | 112 | 128 | 100 |
| Australia Central 2 | 128 | 111 | 106 | 100 |
| Australia East | 127 | 110 | 125 | 98 |
| Australia Southeast | 130 | 101 | 94 | 90 |
| Austria East | 245 | 178 | 180 | 190 |
| Belgium Central | 245 | 182 | 175 | 186 |
| Brazil South | 315 | 348 | 340 | 337 |
| Canada Central | 205 | 236 | 229 | 226 |
| Canada East | 219 | 245 | 241 | 238 |
| Central India | 95 | 74 | 64 | 59 |
| Central US | 183 | 213 | 205 | 201 |
| Denmark East | 217 | 194 | 187 | 186 |
| East Asia |  | 52 | 39 | 41 |
| East US | 207 | 240 | 233 | 229 |
| East US 2 | 208 | 243 | 235 | 232 |
| France Central | 278 | 175 | 177 | 176 |
| France South | 225 | 154 | 146 | 159 |
| Germany North | 243 | 203 | 190 | 237 |
| Germany West Central | 244 | 182 | 181 | 179 |
| Indonesia Central | 52 |  | 23 | 19 |
| Israel Central | 214 | 195 | 185 | 181 |
| Italy North | 246 | 194 | 186 | 184 |
| Japan East | 51 | 86 | 77 | 74 |
| Japan West | 50 | 88 | 78 | 74 |
| Jio India West | 112 | 95 | 87 | 82 |
| Korea Central | 41 | 82 | 70 | 71 |
| Korea South | 36 | 76 | 65 | 69 |
| Malaysia West | 38 | 23 |  | 11 |
| Mexico Central | 195 | 232 | 226 | 221 |
| New Zealand North | 154 | 138 | 130 | 126 |
| North Central US | 191 | 226 | 216 | 213 |
| North Europe | 266 | 251 | 236 | 236 |
| Norway East | 256 | 255 | 208 | 243 |
| Norway West | 206 | 186 | 179 | 186 |
| Poland Central | 250 | 214 | 202 | 201 |
| Qatar Central | 129 | 108 | 100 | 99 |
| South Africa North | 272 | 208 | 190 | 211 |
| South Africa West | 269 | 215 | 208 | 241 |
| South Central US | 183 | 222 | 215 | 211 |
| South India | 74 | 51 | 43 | 39 |
| Southeast Asia | 40 | 18 | 10 |  |
| Spain Central | 242 | 197 | 189 | 227 |
| Sweden Central | 259 | 221 | 212 | 206 |
| Switzerland North | 239 | 178 | 170 | 177 |
| Switzerland West | 239 | 173 | 163 | 175 |
| UAE Central | 122 | 100 | 91 | 86 |
| UAE North | 119 | 99 | 91 | 87 |
| UK South | 274 | 199 | 185 | 183 |
| UK West | 278 | 202 | 191 | 187 |
| West Central US | 166 | 198 | 192 | 187 |
| West Europe | 278 | 182 | 186 | 182 |
| West US | 151 | 184 | 175 | 172 |
| West US 2 | 144 | 176 | 168 | 165 |
| West US 3 | 160 | 205 | 190 | 187 |

#### [Middle East](#tab/MiddleEast/MEA)


| Source | Israel Central | Qatar Central | UAE Central | UAE North |
|---|---|---|---|---|
| Australia Central | 276 | 188 | 179 | 180 |
| Australia Central 2 | 275 | 188 | 179 | 178 |
| Australia East | 273 | 186 | 178 | 179 |
| Australia Southeast | 266 | 180 | 171 | 172 |
| Austria East | 57 | 98 | 114 | 124 |
| Belgium Central | 73 | 90 | 108 | 109 |
| Brazil South | 228 | 292 | 286 | 293 |
| Canada Central | 128 | 192 | 184 | 187 |
| Canada East | 124 | 189 | 181 | 183 |
| Central India | 158 | 48 | 34 | 35 |
| Central US | 150 | 216 | 211 | 212 |
| Denmark East | 78 | 102 | 110 | 120 |
| East Asia | 214 | 131 | 122 | 120 |
| East US | 126 | 191 | 184 | 190 |
| East US 2 | 131 | 195 | 194 | 194 |
| France Central | 61 | 121 | 115 | 116 |
| France South | 45 | 110 | 104 | 104 |
| Germany North | 64 | 132 | 126 | 128 |
| Germany West Central | 58 | 124 | 121 | 122 |
| Indonesia Central | 194 | 108 | 99 | 100 |
| Israel Central |  | 146 | 139 | 143 |
| Italy North | 53 | 92 | 113 | 115 |
| Japan East | 250 | 171 | 155 | 155 |
| Japan West | 251 | 165 | 156 | 155 |
| Jio India West | 172 | 79 | 53 | 53 |
| Korea Central | 246 | 162 | 152 | 153 |
| Korea South | 240 | 154 | 154 | 156 |
| Malaysia West | 186 | 101 | 92 | 91 |
| Mexico Central | 182 | 213 | 220 | 231 |
| New Zealand North | 304 | 216 | 206 | 206 |
| North Central US | 143 | 178 | 202 | 203 |
| North Europe | 80 | 135 | 129 | 131 |
| Norway East | 77 | 143 | 136 | 140 |
| Norway West | 88 | 106 | 121 | 135 |
| Poland Central | 61 | 142 | 135 | 139 |
| Qatar Central | 115 |  | 14 | 16 |
| South Africa North | 212 | 115 | 106 | 104 |
| South Africa West | 183 | 135 | 127 | 125 |
| South Central US | 164 | 195 | 226 | 228 |
| South India | 169 | 66 | 57 | 55 |
| Southeast Asia | 182 | 103 | 88 | 90 |
| Spain Central | 59 | 89 | 108 | 117 |
| Sweden Central | 88 | 118 | 143 | 148 |
| Switzerland North | 55 | 85 | 102 | 105 |
| Switzerland West | 58 | 81 | 106 | 110 |
| UAE Central | 124 | 15 |  | 8 |
| UAE North | 126 | 17 | 8 |  |
| UK South | 70 | 125 | 121 | 122 |
| UK West | 71 | 129 | 125 | 126 |
| West Central US | 164 | 233 | 232 | 236 |
| West Europe | 66 | 128 | 120 | 123 |
| West US | 187 | 252 | 246 | 249 |
| West US 2 | 186 | 252 | 249 | 255 |
| West US 3 | 180 | 242 | 248 | 248 |

#### [Africa](#tab/Africa/MEA)


| Source | South Africa North | South Africa West |
|---|---|---|
| Australia Central | 280 | 294 |
| Australia Central 2 | 278 | 294 |
| Australia East | 347 | 339 |
| Australia Southeast | 345 | 340 |
| Austria East | 186 | 164 |
| Belgium Central | 177 | 148 |
| Brazil South | 327 | 309 |
| Canada Central | 236 | 215 |
| Canada East | 233 | 211 |
| Central India | 134 | 154 |
| Central US | 253 | 237 |
| Denmark East | 190 | 162 |
| East Asia | 272 | 270 |
| East US | 226 | 205 |
| East US 2 | 222 | 203 |
| France Central | 165 | 147 |
| France South | 164 | 156 |
| Germany North | 185 | 160 |
| Germany West Central | 172 | 156 |
| Indonesia Central | 199 | 219 |
| Israel Central | 215 | 180 |
| Italy North | 181 | 160 |
| Japan East | 254 | 312 |
| Japan West | 302 | 271 |
| Jio India West | 152 | 172 |
| Korea Central | 250 | 270 |
| Korea South | 244 | 260 |
| Malaysia West | 191 | 210 |
| Mexico Central | 271 | 254 |
| New Zealand North | 335 | 321 |
| North Central US | 241 | 221 |
| North Europe | 178 | 161 |
| Norway East | 189 | 171 |
| Norway West | 194 | 165 |
| Poland Central | 199 | 172 |
| Qatar Central | 115 | 136 |
| South Africa North |  | 24 |
| South Africa West | 24 |  |
| South Central US | 252 | 235 |
| South India | 154 | 174 |
| Southeast Asia | 190 | 215 |
| Spain Central | 152 | 128 |
| Sweden Central | 200 | 179 |
| Switzerland North | 180 | 152 |
| Switzerland West | 174 | 152 |
| UAE Central | 107 | 128 |
| UAE North | 105 | 126 |
| UK South | 169 | 152 |
| UK West | 173 | 154 |
| West Central US | 264 | 246 |
| West Europe | 171 | 154 |
| West US | 279 | 261 |
| West US 2 | 284 | 267 |
| West US 3 | 269 | 252 |


---

Additionally, you can view all of the data in a single csv table:

```csv
Source,Australia Central,Australia Central 2,Australia East,Australia Southeast,Austria East,Belgium Central,Brazil South,Canada Central,Canada East,Central India,Central US,Denmark East,East Asia,East US,East US 2,France Central,France South,Germany North,Germany West Central,Indonesia Central,Israel Central,Italy North,Japan East,Japan West,Jio India West,Korea Central,Korea South,Malaysia West,Mexico Central,New Zealand North,North Central US,North Europe,Norway East,Norway West,Poland Central,Qatar Central,South Africa North,South Africa West,South Central US,South India,Southeast Asia,Spain Central,Sweden Central,Switzerland North,Switzerland West,UAE Central,UAE North,UK South,UK West,West Central US,West Europe,West US,West US 2,West US 3
Australia Central,,5,10,19,262,252,302,210,221,153,184,271,126,210,230,248,263,259,254,112,276,254,111,117,170,145,135,128,184,37,197,270,271,268,271,188,280,294,179,132,100,261,284,246,245,179,180,266,268,170,266,147,174,184
Australia Central 2,7,,12,16,262,253,301,210,221,155,187,267,128,220,229,248,237,260,253,111,275,253,137,116,170,141,124,106,185,41,197,267,270,268,271,188,278,294,170,132,100,251,281,247,245,179,178,258,259,183,257,148,175,183
Australia East,12,11,,16,295,285,298,207,215,151,178,288,127,206,224,280,273,293,291,110,273,286,105,113,167,137,133,125,210,31,191,272,294,280,300,186,347,339,194,132,98,265,307,286,289,178,179,277,279,163,282,141,180,176
Australia Southeast,19,14,17,,280,267,310,218,226,145,190,291,130,217,236,287,254,301,299,101,266,295,116,124,161,149,145,94,202,42,202,281,283,258,307,180,345,340,204,123,90,276,311,294,267,171,172,286,288,174,292,152,191,189
Austria East,262,259,292,278,,22,206,112,106,146,136,30,245,106,110,23,27,21,16,178,57,20,261,251,154,282,248,180,162,287,124,38,34,38,18,98,186,164,143,172,190,39,41,19,22,114,124,29,34,149,24,170,170,170
Belgium Central,253,252,284,266,23,,196,97,92,148,125,25,245,94,93,11,20,19,13,182,73,26,248,228,152,248,216,175,148,279,113,23,29,24,29,90,177,148,127,143,186,26,38,17,20,108,109,16,20,136,10,157,156,156
Brazil South,302,301,298,310,208,197,,133,134,320,155,195,315,121,121,193,193,200,201,348,228,208,265,273,320,289,283,340,159,311,142,176,200,196,211,292,327,309,142,349,337,184,209,204,202,286,293,184,187,159,191,170,179,163
Canada Central,209,208,207,217,112,96,132,,14,216,35,100,205,21,25,92,90,101,101,236,128,105,165,171,218,190,182,229,74,197,23,78,104,96,114,192,236,215,58,248,226,92,115,101,97,184,187,83,84,49,92,70,68,75
Canada East,222,221,216,227,109,93,134,16,,212,45,96,219,28,32,88,84,98,97,245,124,101,177,182,215,201,192,241,81,210,33,74,100,96,111,189,233,211,66,244,238,88,112,97,94,181,183,79,80,58,88,78,78,89
Central India,154,155,152,145,150,150,320,216,212,,245,159,95,218,220,147,134,158,151,74,158,146,129,130,41,127,122,64,267,178,234,159,170,162,169,48,134,154,249,24,59,149,179,146,143,34,35,150,154,242,153,224,218,240
Central US,185,187,178,188,133,122,154,35,48,247,,127,183,35,42,120,117,126,125,213,150,133,141,149,272,165,162,205,48,174,19,107,131,130,134,216,253,237,30,231,201,110,142,130,126,211,212,117,120,19,118,41,41,49
Denmark East,266,263,279,270,28,21,190,99,92,150,127,,217,92,96,27,33,14,18,194,78,32,253,246,154,264,231,187,147,278,112,22,15,19,23,102,190,162,130,155,186,40,25,25,27,110,120,23,24,130,16,154,153,156
East Asia,128,128,128,130,245,214,315,205,219,96,181,225,,208,209,279,224,242,244,52,214,245,53,52,112,43,38,39,197,147,192,265,257,204,247,131,272,270,177,75,41,229,265,237,235,122,120,274,275,167,279,152,146,162
East US,209,213,207,217,106,93,119,22,27,214,35,95,207,,11,90,90,97,97,240,126,105,165,173,226,191,188,233,63,198,26,74,98,96,104,191,226,205,44,244,229,83,110,104,96,184,190,80,82,54,89,74,75,70
East US 2,230,230,224,234,112,93,121,24,30,219,41,100,208,11,,89,93,103,100,243,131,107,167,174,231,192,187,235,50,205,31,79,104,102,114,195,222,203,33,251,232,79,115,103,101,194,194,87,87,49,93,71,71,60
France Central,249,246,279,285,24,10,192,91,87,147,120,29,278,90,89,,15,19,14,175,61,25,241,247,150,267,262,177,132,268,108,20,32,26,33,121,165,147,118,165,176,21,43,18,16,115,116,12,16,132,15,152,153,138
France South,263,236,273,254,29,20,194,91,84,134,117,39,225,92,93,17,,28,23,154,45,22,240,228,126,235,201,146,141,325,108,31,40,38,39,110,164,156,127,156,159,19,50,15,13,104,104,22,25,131,24,182,155,147
Germany North,261,259,293,301,23,19,200,103,98,159,128,18,243,100,103,21,28,,14,203,64,26,249,256,151,280,224,190,142,287,118,28,21,27,21,132,185,160,133,180,237,37,31,18,23,126,128,24,24,139,16,162,160,156
Germany West Central,254,252,290,299,17,12,199,100,96,150,125,20,244,97,98,14,21,12,,182,58,21,246,252,152,272,245,181,145,296,114,28,24,29,26,124,172,156,131,169,179,30,34,12,17,121,122,19,24,139,14,157,159,151
Indonesia Central,113,111,114,102,179,181,349,238,245,74,214,248,52,241,244,176,154,203,186,,194,195,87,89,95,83,76,23,232,138,228,243,204,186,215,108,199,219,223,51,19,214,226,178,174,99,100,198,202,199,182,184,177,200
Israel Central,276,274,272,267,51,65,228,126,121,157,151,72,214,126,132,62,45,65,60,195,,54,250,250,173,245,239,185,171,296,142,81,78,81,61,146,215,180,158,169,181,59,84,55,58,139,143,69,70,162,66,186,185,176
Italy North,253,252,285,292,19,23,206,106,99,144,132,37,246,107,107,26,18,23,18,194,53,,256,260,149,278,219,186,158,288,120,40,37,41,31,92,181,160,142,160,184,39,45,12,16,113,115,32,36,146,28,167,168,167
Japan East,111,136,105,115,258,244,275,165,176,129,139,248,51,165,168,245,240,251,250,86,250,256,,14,151,35,29,77,147,130,152,232,254,252,260,171,254,312,140,107,74,227,260,254,255,155,155,237,242,125,242,109,103,118
Japan West,116,115,111,122,262,228,271,172,182,129,147,251,50,171,174,247,227,255,253,88,251,261,15,,146,26,21,78,153,138,158,236,256,244,264,165,302,271,137,108,74,233,266,256,239,156,155,241,246,133,246,116,109,122
Jio India West,176,175,177,167,153,153,318,219,215,41,274,157,112,224,231,148,126,153,152,95,172,150,151,151,,146,141,87,277,201,264,171,171,159,171,79,152,172,282,49,82,149,179,138,134,53,53,158,154,260,163,246,239,262
Korea Central,136,133,132,142,286,248,296,189,200,126,163,275,41,192,192,266,234,278,271,82,246,276,36,27,146,,10,70,172,157,175,255,280,262,285,162,250,270,165,103,71,262,286,276,280,152,153,262,263,150,267,133,127,143
Korea South,131,124,132,144,250,216,283,183,192,122,160,233,36,190,187,263,201,224,245,76,240,219,30,22,136,11,,65,162,150,171,248,235,232,235,154,244,260,152,100,69,215,267,211,209,154,156,256,242,147,261,137,129,142
Malaysia West,113,105,125,94,181,173,342,230,239,65,206,202,38,234,236,179,146,184,178,23,186,187,78,80,87,71,65,,227,131,218,231,194,179,207,101,191,210,216,43,11,187,213,170,164,92,91,189,194,192,186,176,169,192
Mexico Central,184,184,184,194,153,136,158,75,84,269,48,140,195,66,60,141,144,153,151,232,182,160,147,154,277,172,161,226,,181,61,131,155,153,162,213,271,254,25,251,221,121,161,154,150,220,231,140,143,48,145,53,75,42
New Zealand North,36,40,30,42,284,282,309,192,206,180,172,286,154,200,202,272,280,283,294,138,304,290,131,138,202,157,150,130,183,,184,265,289,277,294,216,335,321,176,157,126,283,300,279,274,206,206,276,280,158,273,145,140,159
North Central US,194,194,189,199,122,110,141,22,31,232,18,116,191,24,29,109,106,118,115,226,143,121,150,158,261,174,170,216,59,184,,94,121,118,125,178,241,221,41,248,213,98,132,120,114,202,203,100,102,32,106,53,53,63
North Europe,270,267,272,281,39,24,176,80,75,160,107,26,266,76,79,22,30,29,29,251,80,42,232,238,171,255,248,236,121,271,95,,30,28,38,135,178,161,112,181,236,35,40,32,37,129,131,15,18,116,19,137,136,133
Norway East,272,270,294,284,36,28,199,105,100,170,132,18,256,100,104,32,39,22,26,255,77,39,252,256,172,280,235,208,143,290,121,30,,11,30,143,189,171,136,190,243,47,18,30,35,136,140,26,30,138,24,161,157,156
Norway West,270,268,280,258,40,24,195,98,96,158,132,24,206,96,101,28,39,27,30,186,88,42,252,244,159,262,232,179,153,278,121,27,12,,35,106,194,165,136,169,186,42,22,33,37,121,135,19,23,136,26,158,157,163
Poland Central,272,270,300,306,20,30,212,114,110,169,134,28,250,112,115,34,39,21,26,214,61,32,258,264,170,288,235,202,150,298,125,39,30,35,,142,199,172,143,195,201,50,30,30,33,135,139,34,37,152,28,168,171,164
Qatar Central,190,188,190,179,131,124,265,166,161,47,192,136,129,165,181,87,74,97,93,108,115,99,172,165,78,162,154,100,213,215,182,100,110,106,110,,115,136,196,66,99,122,121,85,84,14,16,92,95,203,94,221,224,222
South Africa North,280,278,348,340,184,174,326,235,231,134,251,190,272,225,222,165,163,186,174,208,212,179,255,257,151,255,243,190,268,340,241,178,189,192,198,115,,24,250,156,211,149,196,174,171,106,104,169,171,264,171,278,285,270
South Africa West,295,294,341,340,166,150,309,216,211,154,234,166,269,208,203,148,152,160,157,215,183,160,310,273,172,302,260,208,245,315,223,160,171,166,173,135,24,,233,175,241,129,182,153,151,127,125,152,154,246,154,262,268,252
South Central US,175,174,172,183,140,123,142,57,65,246,29,129,183,47,42,122,127,136,132,222,164,142,140,146,282,164,159,215,24,172,42,113,138,135,145,195,252,235,,242,211,108,146,136,134,226,228,120,123,29,127,44,57,32
South India,134,131,134,122,177,142,334,244,240,25,232,156,74,246,248,164,152,178,168,51,169,161,108,109,49,104,100,43,252,158,250,175,183,170,181,66,154,174,243,,39,169,194,162,158,57,55,163,167,218,169,203,196,219
Southeast Asia,101,99,98,89,187,228,337,226,237,58,201,235,40,229,232,175,157,236,179,18,182,182,74,76,76,72,68,10,220,123,214,236,243,186,202,103,190,215,203,39,,228,256,173,172,88,90,183,187,187,181,171,165,188
Spain Central,252,251,272,276,41,26,185,93,88,148,110,44,242,84,80,23,19,37,32,197,59,37,238,235,151,262,215,189,133,275,101,35,48,42,50,89,152,128,114,166,227,,57,29,27,108,117,27,29,122,30,143,144,141
Sweden Central,279,277,303,307,39,35,204,112,109,174,142,26,259,108,114,40,47,28,31,221,88,45,258,263,177,284,262,212,161,300,132,37,15,19,28,118,200,179,143,191,206,54,,34,39,143,148,34,39,149,31,168,165,172
Switzerland North,248,246,286,274,20,19,202,102,97,145,133,29,239,104,103,19,15,18,12,178,55,13,254,245,137,277,211,170,154,279,122,33,31,33,30,85,180,152,137,162,177,29,39,,10,102,105,25,30,142,20,163,162,164
Switzerland West,245,242,288,264,24,19,198,99,93,142,125,32,239,96,101,18,11,21,16,173,58,17,256,241,134,279,208,163,150,275,115,35,34,36,32,81,174,152,134,157,175,26,42,10,,106,110,21,25,139,23,158,158,160
UAE Central,181,179,181,170,126,118,285,184,177,35,208,131,122,186,193,114,102,119,120,100,124,114,156,156,53,152,164,91,222,206,203,128,127,116,129,15,107,128,227,57,86,117,145,102,106,,8,119,123,235,114,251,254,246
UAE North,182,179,182,171,127,118,288,187,183,34,212,131,119,191,194,117,104,127,122,99,126,117,155,155,53,153,161,91,231,206,204,130,140,134,138,17,105,126,229,55,87,118,149,105,110,8,,122,126,236,124,257,256,248
UK South,266,262,277,286,31,16,183,84,78,151,112,27,274,80,87,13,21,24,20,199,70,32,235,241,161,261,256,185,132,281,102,14,26,19,34,125,169,152,118,174,183,26,36,25,22,121,122,,9,124,12,144,145,138
UK West,270,261,280,288,37,20,188,86,80,154,115,29,278,83,89,17,26,24,25,202,71,37,240,246,156,264,243,191,135,296,104,18,31,23,37,129,173,154,121,175,187,30,41,30,27,125,126,10,,127,17,146,149,140
West Central US,171,175,164,174,148,135,159,49,57,242,20,134,166,55,51,132,131,140,140,198,164,147,125,133,252,150,147,192,48,161,34,116,138,134,149,233,264,246,30,218,187,122,146,142,138,232,236,124,127,,128,27,27,39
West Europe,256,255,282,291,26,10,189,93,88,153,114,20,278,91,94,15,23,17,14,182,66,29,240,246,163,267,260,186,135,275,106,20,25,25,28,128,171,154,126,174,182,29,31,21,23,120,123,13,17,131,,153,153,147
West US,148,148,142,152,170,154,171,71,78,224,42,158,151,72,71,152,163,162,158,184,187,166,110,118,240,134,136,175,54,155,55,138,161,156,167,252,279,261,38,203,172,138,169,162,157,246,249,144,146,27,151,,26,23
West US 2,173,174,179,190,169,155,179,69,77,218,41,151,144,76,71,153,154,159,160,176,186,166,102,110,233,128,128,168,74,145,54,135,156,154,167,252,284,267,58,196,165,142,165,161,156,249,255,144,148,26,147,25,,44
West US 3,172,181,169,185,160,146,166,81,90,243,52,150,160,65,60,137,146,155,150,205,180,161,121,124,256,144,141,190,43,165,59,132,160,154,166,242,269,252,25,220,187,127,166,152,147,248,248,141,138,36,145,22,42,
```

## Next steps

Learn about [Azure regions](https://azure.microsoft.com/global-infrastructure/regions/).
