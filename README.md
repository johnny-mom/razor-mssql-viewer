# razor-mssql-viewer
a simple asp.net razor app I created to query and view a database table. It was initially created using Microsoft's WebMatrix but I've ported it over to a proper asp.net razor project.

##Use Case
I created this app while working at Batesville to run a quick select statement on our client database (running on mssql) so our dev/qa/support team could easily find the related info on our customers such as customer name and app URL.

## NUGET Packages used:
Microsoft.AspNet.Razor
Microsoft.AspNet.WebHelpers
Microsoft.AspNet.WebPages
Microsoft.AspNet.WebPages.WebData

### What's broken:
* showModalDialog javascript call for the comments is not working anymore since Chrome 37 update but still works in IE and Firefox. I'm sure there's a better way to write this without having to use this method.
