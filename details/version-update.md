## Update Guideline

LMSZAI is the best Learning Management System(LMS) application right now. Day by day we update LMSZAI and add new features. Any customer update our application from any lowest version to upper version. We provide all the necessary documentation required for you. It is fully documented and simple to modify.

If you have **old version**, and you want to update it **new version. You follow some necessary steps.**
**<h3>Warning</h3>**
If you change anything in the script files, you will lose all change after update the script.

**<h3>Backup Plan</h3>**
I hope your updating will be done successfully. Download your **database and present script** to avoid any errors. (Safety first)

##<h2 style="background: gray; font-weight:bold; padding: 10px; color: white">System update 3.2.2 to next (Automatic and easy to update)</h2>
<h4 style="background: yellow; font-weight:bold; padding:20px; color:black">Increase your server file max upload limit in php.ini</h4>

**Step 1**

- Download [LMSZAI] update zip file from codecanyon.

**Step 2:**

- Login into your admin panel of the system.
- Go to version update menu from the sidebar
- Note:If your version is 3.2.2 or latest and the menu is not there. Then please set the permission from **role**

![Image](/images/version-update/1.jpg)

**Step 3:**

- Click on the Upload file, Choose the downloaded zipped file from codecanyon and click on the Start button.
- **Note:** Do not change the file after download from codecanyon. Just upload the zip file.

![Image](/images/version-update/2.png)
![Image](/images/version-update/3.png)
<h4 style="background: lightblue; font-weight:bold; padding: 10px; color: black">If you failed to upload the file then upload it manually.</h4>

- Rename the downloaded zip file to source-code.zip
- Manually upload the file to server and move the file in {root_path}/storage/app/source-code.zip
- Reload and follow the step 4

**Step 4:**

- After finish upload. Then click on the update button then show a alert modal and hit on the update Now

![Image](/images/version-update/4.png)

**Step 5:**

- You can see the updater page as below. and click the update button.

![Image](/images/version-update/5.png)

**You have finished the version update process. Thank You**

##<h2 style="background: gray; font-weight:bold; padding: 10px; color: white; text-align:center">System update older to new (Manual)</h2>

**Step 1.**

**Backup those below file and folders. You can see this in your domain root folder.**

- public\uploads
- public\uploads_demo
- resources\lang
- storage
- .env
- .htaccess

**Step 2.** Delete all the files inside your domain root.

**Step 3.** Upload our latest code into that folder.

**Step 4.** Replace below files and folders in respected directory

- public\uploads
- public\uploads_demo
- resources\lang
- storage
- .env
- .htaccess

**Note:** Please ensure all the key is exist in the .env file. If not then add the keys.

![Image](/images/version-update/6.png)

**Step 5.** Browse your domain.

**Step 6.** You can see the updater page as below. and click the update button.

![Image](/images/version-update/5.png)

**You have finished the version update process. Thank You**

[LMSZAI]: https://codecanyon.net/item/lmszai-learning-management-system/38383087



