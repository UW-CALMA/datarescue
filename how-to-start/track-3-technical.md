# 🕵️ Track 3 (Technical)


This track focuses on the actual capture of at-risk data in a variety of formats. As these tasks require the most technical knowledge, skills, and equipment, volunteers are encouraged to take this track when they are able to dedicate more time.

**Tech Skill Level:** Advanced

**Time Commitment:** \~2-3 hours

**Tools Required (vary across tasks):**

* Web capture tools ([Conifer](https://guide.conifer.rhizome.org/), [Archive-It](https://archive-it.org/), [Webrecorder](https://webrecorder.io/), [wget](https://www.gnu.org/software/wget/). [More information on web archiving](https://bits.ashleyblewer.com/blog/2017/09/20/how-do-web-archiving-frameworks-work/))
* Data quality check system (i.e. checksum)
* Spreadsheet editor (i.e., excel, google sheets)
* Web monitoring tool
* Storage (available internal memory, external hard drive)

**Tasks Include:**

1. Setup website monitoring systems
2. Capture website content
3. Harvesting public datasets
4. Review data authenticity and quality
5. Program or conduct comprehensive data/website crawl&#x20;

**Breakdown of Task Sections**\
🚁 _(helicopter emoji)_ gives summary of task\
🗂️ _(index dividers)_ outlines specific steps needed to complete task\
🛠️ _(hammer & wrench emoji)_ details skills & tools needed for task

### TASKS BREAKDOWN

#### <mark style="background-color:purple;">1. Set up monitoring API tracker to document changes to government websites</mark>

🚁**Summary:** Given the previous removal of content and subtle revision to federal government environmental websites, many websites need to continually crawled to document track changes.

🗂️**Workflow**

1. Read or skim the following report of website monitoring by EDGI
   1. Report Link: [https://envirodatagov.org/publication/changing-digital-climate/](https://envirodatagov.org/publication/changing-digital-climate/)&#x20;
2. Download the a monitoring tool like:
   1. HTTP API tracker [https://github.com/edgi-govdata-archiving/web-monitoring-db](https://github.com/edgi-govdata-archiving/web-monitoring-db)&#x20;
   2. Comprehensive list of other tools here: [https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)&#x20;
3. Identify website to track using [**link to Data Tracking List**])&#x20;
4. Deploy tracker for selected website&#x20;
5. Submit information about tracked website to [**link to the Data Tracking form**]

**Skills Needed:** Advanced understanding of software deployment, APIs, and technical git repositories.&#x20;

#### <mark style="background-color:purple;">2. Capture web files/data</mark>

🚁**Summary:** The collecting of web archives (meaning webpages and the content with them) can be complex, but necessary. Using more user friendly software, non-digital preservationist can help capture select content of websites without worrying about collecting the entire structure of a website.

🗂️**Workflow**

1. Identify a web file ready to   ready to be captured [**link to Data Tracking List**]
2. Update the "Status" cell that you are working on that row so that others will know that you are working on that web file
3. Using web capture software (like [Conifer](https://guide.conifer.rhizome.org/)) pick an at-risk website that includes at-risk data
4. Change the status on the same "Status" cell to notify that the web file/data has been archived and to avoid others from doing redundant work

🛠️**Skills Needed:** Intermediate understanding of software deployment and website navigation.&#x20;

#### <mark style="background-color:purple;">3. Harvest public datasets available online</mark>

🚁**Summary:** Some state and federal agencies are required by law to publish data, publications, and basic information about publicly funded projects (think grants and contracts) Given changes in agency personnel, system updates, as well as financial support to pay for database services and storage, the data stored in these repositories may not always be available for the public. Saving copies can help ensure future access as well as information on past government activities and areas of interests.

🗂️**Workflow**

1. Search for publicly funded project repositories (examples include: NIH [RePORTER](https://reporter.nih.gov/), US Government Awards [USASpending](https://www.usaspending.gov/search), Federal Audit Clearinghouse [FAC](https://app.fac.gov/dissemination/search/), [NWIS - National Water Information System](https://waterdata.usgs.gov/nwis?) and many others)
2. Verify that downloadable datasets contain enough descriptive information (data files, interactive maps, etc.)&#x20;
3. Capture dataset(s) to internal storage (temporary place)
4. Submit and upload the dataset(s) via 1 of these options
   * Files up to 2 GB [https://wetransfer.com/](https://wetransfer.com/)&#x20;
   * OR submit the URL of a downloadable folder via the exit tix [**link to Work Completion Form**]&#x20;
5. You can delete dataset after successful transfer to Data Rescue coordinators

🛠️**Skills Needed:** Intermediate understanding of different dataset types and file formats. Comfort with downloading and saving larger files.

#### <mark style="background-color:purple;">4. Create checksum for captured files</mark>

🚁**Summary:** This helps short and long term preservation effort to verify the integrity (fixity) of stored files and datasets. Creating checksums or reviewing them helps detect transfer or creation errors or signs of tampering by external forces.

🗂️**Workflow**

* Read through the [digital preservation manual chapter on fixity and checksums by the Digital Preservation Coalition](https://www.dpconline.org/handbook/technical-solutions-and-tools/fixity-and-checksums)&#x20;
* Download a fixity or checksum verification tool like
  * [Md5summer](https://md5summer.org/): An application for Windows machines that will generate and verify md5 checksums.
  * [checksum](https://corz.org/windows/software/checksum/): A file hashing application for Windows, a program that generates and verifies BLAKE2, SHA1 and MD5 hashes (aka. "MD5 Sums", or "digital fingerprints") of a file, a folder, or recursively.
  * There are a number of other tools, the above mentioned are examples (see Digital Preservation Coalition Digital Preservation Handbook above).
* Ask the "data titan" coordinator to gain access to captured files
* Use the [**link to Data Tracking List**] to check details to create checksum&#x20;
* Run a check on the selected data to create the supplemental checksum value
* Upload checksum file using (1 )of the following options
    * Submit and upload the dataset(s) via 1 of these options
      * Files up to 2 GB [https://wetransfer.com/](https://wetransfer.com/)&#x20;
      * OR submit the URL of a downloadable folder via the exit tix [**link to Work Completion Form**]&#x20;

🛠️**Skills Needed:** Best for those who have strong tech skills, attention to detail, and willingness to read the docs.
