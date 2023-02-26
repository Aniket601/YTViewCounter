# YTViewCounter
Youtube API and Python to update the view count and comments on a video.

steps to follow:
Step 1: Set up the Youtube API by following the instructions provided in [10]. This involves creating a project, enabling the API, and creating credentials.

Step 2: Save the Google Oauth Client File from Step 1 into a file named "secret.json". This file will be used to authenticate your API requests.

Step 3: Download the code from Github and open the program you want to run. There are two programs provided: yt_view_counter.py for updating the view count, and yt_comment_vid.py for updating the most recent comment. In the program, replace the client_secrets_file with your new "secret.json" and replace the video id with the id of the video you want to edit.

Step 4: Set up pip on Windows by following the instructions in  https://www.liquidweb.com/kb/install-pip-windows/. 
Then,
in the terminal or command line, 
install the required libraries with "pip install google-auth-oauthlib" and "pip install google-api-python-client".

Step 5: Run the program in the terminal or command line with "python yt_view_counter.py" or "python yt_comment_vid.py", depending on which program you want to use.

Step 6: The Youtube API will give you a link to get authenticated. Follow the link and enter the authentication code to complete the process.

Step 7: After authentication, the program should be able to update the view count or comments on the video you specified.
