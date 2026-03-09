Repository Description: 
E-commerce Price Comparison SQL Queries
This repository contains a comprehensive collection of SQL queries designed for data analysis, catalog management, and quality assurance within a price comparison engine database. The scripts primarily focus on handling complex data structures related to products, store offers, categories, and brands to ensure data integrity and optimize e-commerce operations.

Key areas covered by these queries include:

Offer Indexing & Mapping: A core part of a price comparison engine is matching store offers to the correct products. Queries such as offers indexed to the products, indexed_from_stores_by_category, and non-indexed_offers help track mapping efficiency. Additional scripts, like offers_not-indexed_but_matching_code, are designed to identify missed indexing opportunities where EAN/UPC codes match but offers remain unlinked.

Data Quality & Deduplication: Maintaining a clean product catalog is crucial. Queries like duplicates in the categories and the_same_ean_under_diff_products detect data anomalies, conflicting EAN codes, and redundant entries, allowing for quick catalog cleanup.

Brand & Category Analysis: Scripts such as brands_in_categories and codes_from_brand analyze the relationships between manufacturers, barcodes, and the overarching catalog structure.

Catalog Growth & Keyword Tracking: The repository includes queries for filtering items by specific attributes (products with specific keywords in the name, offers_by_keyword) and tracking catalog expansion over time (products_created_in_specific-year_vs_all_created, created_from_one_store).

Workflow & Productivity Monitoring: Queries like hours_by_user and products_by_user_and_auto provide insights into internal operations, comparing manual product creation by administrators against automated processes.

Overall, this collection serves as a practical toolkit for data analysts and database administrators working with e-commerce aggregators to monitor feed integrations, resolve catalog inconsistencies, and generate valuable business insights.
