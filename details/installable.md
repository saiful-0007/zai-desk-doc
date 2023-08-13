## Social Login(Google)

Google Credentials:

For social login features (Google), you have to add some credentials to the admin settings. Firstly, go to the social
login settings in the global settings subcategory of Application settings.

![Image](/images/Admin/socal.jpg)

Now create Google credentials. For that, you need to sign in to your Google account. After that, you have to go to the
URL (console.cloude.google.com)
Click on the console.

![Image](/images/installable/google-credentials.png)

Then click the menu bar and go to APIs and Services, and you have to go to the Library section.

![Image](/images/installable/api-1.png)

In the library, when you reach it, you have to go to the Google+ API.

![Image](/images/installable/api-2.png)

After that, you can see the Google+ API section below.

![Image](/images/installable/api-3.png)

After that, click the enable button to enable this API. Now click my project button.

![Image](/images/installable/api-4.png)

Now create a new project, or you can choose an existing one.

![Image](/images/installable/new-project.png)

Give the project a name.

![Image](/images/installable/new-project-2.png)

So, your project will be created here. Now go to the credential section to create credentials for your project. Click
the create credential button.

![Image](/images/installable/project-3.png)

Click the OAuth client ID.

![Image](/images/installable/project-4.png)

To create an OAuth client ID, you must first configure your consent screen. Click here.

![Image](/images/installable/project-5.png)

Now you have to choose the user type external and create.

![Image](/images/installable/project-6.png)

Give the app information

![Image](/images/installable/project-9.png)

![Image](/images/installable/project-7.png)

In the second step, there is no need to enter any information. Just go tSaveve and continue.

![Image](/images/installable/project-8.png)

When you reach your test user, you can add the user to your particular app. Then go to Save and Continue.

![Image](/images/installable/project-10.png)

Now you are configured. And you have to go to the credentials again.

![Image](/images/installable/project-11.png)

Go to the create credential page again.

![Image](/images/installable/project-4.png)

Here, you have to select the application types. You also have to edit your new web name and give the URI. You have to
follow the format for writing URLs.

{website URL}/auth/google/callback

For example

https://lmszai.zainikthemes.com/auth/google/callback

![Image](/images/installable/project-13.png)

Go to the credential. Click the edit button

![Image](/images/installable/project-14.png)

And here is your client id, client secret and URI.

![Image](/images/installable/image22.png)

Put this information in the admin application settings and click the update button.

![Image](/images/installable/Social-Login-Setting.png)

## Social Login(Facebook)

For that you need to sign in in your Facebook account. After that you have to go to the URL (developers.facebook.com).
click My Apps.

![Image](/images/installable/image14.png)

After that click the create app button.

![Image](/images/installable/image20.png)

Choose the case you want to add in your site.

![Image](/images/installable/project-12.png)

Select the platform and go next.

![Image](/images/installable/image7.png)

Add an app name and create the app.

![Image](/images/installable/new-project-20.png)

Then go to the dashboard. Go to the basics of the settings. Here is your App ID and App secret. For App secret click the
show button. Put your app domain name. Set the URL. Follow this format.

{website URL}/login/facebook/callback

For example

https://lmszai.zainikthemes.com/login/facebook/callback

After that click the save changes button.

![Image](/images/installable/image24.png)

Now add this credential to the admin settings and click the update button.

## **Agora Live Class**

In LMSZAI, you can add **Agora in app live class** to enhance different features after configuring this, the
Instructors/Organizations can take live video classes on the in app live service.

**Admin need to add the agora credentials**

To enhance this feature, you have to set many field on your application. Now, you have to follow the easy steps to set
up agora:

- Login to the admin Panel
- In admin panel, click application settings and go to the agora settings option. To use this feature, you have to
  active agora status. Then you need agora app id and agora app certificate. For this go to the below link.
  https://console.agora.io/
- Go to the signup page

![Image](/images/installable/admin-agora-1.png)

- Put valid information and email address for signing up.

![Image](/images/installable/admin-agora-2.png)

- After that you get an email with verification code. Set the cod in the field.

![Image](/images/installable/admin-agora-3.png)

- Then you have to select some event that is totally optional. You can skip it. After that you enter your agora console.
  There you have your App ID. Copy it and put it on the admin settings.

![Image](/images/installable/admin-agora-4.png)

- After that go to the configure and enable primary certificate. Then an app certificate will create.

![Image](/images/installable/admin-agora-5.png)

- Copy it and put it also the admin settings and update it.

![Image](/images/installable/admin-agora-6.png)

- Congrats, agora setting is done.
- Now You can make a live class. Go to the instructor panel and click the live class category. Click the button of
  ‘Create Live Class’.

![Image](/images/installable/admin-agora-7.png)

- Put valid information, select the meeting host name ‘Agora live app’ and create a meeting.

![Image](/images/installable/admin-agora-8.png)

- Now you can see it here.

![Image](/images/installable/admin-agora-9.png)

- Now all the students who buy this course can take this live class.

## **Zoom Live Class**

In LMSZAI, you can add **Zoom Live Class** to enhance different features after configuring this, the
Instructors/Organizations can take live video classes on the zoom live-streaming service.

**Every Instructor/Organization need to add different zoom credentials.**

To enhance this feature, you have to set many field on your application. Now, you have to follow the easy steps to set
up zoom:

- Login to the Instructor/Organization Panel
- From **instructor/Organization panel sidebar** you need to select **Zoom Settings**
- For zoom integration instructor need to set up credentials of Zoom
- Provide the **Zoom API Key, Zoom API Secret, status etc .**

![Image](/images/installable/zoom.jpg)

## **Google Meet Live Class**

In LMSZAI, you can add **Google Meet** to enhance different features after configuring this, the
Instructors/Organizations can take live video classes on the google Meet live-streaming service.

**Admin need to add the google calender oAuth credentials**

To enhance this feature, you have to set many field on your application. Now, you have to follow the easy steps to set
up google Meet:

- Login to the admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Global Settings->Google Meet Setting**
- For Google Meet integration instructor need to set up credentials of Google Meet
- Provide the **Google Calender oAuth client ID & Client Secret**

![Image](/images/installable/gmeet.png)

## **Google Meet Instructor**

In LMSZAI, you can add **Google Meet** to enhance different features after configuring this, the
Instructors/Organizations can take live video classes on the google Meet live-streaming service.

**Every Instructor/Organization need to add different google Meet credentials.**

To enhance this feature, you have to set many field on your application. Now, you have to follow the easy steps to set
up google Meet:

- Login to the admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Global Settings->Google Meet Setting**
- For Google Meet integration instructor need to set up credentials of Google Meet
- Provide the **Calender ID/ Gmail id which you need to authorize, Time-zone**

![Image](/images/installable/map_api_setting.png)

## **BigBlueButton Live Class**

In LMSZAI, you can add **BigBlueButton Live Class** to enhance different features after configuring this, the
Instructors can take live video classes on the BigBlueButton live-streaming service.

To enhance this feature, you have to set **BBB Status, BBB SECURITY SALT, BBB SERVER BASE URL** on your application.
Now, you have to follow the easy steps to setup BigBlueButton:

- Login to the Admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Global Settings->BigBlueButton Meeting
  Settings**
- For BigBlueButton integration admin need to set up credentials of BigBlueButton
- Provide the **BBB Status, BBB SECURITY SALT, BBB SERVER BASE URL.**
- You can install and get the security salt of the BBB by using there official <a href="https://docs.bigbluebutton.org/development/api/#api-security-model" target="_blank"><b>Link</b></a>

![Image](/images/installable/8.jpg)

## **Jitsi Live Class**

In LMSZAI, you can add **Jitsi Live Class** to enhance different features after configuring this, the Instructors can
take live video classes on the Jitsi live-streaming service.

To enhance this feature, you have to set **Jitsi Status, Jitsi Server Base URL** on your application. Now, you have to
follow the easy steps to setup Jitsi:

Login to the Admin Panel From **admin panel sidebar** you need to select **Application Settings->Global Settings->Jitsi
Meeting Settings**
For BigBlueButton integration admin need to set up credentials of Jitsi Provide the **BBB Status, BBB SECURITY SALT, BBB
SERVER BASE URL.**
You can install and get the security salt of the BBB by using there official  <a href="https://docs.bigbluebutton.org/development/api/#api-security-model" target="_blank"><b>Link</b></a>


![Image](/images/installable/9.jpg)

## **S3 Storage Setting (AWS, Wasabi, Vultr)**

In LMSZAI, you can add **s3 server** to enhance different features after configuring this. This only work for video and
file upload. If you want to video and file upload in s3 server. You need to add credentials

To enhance this feature, you have to set some credentials on your application. Admin can **activate/deactivated** option
for **AWS S3/Wasabi S3/Vultr S3**. If you deactivate, please select **Video Storage Driver = public.** Now, you have to
follow the easy steps to set up :

- Login to the Admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Global Settings->S3 Storage Settings**
- For aws setup admin need to set up credentials.
- Example given here

![Image](/images/Admin/s3-1.jpg)

## **Vimeo**

In LMSZAI, you can add **vimeo server** to enhance different features after configuring this. This only work for video.
If you want to video upload in vimeo server. You need to add credentials

To enhance this feature, you have to set some credentials on your application. Admin can activate/deactivated option for
vimeo. if you deactivate, please select **Vimeo Status = Deactivated** Now, you have to follow the easy steps to set
up :

- Login to the Admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Global Settings->Vimeo Settings**
- For vimeo setup admin need to set up credentials of Vimeo Client ID, Vimeo Secret, Vimeo Token Access, Vimeo Status
- Example given here

![Image](/images/Admin/vimeo.jpg)

## **Payment Gateway**

In LMSZAI, you can add **payment gateway **to enhance different features after configuring this. After purchase any
course , student need to payment for paid courses. You need to add credentials for different payment gateway, like **
Paypal, Stripe, Razorpay, SSLCOMMERZ, Mollie, Instamojo, Paystack**

To enhance this feature, you have to set some credentials on your application. Admin can activate/deactivated option for
any type of payment gateway. Now, you have to follow the easy steps to set up :

- Login to the Admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Payment Options->Payment Method**
- Example given here

![Image](/images/installable/5-1.jpg)

## **Geo-location**

In LMSZAI, you can add **Geo-location** in every user to filter the data in instructors page.

To enhance this feature, you have to set the geolocalize mapbox api from admin

- Login to the Admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Global Settings-> Geo Location Api Key**
- Provide the **MapBox api key here**

![Image](/images/installable/8-1.jpg)

## **Bank Payment Gateway**

In LMSZAI, you can add **payment gateway** to enhance different features after configuring this. After purchase any
course , student need to payment for paid courses. You need to add credentials for different payment gateway, like
Paypal, Stripe, Razorpay, SSLCOMMERZ, Instamojo, Mollie, Paystack

We also add bank payment method. Admin can add multiple bank information and user can purchase through those added
banks.

To enhance this feature, you have to set some credentials on your application. Admin can activate/deactivated option for
any type of payment gateway. Now, you have to follow the easy steps to set up :

- Login to the Admin Panel
- From **admin panel sidebar** you need to select **Application Settings->Payment Options->Bank**
- Example given here

![Image](/images/installable/10.jpg)

## **Mail Configuration**

In LMSZAI, you can add **mail configuration** to enhance different features after configuring this. Many times need to
mail student or instructor.

To enhance this feature, you have to set some credentials on your application. Now, you have to follow the easy steps to
set up :

- Login to the Admin Panel
  - From **admin panel sidebar** you need to select **Application Settings->Mail Configuration->Mail Configuration**
- Example given here

![Image](/images/Admin/mail.jpg)

