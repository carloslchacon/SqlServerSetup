# SqlServerSetup
Based the inquiry of a listener to the SQL Data Partners Podcast, Steve Stedman and Carlos Chacon put together a SQL Server checklist and shared it on our podcast http://sqldatapartners.com/2016/11/09/sql-server-install-checklist/

Due to the response we got from the list, we decided to make this a community option and put the check list into a source control repository.  To help keep things simple we have broken up the checklist into four main categories:
 - Preparation
      This can be anything associated with requesting the server or  making sure you have the right Windows settings.  
 - Installation
      The settings needed for SQL Server to be installed.  
 - Configuration
      This section includes SQL Server settings.  Trace Flags and other parameters are set in this section.
 - Post Install
      This section includes options outside of SQL Server.  Response processes or 3rd party tools are listed here.  We may be splitting hairs here, but this section also includes SQL Server Agent settings.
      
The files are currently in text format for easier merging options; however, this does present some challenges for formatting.  The files follow this basic pattern

/****
*Notes Section
*****/
- top level point
 o subpoint  (yes, that is a tab)

We will merge contributions from time to time and make the 'updated' checklist available on the website.      
