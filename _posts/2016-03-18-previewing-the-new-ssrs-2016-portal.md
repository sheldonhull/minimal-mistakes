---


title:  "Previewing the new SSRS 2016 portal"
date: 2016-03-18
tags: ["sql-server","ssrs"]
---

Ran into an issue with the "Preview New Reporting Portal" link on a fresh install of 2016 giving me a not found error.

![SNAG-0031](/assets/img/SNAG-0031_kxyjti.png)

Changing the virtual directory in the Report URL tab for SSRS configuration fixed this invalid link. In my case, I changed /Report to /Reporting.
Thanks to [Adam on Stack Overflow](http://stackoverflow.com/questions/34410218/access-ssrs-2016-new-reporting-portal) for providing the solution and saving me a lot of time!
