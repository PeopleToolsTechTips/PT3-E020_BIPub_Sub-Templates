# PT3-E020_BIPub_Sub-Templates
BI Publisher Sub-Templates

PeopleTools Tech Tips    
Randy Groncki

2022-01-27

BI Publisher Sub-Templates are reusable code blocks for RTF templates.  

Sub-Templates allow us to create a commonly used code block such as headers with logos and other information instead of recreating that header on every report.   When an item in that header changes, we only need to change the header sub-template instead of every report that uses that common header.

Additionally, we can conditionally call sub-templates as different headers for a common document to apply appropriate branding.   Think of a State University system with eighteen schools on a common PeopleSoft HCM instance.   Instead of 18 versions of a common letter, we can have one letter using the appropriate branding as per the school.   If the letter changes, one template needs updated and tested, not eighteen.

We can also use sub-templates as conditional, reusable blocks in our reports.   Think of an address block or a benefits block.  That block can be used every time or conditionally included on each individual report depending on the data in that report.

### Web Posting: https://peopletoolstechtips.com/tbd

### YouTube demo: TBD

### Contact:  
* randy@peopletoolstechtips.com  
* PeopleToolsTechTips@Gmail.com

This file contains all the objects referenced in the video and document.

## PeopleTools Project is using PeopleTools 8.59.04
  * This contains all the components, pages, records and PeopleCode used in the demonstration.
  * The target database must be minimal 8.58 PeopleTools

* X_PT3_020_BIPUB_SUB_TEMPLATS (folder)  
* X_PT3_020_BIPUB_SUB_TEMPLATES.zip  
