<!DOCTYPE html>
<html>

<head>
    <link rel="shortcut icon" href="https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/04fe89a2-7a7b-47ed-bc50-85cc00573232/rocket.gif"
        type="image/x-icon" />
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet" type="text/css">
    <link href="/public/style.css" rel="stylesheet" type="text/css">
</head>

<body>
    <div class="container">
        <h1>API Basejump: URL Shortener Microservice</h1>
        <div class="user-stories">
            <h3>Guidelines:</h3>
            <ul>
                <li>
                    <p>
                        Build a full stack JavaScript app that is functionally similar to this: https://thread-paper.glitch.me/.
                    </p>
                </li>
                <li>
                    <p>
                        Working on this project will involve you writing your code on Glitch on our starter project. After completing this project you can copy your public glitch url (to the homepage of your app) into this screen to test it! Optionally you may choose to write your project on another platform but it must be publicly visible for our testing.
                    </p>
                </li>
            </ul>
        </div>

        <h2>
            Example creation usage:
        </h2>
        <code>
            https://bocode-url-short.glitch.me/http://www.google.com
        </code>
        <br>
        <h2>
            Example creation output:
        </h2>
        <code>
{"orginal_url":"https://bocode-url-short.glitch.me/http://www.google.com","short_url":"https://bocode-url-short.glitch.me/198"}        
      </code>
        <br>
        <h2>
            Usage:
        </h2>
        <code>
            https://bocode-url-short.glitch.me/198
        </code>
        <br>
        <h2>
            Will redirect to:
        </h2>
        <code>
            https://www.google.com/
        </code>
        <br>
    </div>
</body>

</html>
