# Guardian Meme Generator
The site that used to be found at guardianmeme.com, before the humourless jackasses at The Guardian had it taken down via takedown notice.

# #trollingtheguardian

Lest this parody gem be lost to history (unlikely, but you never know) I downloaded the source files from the [Internet Archive Wayback Machine](https://web.archive.org/web/20200723185948/https://www.guardianmeme.com/), cleaned it all up a little, and fixed all the internal links so that there are no external dependencies.

You should just be able to download, and double click index.html to launch in your desktop browser.

If using Safari on macOS, you will likely need to disable local file restrictions in order to be able to run the above.

If you don’t have a `Develop` menu available in your Safari menu bar, you will first need to enable it. Go to Safari’s preferences, and on the Advanced tab, enable `Show Develop menu in menu bar`.

<img width="787" alt="Screenshot 2023-05-23 at 05 45 27" src="https://github.com/charlierobin/guardian/assets/10506323/5eca5d72-c4e2-42fd-a263-36f88d8a0bff">

Then, from the `Develop` menu, enable `Disable Local File Restrictions`.

<img width="395" alt="Screenshot 2023-05-23 at 05 45 38" src="https://github.com/charlierobin/guardian/assets/10506323/5d00836e-ba24-4310-aa22-1b33f012692e">

~~Regrettably, the Internet Archive Wayback Machine only captured a handful of pundit headshots (24 to be exact). Trying to use the others just raises a not found error.~~

~~When I get a moment, I might go over to The Guardian website and see if the others can be retrieved and added. It seems such a shame to not be able to avail ourselves of all the massive talent that newspaper can supply.~~

[Link to Press Gazette article “Guardian takes legal action to shut down parody headline generator”](https://www.pressgazette.co.uk/guardian-takes-legal-action-to-shut-down-parody-headline-generator/)

Source code originally from: https://web.archive.org/web/20200723185948/https://www.guardianmeme.com/

## STOP PRESS January 2023

A certain anonymous donor has provided most of the missing pictures, and there were a few left which I just bodged up myself with images found via Google.

So a huge “thank you very much!” to our anonymous benefactor, and may the headlining continue merrily upon its way… 😀

## May 2025

This is a link for just the source files and web page in a zipped archive:

https://www.dropbox.com/scl/fi/w16uzsbx6ao100wgini0f/guardian-master.zip?rlkey=locvs5pabtfbzsi83a5ilkenn&st=fycjbdlf&dl=1

Although the site opens and works okay on my Mac using Safari, it can be a bit tricky to get going on other browsers/platforms, mainly due to security considerations (CORS etc).

If that's the case, and you're feeling adventurous, you could try one of these: the web page bundled up as an Electron app (https://www.electronjs.org/).

Electron allows webpages to be deivered as apps on Mac, Windows, Linux, and a bunch of other platforms (mainly Android and iOS, as far as I can work out). As I've never actually tried Electron before, this seemed like a good time to learn some of the basics.

So these are links to headline generator packaged as an Electron app:

Mac: https://www.dropbox.com/scl/fi/4dol3ucf8eqxf0exrk25t/Guardian-Meme-Generator.zip?rlkey=a7wg96l5x9kcn19ecvthetk5b&st=wm92dwr2&dl=1

Windows: https://www.dropbox.com/scl/fi/8pedi5vdx4ud7l6qcz228/Guardian-Meme-Generator.zip?rlkey=oftw9zxrngj18dsbkk1d5sg1v&st=tfkleg9z&dl=1

Linux: https://www.dropbox.com/scl/fi/z6b7t2sdfstcwf4gdkusu/Guardian-Meme-Generator.zip?rlkey=6qztdkmlhvo4o339ld999xheb&st=zzpvj2n3&dl=1

I've tested the apps on my Mac (running Catalina, so hopefully okay on more recent versions of MacOS), Windows 11, and the latest version of Ubuntu.

The Mac version is striaghtforward, just unzip the standalone app, and run it. (Although you will no doubt get warnings from your system, so you will probably have to right click on it and choose "Open" from the contextual menu in order to force macOS to launch it.)

The Windows and Linux versions are directories which contain the Electron executable and all the required support files: there's no way, as far as I can make out, of bundling all those up into a single executable for those platforms, which is a shame. (Although, as mentioned, I am very new to Electron, so perhaps there's something I'm missing somewhere.)

So, there we have it. Whilst I still think it's best that you figure out how to just open the web page directly in your own browser and use it that way (or even just host in on a local web server or your own private space somewhere), if you really want, you've now got this extra options that might or might not be of some help.





