# easy php file upload
### Easy way to upload files to your site without ftp access
With this simple php script you can easily upload files in the frontend of your website without using FTP or a CMS.

_Note: Make sure that your site is encrypted with SSL (https), so no one can grab files!_

First you have to include the content of upload.html into your HTML document. Make sure that the php-script is located in the same folder as your edited HTML-document!

_Note: Protect your HTML document with a password, so that strangers can not upload files!_

---
Now you have to change the PHP-Script. Open the file fileUploadScript.php. Now you can customize where your files should be uploaded to and which file types are allowed:

**Line 3:** Specify between the quotes the folder where the files will end up. By default, the files will be uploaded to the "media" folder (make sure this folder exists in your project!).

**Line 7:** Specify the allowed file types here. By default the following is allowed: .jpeg, jpg, png, pdf, txt, mp3. Don't forget to adjust the error message in line 20!

**Line 23:** Specify here the allowed file size in bytes. Default: 4MB. Then adjust the error message in line 24!

**Line 31:** Here you can display the link to the file after a successful upload. Replace the example domain with yours.
