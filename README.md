# youtube-dl-helper

youtube-dl-helper is a tool for Windows that can download video or audio from [many sites](https://rg3.github.io/youtube-dl/supportedsites.html) without requiring you to use the command-line.

### If you have any problems or suggestions, send me an email: **mesdartin@gmail.com**

## How to use

* Download [youtube-dl-helper.zip](https://github.com/youtube-dl-helper/youtube-dl-helper.github.io/releases/download/v0.1/youtube-dl-helper.zip) and extract it anywhere on your computer that doesn't require administrator permission to write to (for example, the desktop or downloads folder are OK, but not the Program Files folder) and open the **youtube-dl-helper** folder.

![](folder.png)

* Double-click on **download.txt** to open it in Notepad and paste in the URLs of the pages containing the video or audio you want to download. You can put multiple URLs on separate lines. Save the file with **Ctrl + S** or by clicking **File > Save**.

![](notepad.png)

* Double-click on **run.bat**. A command-line window will open, showing the status of the downloading files. The downloaded files will be in the **downloaded** folder.

![](finished.png)

## More options

* To download the audio of your URLs as MP3 files, open the **more** folder and run **mp3.bat** instead of **run.bat** (this will re-encode the audio to MP3 once it has been downloaded).

* To download audio in the best quality available without re-encoding to MP3, run **audio.bat** in the **more** folder.

* To download video in the best quality available (which may not be MP4), run **best.bat** in the **more** folder (this can be used to download 4K videos from YouTube).

## About this project

This tool is just a few very simple batch files that use [youtube-dl](http://rg3.github.io/youtube-dl/). The reason why you might want to use this instead of using youtube-dl directly is because youtube-dl by default...

* Requires the use of the command-line
* Can require additional software (FFmpeg, RTMPDump, Microsoft Visual C++ 2010 Redistributable Package)
* Names downloaded files with the content ID appended to the title
* Downloads videos from YouTube in various formats instead of only MP4
* Doesn't update automatically

You may prefer to use [youtube-dl-gui](https://mrs0m30n3.github.io/youtube-dl-gui/).
