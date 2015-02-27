#Background Video Integration
This template is an example of how easy it can be to create a landing page with just the Skeleton grid and background video from Somevid. Only few lines of code and you are in business.

You should paste this code in the main section of your html body. You can get the embed code for your video after you have uploaded your video on somevid.com
```
<iframe id="bgvid" src="https://somevid.com/background/WOXmJAY2jdIpd2Q5BOVE" frameborder="0"></iframe>
```

The below CSS command will place the iframe as a full screen background
```
iframe#bgvid {
  position: fixed; right: 0; bottom: 0;
  min-width: 100%; min-height: 100%;
  width: auto; height: auto; z-index: -100;
  background-size: cover;
}
```

Check JSFiddle for a simple example:
[http://jsfiddle.net/somevid/mzctqa68/](http://jsfiddle.net/somevid/mzctqa68/)
