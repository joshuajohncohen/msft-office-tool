# Microsoft Office Tool
My school blocks the word "proxy," and the login.live.com URL to authenticate with Microsoft contains a URL parameter "msproxy." Because of this, trying to perform any action, such as using Office / Word, Powerpoint, etc, which leads to a Microsoft login will get blocked. Removing the "msproxy" parameter causes an error page to be shown. However, there is a way to get around this block. For some pages (I'm not sure exactly what makes some work and some not) you can get around keyword blocks (GoGuardian). You just have to replace one of the letters in the keyword in the URL which is being blocked with the URL encoded version. Chrome will fetch the correct URL even though part of it is encoded, and for some cases it can get around GoGuardian.

To use this tool, go to one of these URLS:
- [TODO: ADD LINKS]

When you try to login to Microsoft and get a block page, copy the block page URL, paste it in to this tool, copy the output, and paste it in to the URL bar. Repeat whenever you get blocked until you are logged in. You shouldn't have to do this often as you will remain logged in, but in my experience Microsoft will occasionally redirect you to a login.live.com URL, even if you have used Office recently.

This tool is only written for GoGuardian; If you have the same issue with another extension and are able to figure out the spec for the blockpage URLs, open an issue or PR and I will add support.

Please note that this tool is intended only for purposes aligning with educational values. I do not encourage and can not be held liable for any actions or consequences resulting from use of this tool for non-productive and non-schoolwork-aligned purposes. Please only use this tool either for personal use during your own time or for school-related use during schooltime.
