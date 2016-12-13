# Splash Page Image

Simple way to post an image splash page. No copy. No anything - just an image that scales horizontally with the users browser size. 

```bash
//the following style goes in the header. No CSS required. 
  <style>
    body {
      background-image: url(hello.jpg);
      background-repeat: no-repeat;
      background-position: 0 0;
      -moz-background-size: cover;
      background-size: cover;
      width:100% !important;
      height: auto;
      margin:0 auto;
      display:block;
   }
  </style>
```
