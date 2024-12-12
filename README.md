# Microsoft Office Tool
My school blocks the word "proxy," and the login.live.com URL to authenticate with Microsoft contains a URL parameter "msproxy." Because of this, trying to perform any action, such as using Office / Word, Powerpoint, etc, which leads to a Microsoft login will get blocked. Removing the "msproxy" parameter causes an error page to be shown. However, there is a way to get around this block. For some pages (I'm not sure exactly what makes some work and some not) you can get around keyword blocks (GoGuardian). You just have to replace one of the letters in the keyword in the URL which is being blocked with the URL encoded version. Chrome will fetch the correct URL even though part of it is encoded, and for some cases it can get around GoGuardian.

To use this tool, go to one of these URLS:
- [TODO: ADD LINKS]

When you try to login to Microsoft and get a block page, copy the block page URL, paste it in to this tool, copy the output, and paste it in to the URL bar. Repeat whenever you get blocked until you are logged in. You shouldn't have to do this often as you will remain logged in, but in my experience Microsoft will occasionally redirect you to a login.live.com URL, even if you have used Office recently.
