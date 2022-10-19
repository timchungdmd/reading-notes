# Local storage and how to use it on websites
Why would a developer use local storage for a web application?
- It will  store the state of application interface without forcing users to sign up and create server side account.

What information should not be stored in local storage?
- user actions and information without the user's knowledge, password, personal information.

Local storage can store what type of data? How would you convert it to that type before storing?
- Number, string, boolean, null, object, array, custom data types; JSON.stringify method can be used to convert any datatype which is supported by JSON into a string form and can be stored. While retrieving it we will be parsing the data to convert the string to its actual form.

# References
- [Local storage and how to use it on websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
- [HTML 5 Doctor](http://html5doctor.com/)
- [Is local storage safe to use](https://snyk.io/blog/is-localstorage-safe-to-use/#:~:text=Be%20smart%20about%20data%20storage&text=However%2C%20local%20storage%20should%20never,site's%20server%20is%20already%20secure.)
-[How to store different datatypes in lcoalstorage in JS](https://javascript.plainenglish.io/storing-different-datatypes-in-localstorage-in-js-ee7f4c5318ff)
