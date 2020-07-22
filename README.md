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
generated](media/image1.PNG){width="6.5in"
height="3.2402777777777776in"}

In this demo, the region was chosen as US East-1. Click next, and in
configure options pane, leave everything as is and click next. You will
be taken to the **Set Permissions** pane. Here, uncheck Block all public
access and check the acknowledgment that comes with the warning message
pop up.

![A screenshot of a cell phone Description automatically
generated](media/image2.png){width="6.5in" height="3.247916666666667in"}

Then you review and click create bucket and there you have your new
bucket.

![A screenshot of a cell phone screen with text Description
automatically generated](media/image3.PNG){width="6.5in"
height="3.252083333333333in"}

Your result should look like the one below:

![A screenshot of a cell phone Description automatically
generated](media/image4.PNG){width="6.5in"
height="1.4319444444444445in"}

**Uploading the static webpage**

Double click on your bucket's name, under the **Overview** tab, click
**Upload**

![A screenshot of a cell phone Description automatically
generated](media/image5.png){width="6.5in"
height="1.9791666666666667in"}

Then click add file and select the file from where it is located:

![A screenshot of a cell phone Description automatically
generated](media/image6.PNG){width="6.5in" height="3.076388888888889in"}

After uploading you have something similar to this.

![A screenshot of a cell phone Description automatically
generated](media/image7.png){width="6.225in"
height="1.9236111111111112in"}

Click **Next**, this under **Set Permissions** select **Grant public
access to this object(s)** from the **Manage public permissions** drop
down menu.

![A screenshot of a cell phone Description automatically
generated](media/image8.PNG){width="6.5in" height="3.136111111111111in"}

Leave **Set Properties** unchanged, go to **Review** and upload. By
clicking on the new object a menu similar to the one below will appear.
You can copy the **OBJECT URL** from there and paste in a browser.

![A screenshot of a cell phone Description automatically
generated](media/image9.PNG){width="5.229166666666667in"
height="4.027777777777778in"}

After which you obtain the following

![A screenshot of a social media post Description automatically
generated](media/image10.png){width="6.5in"
height="1.2638888888888888in"}

Since, S3 is a paid service you might consider deleting your bucket
after this to avoid losing credits unnecessarily.
