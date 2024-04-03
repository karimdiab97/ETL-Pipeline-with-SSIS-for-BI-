# ETL-Pipeline-with-SSIS-for-BI-


Summary:

I am excited to share the ETL portion of my latest BI project with you. Here's an overview of the steps I typically follow in my ETL processes:
- Thoroughly understanding the source and destination systems, including data profiling.
- Creating a mapping sheet to visualize source columns, destinations, and lookups.
- Establishing a meta control table in the destination to track last load date or ID for incremental loading.
- Collaborating with teammates to define unique system codes for different sources and adding a derived column to all dimensions and fact tables.
- Performing data transformations as needed.
- Implementing slowly changing dimensions for future changes.
- Loading dimension tables first, followed by fact tables.
- Conducting rigorous testing of the ETL process.

Tools Used:
- Microsoft SQL Server Integration Services (SSIS)

SSIS proved to be an ideal choice for this project due to its compatibility with MS SQL Server, which houses both the source and destination systems.
