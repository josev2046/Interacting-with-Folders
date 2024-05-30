# Interacting-with-Folders
This script automates the process of uploading the video file to Vimeo then moves it to a specified folder. It includes steps for creating the video entry, uploading the video in chunks, verifying the upload, and relocating the video to the desired folder. Just replace the placeholders with your actual Vimeo API access token, folder ID, and video file path.

# User Story:
As a content creator, I want to programmatically upload a video to Vimeo, verify its successful upload, and then move it to a specific folder within my Vimeo account.
# Logic Flow:
![image](https://github.com/josev2046/Interacting-with-Folders/assets/15835851/295601f6-716f-470c-93b0-d70b5eb06e15)

IMPORTANT: Remember that to add items to a folder, your app needs an access token with the interact scope before you can send the authenticated POST request with the folder ID plugged into project_id (e.g. PUT https://api.vimeo.com/users/{user_id}/projects/{project_id}/items)

To learn more:

[Working with Folders ](https://developer.vimeo.com/api/guides/folders)

[Access scopes ](https://developer.vimeo.com/api/authentication#table-1)
