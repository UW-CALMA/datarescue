# 🕵️ Track 3 (Technical)

This track focuses on the actual capture of at-risk data in a variety of formats. As these tasks require the most technical knowledge, skills, and equipment, volunteers are encouraged to take this track when they are able to dedicate more time.

**Tech Skill Level:** Advanced

**Time Commitment:** \~2-3 hours

**Tools Required (vary across tasks):**

* Web capture tools ([Conifer](https://guide.conifer.rhizome.org/), [Archive-It](https://archive-it.org/), [Webrecorder](https://webrecorder.io/), [wget](https://www.gnu.org/software/wget/). [More information on web archiving](https://bits.ashleyblewer.com/blog/2017/09/20/how-do-web-archiving-frameworks-work/))
* Data quality check system
* Spreadsheet editor (excel, google sheets)
* Web monitoring tool
* Storage (available internal memory, external hard drive)

**Tasks Include:**

1. Setup website monitoring systems
2. Capture website content
3. Harvesting public datasets
4. Review data authenticity and quality
5. Program or conduct comprehensive data/website crawl&#x20;

### TASKS BREAKDOWN

#### 1. Set up monitoring API tracker to document changes to government websites

**Summary:** Given the previous removal of content and subtle revision to federal government environmental websites, many&#x20;

**Workflow**

1. Read or skim the following report of website monitoring by EDGI
   1. Report Link: [https://envirodatagov.org/publication/changing-digital-climate/](https://envirodatagov.org/publication/changing-digital-climate/)&#x20;
2. Download the a monitoring tool like:
   1. HTTP API tracker [https://github.com/edgi-govdata-archiving/web-monitoring-db](https://github.com/edgi-govdata-archiving/web-monitoring-db)&#x20;
   2. Comprehensive list of other tools here: [https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)&#x20;
3. Identify website to track using [this Data Tracking List](https://docs.google.com/spreadsheets/d/1tOS7B3lgK-8wdgyhY81ntfICMIkGwAiHfeV63hi3UzU/edit?usp=drive_link)&#x20;
4. Deploy tracker for selected website&#x20;
5. Submit information about tracked website to [the Data Tracking form](https://docs.google.com/forms/d/e/1FAIpQLSfII-rl4yUcGPJlPWk9knWMhC_qBueJLEPcC7vphPeVisLhHA/viewform?usp=sf_link)

**Skills Needed:** Advanced understanding of software deployment, APIs, and technical git repositories.&#x20;

#### 2. Capture web files/data

**Summary:** The collecting of web archives (meaning webpages and the content with them) can be complex, but necessary. Using more user friendly software, non-digital preservationist can help capture select content of websites without worrying about collecting the entire structure of a website.

**Workflow**

1. Identify a web file ready to[ ready to be archived](https://docs.google.com/spreadsheets/d/1tOS7B3lgK-8wdgyhY81ntfICMIkGwAiHfeV63hi3UzU/edit?usp=drive_link)&#x20;
2. Comment on the Status cell that you are working on that row
3. Using web capture software (like [Conifer](https://guide.conifer.rhizome.org/)) pick an at-risk website that includes at-risk data
4. Comment on the same Status cell that the web file/data has been archived

**Skills Needed:** Intermediate understanding of software deployment and website navigation.&#x20;

#### 3. Harvest public datasets available online

**Summary:**&#x20;

**Workflow**

1. Search for public funding project repositories (NIH [RePORTER](https://reporter.nih.gov/), US Government Awards [USASpending](https://www.usaspending.gov/search), Federal Audit Clearinghouse [FAC](https://app.fac.gov/dissemination/search/))
2. Verify that downloadable datasets contain enough descriptive information (data files, interactive maps, etc.)&#x20;
3. Capture dataset(s) to internal storage (temporary place)
4. Submit and upload the dataset(s) to [this Data Tracking Form](https://docs.google.com/forms/d/e/1FAIpQLSfII-rl4yUcGPJlPWk9knWMhC_qBueJLEPcC7vphPeVisLhHA/viewform?usp=sf_link)&#x20;
5. You can delete dataset after successful submission via form

**Skills Needed:** Intermediate understanding of different dataset types and file formats. Comfort with downloading and saving larger files.

#### 4. Create Bag/Create checksum (save for Data Rescue Day 2 - Jan 22)

**Summary:** This helps short and long term preservation effort to verify the integrity (fixity) of stored files nd datasets. Creating checksums or reviewing them helps detect errors or signs of tampering.

**Workflow**

* Read through the [digital preservation manual chapter on fixity and checksums by the Digital Preservation Coalition](https://www.dpconline.org/handbook/technical-solutions-and-tools/fixity-and-checksums)&#x20;
* Download a fixity or checksum verification tool like
  * [Md5summer](https://md5summer.org/): An application for Windows machines that will generate and verify md5 checksums.
* Identify dataset to create checksum using this [Data Tracking List - Data Rescue 2025 (Responses)](https://docs.google.com/spreadsheets/d/1tOS7B3lgK-8wdgyhY81ntfICMIkGwAiHfeV63hi3UzU/edit?usp=drive_link)
* Run a check on the selected data to create the supplemental checksum value

**Skills Needed:** Best for those with basic data or web archiving experience, or have both strong tech skills and attention to detail.
