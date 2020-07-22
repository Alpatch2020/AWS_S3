**Storing a Static Website on Amazon Web Services Simple Storage
Service**

This is a paid cloud public cloud storage service offered by AWS for the
storage of objects which consists of data and metadata. We can think of
AWS S3 buckets as file folders in the cloud.

**Creating an AWS S3 bucket.**

From your AWS account, select **AWS management console**, thereafter,
type **S3** in the search bar underneath **Find Services.** Select
**S3.** On the next page click create bucket and fill in the name of
your bucket(this name is globally unique, hence, you can't use a name
already used by another AWS user).

![A screenshot of a cell phone Description automatically
generated](.//media_files/image1.PNG)

In this demo, the region was chosen as US East-1. Click next, and in
configure options pane, leave everything as is and click next. You will
be taken to the **Set Permissions** pane. Here, uncheck Block all public
access and check the acknowledgment that comes with the warning message
pop up.

![A screenshot of a cell phone Description automatically
generated](.//media_files/image2.png)

Then you review and click create bucket and there you have your new
bucket.

![A screenshot of a cell phone screen with text Description
automatically generated](.//media_files/image3.PNG)

Your result should look like the one below:

![A screenshot of a cell phone Description automatically
generated](.//media_files/image4.PNG)

**Uploading the static webpage**

Double click on your bucket's name, under the **Overview** tab, click
**Upload**

![A screenshot of a cell phone Description automatically
generated](.//media_files/image5.png)

Then click add file and select the file from where it is located:

![A screenshot of a cell phone Description automatically
generated](.//media_files/image6.PNG)

After uploading you have something similar to this.

![A screenshot of a cell phone Description automatically
generated](.//media_files/image7.png)

Click **Next**, this under **Set Permissions** select **Grant public
access to this object(s)** from the **Manage public permissions** drop
down menu.

![A screenshot of a cell phone Description automatically
generated](.//media_files/image8.PNG)

Leave **Set Properties** unchanged, go to **Review** and upload. By
clicking on the new object a menu similar to the one below will appear.
You can copy the **OBJECT URL** from there and paste in a browser.

![A screenshot of a cell phone Description automatically
generated](.//media_files/image9.PNG)

After which you obtain the following

![A screenshot of a social media post Description automatically
generated](.//media_files/image10.png)

Since, S3 is a paid service you might consider **deleting** your bucket
after this to avoid losing money unnecessarily, unless you really need it.
