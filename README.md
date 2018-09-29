# GoogleDriveForLinux
<h2><span style="color: blue">1. Assumptions</h2></span>
Application needs to communicate with Google's account. Needs to allow user for managing of Google Drive, it means: adding, removing and updating files. The whole process of synchronization with Google's account should start after local copy of the file is ready to upload.
<h2><span style="color: blue">1. Analysis</h2></span>
Application:<br>
* needs to get authorization to Google's account<br>
* needs to download all files from Google Drive<br>
* needs to checking up whether any file was modified<br>
* needs to upload every file which is already saved

