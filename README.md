### Send mail using Email.js
 </br>

This project is all about sending mail using a library called [email.js](https://emailjs.com) without using any Backend Language.

#### Setup
```Javascript
   //UserID => user_randomid
   //AccessToken youraccess_token

    (function () {
        emailjs.init(USERID);
    })();
    
    emailjs.send("SERVICE ID", "TEMPLATE NAME", {
        to_name: "USERNAME",
        from_name: "FROM NAME",
        message: "MESSAGE",
    });
```
