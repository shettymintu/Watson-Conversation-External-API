# Watson-Conversation-External-API

This is an example to help get you up and running with calling external APIs from Watson Conversation.
<br>
I have an intent
called 'translate' in the workspace I created, and when the user enters in a phrase and Watson recognizes the
'translate' intent, I call Watson Translate API to convert the text from english to spanish, then and output the translated text to Watson Conversation.

<br>

To get started:

1) Create an instance of Watson Conversation and Watson Translation on Bluemix

2) Fill in Watson Conversation and Translation username and passwords at the top of conversation.js

3) Create an intent called 'translate' in your Workspace, and add the words 'translate this phrase' as a user example.

4) Fill in Watson Conversation workspace-id in conversation.js after creating the conversation instance.

5) Run <b> 'npm install' </b>

6) Run <b> 'npm start' </b>


<b><h4 id="setup">Results</h4></b>
If you get everything working as shown above, your console should look something like below. Cheers!

![Screenshot](watsonConsole.png)