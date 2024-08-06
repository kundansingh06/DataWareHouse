# Introduction: Data Warehousing

# What is a Data Warehouse?
A data warehouse is a large, centralized repository of data that is used to support data-driven decision-making and business
intelligence (BI) activities. It is designed to provide a single, comprehensive view of all the data in an organization, and to
allow users to easily analyze and report on that data.
Data warehouses are typically used to store historical data and are optimized for fast query and analysis performance. They
often contain data from multiple sources and may include both structured and unstructured data. Data in a data warehouse is
imported from operational systems and external sources, rather than being created within the warehouse itself. Importantly,
data is copied into the warehouse, not moved, so it remains in the source systems as well.
Data warehouses follow a set of rules proposed by Bill Inmon in 1990. These rules are:
1. Integrated: They combine data from different source systems into a unified environment.
2. Subject-oriented: Data is reorganized by subjects, making it easier to analyze specific topics or areas of interest.
3. Time-variant: They store historical data, not just current data, allowing for trend analysis and tracking changes over time.
4. Non-volatile: Data warehouses remain stable between refreshes, with new and updated data loaded periodically in
   batches. This ensures that the data does not change during analysis, allowing for consistent strategic planning and
   decision-making.
   As data is imported into the data warehouse, it is often restructured and reorganized to make it more useful for analysis. This
   process helps to optimize the data for querying and reporting, making it easier for users to extract valuable insights from the
   data.

# Why do we need a Data Warehouse?
Primary reasons for investing time, resources, and money into building a data warehouse:
1. Data-driven decision-making: Data warehouses enable organizations to make decisions based on data, rather than solely
   relying on experience, intuition, or hunches.
2. One-stop shopping: A data warehouse consolidates data from various transactional and operational applications into a
   single location, making it easier to access and analyze the data.
   Data warehouses provide a comprehensive view of an organization's past, present, and potential future/forecast data. They
   also offer insights into unknown patterns or trends through advanced analytics and Business Intelligence (BI). In conclusion,
   Business Intelligence and data warehousing are closely related disciplines that provide immense value to organizations by
   facilitating data-driven decision-making and offering a centralized data repository for analysis.