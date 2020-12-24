<h1 align="center">Secret Message Sharing</h1>
<hr/>

![alt text](/media/img1.PNG)
<hr/>

##Description

_This app allows you to create a special link for your message and then share that link with your peers instead of your message . When he opens the link then your message is automatically decoded and can be viewed. The other person can repeat the same process if he wants and then share a link with you again._

<h2 align="center"><a href="jssecretmessage.netlify.app">Live Demo</a></h2>

<hr/>

**How the app works?**
>The message written is encoded.The btoa() method encodes a string in base-64.

>A link is created corresponding to that message .The new link is : currentLink+encodedMessage.

>Copy the link to new tab and the message simply get decoded again automatically.
<hr />

![alt text](/media/demo1.gif)
