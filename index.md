# **SharePoint Online - Standards, Roles and Practices**
The objective of this document is to establish the standard processes, roles and guidelines related to the use of SharePoint within the Riverside County SharePoint Online Environment.

# **Site Collection Lifecycle**

## Creating your new site
To create your new site, first visit https://www.microsoft.com. Once there, an option will appear near the top of the screen that says "Create Site"

### 1. Site Type
When you create a site, you will have the option of creating a Modern Team site or a Modern Communication site. 

### 3. Modern Communication Site Design
If you choose to create a Communication Site, then you will also be asked to choose a site design in the next screen.
Topic
Showcase
Blank

### 2. Site Name and Description
After selecting your site type (and the site design if you chose a Communication Site), you will be asked to give your site a name and provide a description for your site. In order to maintain distinction amongst the RCIT managed departments within the shared tenant, it is encouraged that your site be named in a way that distictly identifies it as belonging to your department.

### 3. Site collection administrators
As the creator of the site, you will become the first site collection administrator. It is recommended that you add at least one more Site Collection Administrator for security and maintenance purposes. Each site collection should have a minimum of two (2) and a maximum of three (3) site collection administrators. 

## Site Collection Maintenance

### Site Collection Storage
Each site collection will be provisioned with a maximum of 25GB. 

## Site & Content Deletion
Sites may be deleted by the site collection administrators and those delegated by the site collection administrators. When a site is deleted, the heirarchy of sites in the collection and all content within them are also deleted. This includes the following:

 - Documents and document libraries
 - Lists and list data
 - Site configuration settings
 - Role and security information that is related to the site or its subsites
 - Subsites of the top-level website, their contents, and user information

Once items from a site are deleted, they are moved to the site recycle bin for 93 days. If an administrator empties the site recycle bin, then the content is moved to the site collection recycle bin for the remainder of the original 93 days.

### Content Retention 
Versioning
Retention Policy - Creation based or last modified?


### Recovery of deleted sites
If a site is deleted due to inactivity or by request of a site collection admin, it may be possible to recover it if it has been less than 93 days since it was deleted. Full recovery is not guaranteed. For recovery requests, please submit a Service Now ticket to the Office 365 Services team with the following information:

1. Site Name
2. Site Owners

# **Site Design & Architecture**

## "Out of the Box" Philosophy
SharePoint is available in an "out of the box" configuration. The use of third-party tools and integrations is strongly discouraged and will not be supported by RCIT.

# **Security & Support**

## Roles and Responsibilities
|Role Name|Sharepoint Online Authority  |
|-----------------------------|---------|
|Global Administrator         |<ul><li>Has complete access to SharePoint Online, including all Site Collections</li>|
|SharePoint Administrator     |<ul><li>Has complete access to SharePoint Online, including all Site Collections</li>|
|Site Collection Administrator|<ul><li>Has administrative access to a given site collections</li>|
|Site Owner                  |<ul><li>Has administrative access to a given site or subsite within a site collection</li><li>Can add/edit/delete content, delete sites, and set up permissions for a given site</li>|
|Hub Owner     |<ul><li>Site collection administrator of a given hub site. Has the ability to associate a site collection to an existing hub.</li>|
|Internal Site User     |<ul><li>Any Riverside County employee assigned to the "Site Members" or "Site Visitors" Role. <li>Site Members are granted edit permission level, which gives them add/edit/delete permissions to content within a site. It is strongly recommended that Site Collection Administrators change this to the contributor permission level to avoid unwanted deletion of content. </li><li>Site Visitors are granted read access only to a given site</li>|
|External Site User     |<ul><li>Vendor, contractor or any other external user who is not an employee of the County of Riverside</li>         |

## Custom Permission Levels
Custom permission levels are strongly discouraged, however Site Collection Administrators may create them at their discression. Site Collection Administrators are solely responsible for resolving access issues related to custom permission levels that they create. 

# References



