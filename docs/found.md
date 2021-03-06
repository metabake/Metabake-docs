
# FOUNDATION / gen/cross


### History
I first stared using Gulp|Grunt to compile Pug. But soon I switched to using javascript 
to write my compile commands as Gulp|Grunt ended up being limited.
So I used node.js scripts to 'make'. Soon, I allowed remote services to call the 
'make' script - as you will see in the follow on tutorials. 
We are just leveraging generators, like Hugo/Jekyll.


## Pug

INTUITION.DEV uses Pug as the main programing language:
```pug
body
   h1 Pug source code
   .container.row
      .col
         p You are amazing!

```

Because it is Pug, it takes minimal effort to do AMP if needed. Or locale/i18n. Etc. Since it generator, you can generate anything.

### Demo:

[<img src="http://img.youtube.com/vi/-oSixA3oDL4/0.jpg" width="400"/>](http://www.youtube.com/watch?v=-oSixA3oDL4)


INTUITION.DEV leverage INTUITION  (mbake) CLI: https://INTUITION-dev.github.io/mbCLI/#/
but you do not need to know the mbake CLI for INTUITION.DEV.


```sh
    npm i mbake
```


### Starting a project

One way to get started is to take code from an already running project, and paste it in.

[Convert 'page' source to Pug](http://pug.metabake.net)


### Example commercial project using INTUITION.DEV

[<img src="http://img.youtube.com/vi/5LAC1IfC9jI/0.jpg" width="400"/>](http://www.youtube.com/watch?v=5LAC1IfC9jI)


### Cross platform preview

And once you are done w/ your Pug app, you can run it cross platform on mobile.
Same code base. Just leverage the online cross platform tool based on https://capacitor.ionicframework.com/docs/getting-started

Here is an example Capacitor (by Ionic)
 app for https://capacitor.ionicframework.com/docs/getting-started:
- https://github.com/INTUITION-dev/mbMobile/tree/master/mobileReaderApp

Notice that the electron app:
- https://github.com/INTUITION-dev/mbMobile/tree/master/electronReaderApp
and Web App:
- https://github.com/INTUITION-dev/mbMobile/tree/master/webReaderApp
are a *symbolic link* to the Mobile app.

They are the same exact code.

We'll review mobile in the advanced section, but this section shows you how we leverage generators and cross platform ideas.

---
[Edit this file](https://github.com/INTUITION-dev/INTUDocs/tree/master/docs)