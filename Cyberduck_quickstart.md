<!---

Images can be added in-line as a reStructured text substitution, but will not render in markdown. See reStructured text example. http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#substitution-definitions

|CyVerse logo|

--->

#Uploading/Downloading Data with Cyberduck
<!---
Use short, imperative titles e.g. Upload and share data, uploading and sharing data
--->

## Goal

<!---
Avoid covering upstream and downstream steps that are not explicitly and necessarily part of the tutorial - write or link to separate quick starts/tutorials for those parts
--->

<!---
A few sentences (50 words or less) describing the ultimate goal of the steps in this tutorial
--->
Cyberduck is a free cross-platform, high-throughput and parallel data transfer open source file transfer program which is used to download/upload files and directories from/to the CyVerse Data Store. 
## Prerequisites 


### Downloads, access, and services

*In order to complete this tutorial you will need access to the following services/software*

|Prerequisite|Preparation/Notes|Link/Download|
|------------|-----------------|-------------|
|CyVerse account|You will need a CyVerse account to complete this exercise|[Register](https://user.cyverse.org/)|
|Cyberduck|Stand alone software for upload/download to Data Store|[Download](https://cyberduck.io/)|

## Get Started

### Step 1. Configure Cyberduck for use with the Data Store (one-time only)
- Click to to download the [Connection Profile](./misc/iPlant_Data_Store.cyberduckprofile), which contains preconfigured settings for using Cyberduck with the CyVerse Data Store.
- Click to open the downloaded **iPlant Data Store.cyberduckprofile** file
- Verify iPlant Data Store is displayed in the first field
- In the Nickname field, enter **data.iplantcollaborative.org – iRODS**

### Step 2. Logging in user CyVerse credentials
- Open Cyberduck.
- Click **Open Connection** and in the drop-down list, click the **iPlant Data Store** 
- Log in to Cyberduck and enter your CyVerse **user name** and **password** and click Login.

### Step 3. Downloading a file or folder from the Data Store 
- Double click the file or folder to download.The file is downloaded to your default download folder.

### Step 4. Uploading a file or folder to the Data Store
- Click the Cyberduck File menu and then click Upload. 
- Click the file or folder to upload and then click Upload.
The item is uploaded to your Home folder.


## More help and additional information

<!---
Short description and links to any reading materials
--->

More information about uploading and downloading files and folders usign Cyberduck can be found [here](https://wiki.cyverse.org/wiki/display/DS/Using+Cyberduck+for+Uploading+and+Downloading+to+the+Data+Store)

**Search for an answer:** [CyVerse Learning Center](http://www.cyverse.org/learning-center) or [Wiki](https://wiki.cyverse.org/wiki/dashboard.action)
**Post your question to the user forum:** [Ask CyVerse](http://ask.iplantcollaborative.org/questions/)

For questions on using **Cyberduck**, please see the [Cyberduck Help manual](https://trac.cyberduck.io/wiki/help/en), the [Cyberduck FAQs](https://trac.cyberduck.io/wiki/help/en/faq), or contact [Cyberduck Support](https://trac.cyberduck.io/newticket).


<!---

SAMPLE DIRECTIVES (DELETE UNUSED ONES)
--------------------------------------

See: http://docutils.sourceforge.net/docs/ref/rst/directives.html#admonitions

.. Danger::
	This step is dangerous

.. Important::
	This step is important
	
.. Caution::
	Exercise caution
	
.. Hint::
	This is a hint

.. Important::
	This is very important

.. note:: This is a note admonition.
   This is the second line of the first paragraph.

   - The note contains all indented body elements
     following.
   - It includes this bullet list.



.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
--->
