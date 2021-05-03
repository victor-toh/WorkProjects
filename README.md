# WorkProjects

1) Batch Job Excel to SQL Server

This is a Batch Job code that essentially takes data from a flat file source (in this case, Excel workbook), read the contents according to the headers, and then populate the contents into a Microsoft SQL Server (RDBMS). There are validations present in the code, for instance checking of presence of Excel file, and also ensuring no duplicates of primary IDs, etc. In addition, there are some more specific requirements, such as finding relevant document attachments related to the Excel data ID, and moving the excel file to an archive folder after the Batch Job successfully executes.
