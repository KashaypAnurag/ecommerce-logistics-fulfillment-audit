# ecommerce-logistics-fulfillment-audit

# Global E-Commerce Logistics & Order Fulfillment Audit

An institutional multi-sheet Excel analytical framework built to optimize international supply chain operations, isolate processing delays, and track regional revenue performance. This project monitors 100 global transactional order paths, linking relational lookups, dynamic delivery metrics, and automated pivot tables into a clean business intelligence dashboard.

---

## 1. Core Analytics Objective & Financial Summary

The objective of this framework is to audit shipping latency variations across distribution networks, spot delivery speed bottlenecks, and track gross revenue performance across our core product lines:

*   **Total Accumulated Gross Revenue:** \$35,258.00 total sales captured across all active global regions.
*   **Total Logistical Footprint:** 100 enterprise transactional order profiles tracked down to different delivery status.
*   **Primary Revenue Driver:** The **Smartphone** category, leading the portfolio with **\$9,644.00** in total gross sales.

---

## 2. Workbook Architecture & 8-Sheet Structural Ledger

To demonstrate advanced spreadsheet structure and data modeling standards, the workbook is organized into 8 individual specialized tabs:

1.  **Fulfillment Dashboard:** A clean, executive visual control panel displaying regional cancellation rates, delivery status distributions, and gross monthly sales trends.
2.  **Order Transaction Ledger:** The master database containing order logs, price metrics, quantities, and transaction types.
3.  **Customer Registry Matrix:** A relational lookup database mapping Customer IDs to individual client types (Business, Prime, Individual) and geographic cities.
4.  **Product Catalog Directory:** A structured asset database tracking cost prices, retail values, and product names across 5 core categories.
5.  **Region Performance Lookups:** Connects regional coordinates directly to predefined regional sales target benchmarks.
6.  **XLOOKUP Integration Hub:** Houses the core formulas that connect our tables together, mapping cities, states, and product categories into a single row snapshot.
7.  **Fulfillment Metrics Compiler:** Automatically calculates delivery latencies and maps delivery performance speeds (FAST, SLOW, or CANCELLED).
8.  **Pivot Analysis Sheets:** Dedicated pivot tables that break down total sales by region, average delivery days by shipping partner, and regional cancellation rates.

---

## 3. Core Insights & Logistical Recommendations

### Simplified Multi-Sheet Relational Mapping
By utilizing advanced **XLOOKUP** string arrays, the data pipeline consolidates information across sheets without bloating file memory. This allows business analysts to generate clean pivot reports without manually jumping between individual tabs.

### Regional Performance and Bottlenecks
*   **The Discovery:** The **North Region** is our highest revenue driver (**\$10,491.00**), but it also tracks the highest order cancellation rate. 
*   **The Logistics Fix:** Partner with local delivery service operators in New York, Seattle, and Phoenix to address the high average delivery times in those hubs.

### Delivery Partner Optimization
*   **The Discovery:** **FedEx and USPS** suffer from higher average delivery windows despite handling a lower overall volume of orders. Conversely, **DHL** maintains a fast average delivery timeline while processing a much larger share of shipments.
*   **The Logistics Fix:** Shift our electronics items (which face the longest average shipping delays) over to DHL’s distribution network to optimize our delivery speeds.

---

## 4. Operational Workbook Visual Ledger

### Executive Fulfillment Control Dashboard
Below is the live operational dashboard panel used by logistics teams to monitor gross revenue trends, regional performance metrics, and order status tracking columns in real time:

<div align="center">
  <img src="https://private-user-images.githubusercontent.com/50950725/659130136-02e84f19-8f9c-4118-81dc-95ccc0f752cd.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAzNjAxMjIsIm5iZiI6MTc5MDM1OTgyMiwicGF0aCI6Ii81MDk1MDcyNS82NTkxMzAxMzYtMDJlODRmMTktOGY5Yy00MTE4LTgxZGMtOTVjY2MwZjc1MmNkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA5MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwOTI1VDE4MTAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJmNDBmZTMxMTE3N2M1NjY0MDg1M2Q2MjIzYzE3ZGVjODE5OWQ3NjcwOTNlNmM5ZDRkODEzNGE3NjI1NDM1YmImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.AeT-r8OlttS5kIVBSLk_0z6_huhZ9FoAZjG_lqewXXA" width="100%" alt="Fulfillment Control Dashboard View" style="margin-bottom: 15px;" />
</div>

### Relational Lookups & Automated Formula Engines
Below are the backend data matrices showcasing our clean multi-sheet data connections, relational lookup formula networks, and automated error-handling validation parameters:

<div align="center">
  <img src="https://private-user-images.githubusercontent.com/50950725/659130128-9a45e31c-db36-4eac-9588-fc7bed72bac2.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAzNjAxMjIsIm5iZiI6MTc5MDM1OTgyMiwicGF0aCI6Ii81MDk1MDcyNS82NTkxMzAxMjgtOWE0NWUzMWMtZGIzNi00ZWFjLTk1ODgtZmM3YmVkNzJiYWMyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA5MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwOTI1VDE4MTAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTNmYjM0Y2MwYmYzMjZhY2NmYTQ2OTg1OWU2ZGQ4NGVjYzg2YTc4ZGFjMjMzOWE2NTdiZGU2NzI3MTAxNmM4NGQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.itHrLnnOxqgUocwC1VPGNUgFUYn05eXtnvvmA4iqvf0" width="100%" alt="Relational XLOOKUP Category Matching Ingestion" style="margin-bottom: 15px;" />
  <br>
  <img src="https://private-user-images.githubusercontent.com/50950725/659130124-08033d68-723b-4b42-9af1-ab855b0e5797.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAzNjAxMjIsIm5iZiI6MTc5MDM1OTgyMiwicGF0aCI6Ii81MDk1MDcyNS82NTkxMzAxMjQtMDgwMzNkNjgtNzIzYi00YjQyLTlhZjEtYWI4NTViMGU1Nzk3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA5MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwOTI1VDE4MTAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTRkYTRhYjZlYzBmZmQ0ZWY3ZGFjMTgyNGQzNjViN2RlNzRjNjhhZTU2NzAyNWYzMjIyNzYwNDQxOWM0YTc5NzMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.hRQroTszUveWRYInFRsjf_EiAcjABLnqVAodRDi90dU" width="49%" alt="Conditional Customer Data Relational Lookup" style="margin: 5px;" />
  <img src="https://private-user-images.githubusercontent.com/50950725/659130125-a18423d5-3e8a-4566-b234-a3f17ff01eed.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAzNjAxMjIsIm5iZiI6MTc5MDM1OTgyMiwicGF0aCI6Ii81MDk1MDcyNS82NTkxMzAxMjUtYTE4NDIzZDUtM2U4YS00NTY2LWIyMzQtYTNmMTdmZjAxZWVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA5MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwOTI1VDE4MTAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTlhY2RhNzA3ZGQ2MmJhYTNmZjE1NGJhOGZkOTUwNmEzNzI5YTIwMTEwMWM0ODlmNDg3ZTM2MmYwZjQ3MzI2ZjkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.JwT02xHAb9d5mvxJa3pxzRUG4Pai1sNP9g2pjQJgy-8" width="49%" alt="Automated Latency Exception Handling Engine" style="margin: 5px;" />
</div>

### Multi-Dimensional Pivot Analysis Sheet
Below is our dedicated calculation matrix workspace, aggregating gross transaction volumes, multi-layered slicer dimensions, and regional latency summaries across active billing footprints:

<div align="center">
  <img src="https://private-user-images.githubusercontent.com/50950725/659130137-719f8b88-dba0-4890-801b-6da435763437.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAzNjAxMjIsIm5iZiI6MTc5MDM1OTgyMiwicGF0aCI6Ii81MDk1MDcyNS82NTkxMzAxMzctNzE5ZjhiODgtZGJhMC00ODkwLTgwMWItNmRhNDM1NzYzNDM3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA5MjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwOTI1VDE4MTAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWIzZjE3MzhkMTQ5ZDFkMTYzNmY0OGU1MDUxMWY0Zjc0ZWRhMzIwYWM2Zjk0NzcyZjU4MDliYjRmODVhMzA4YWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.AZ1-KJhN1vAvdFH7EMbFoCJM_Xoh8wR9wKp9l-ny690" width="100%" alt="Multi-Dimensional Pivot Analysis Grid" style="margin-top: 15px;" />
</div>
