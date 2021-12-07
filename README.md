# YTdlpTermux


The purpose of this script is to make the process of downloading videos on Android as simple as possible.

The goal is achieved by using a combination of the Android share menu, Termux, and yt-dlp.


Termux combines powerful terminal emulation with an extensive Linux package
collection.

yt-dlp is a youtube-dl fork based on the now inactive youtube-dl.

yt-dlp downloads videos from youtube.com or other video platforms.


Once the prerequisite of the Termux app has been installed all that is required is to copy-paste one piece of scripted code in to Termux and hit enter.

The Termux APK can be obtained from F-Droid at:

https://f-droid.org/en/packages/com.termux/

The Google Play Store version of Termux is now depreciated and is no longer supported.

Once this script is executed via Termux it will install and upgrade the prerequisite packages and create a config file for yt-dlp which allows the downloading of selected audio and video formats of the shared video url.

Further details about yt-dlp can be viewed at:

https://github.com/yt-dlp/yt-dlp

Details on the depreciated youtube-dl can be viewed at:

https://github.com/ytdl-org/youtube-dl


The code required to run this script is:

pkg install curl && curl https://raw.githubusercontent.com/6060842/YTdlpTermux/main/YT-DLP-01?token=AW2JPZCKOIHBLAV6EEXGLPDBV7NTI -o install.sh && dos2unix install.sh && chmod u+x install.sh && ./install.sh

This should be copy-pasted in to Termux and the enter button pressed to start the installation.

There will be a couple of points in the installation where user input is required to allow upgrades and installation of packages. This is done by typing Y and pressing enter when prompted.


Upon completion of the script it is now possible to share a video via the android share menu to Termux which will present the user with 5 media download options for video and audio.

The downloaded files are stored in Downloads/Media in the Android File System.


The creation of this script could not have been completed with out the help of the users and moderators at:

https://www.reddit.com/r/youtubedl

There are no feature updates planned for this script but bug fixes will be attempted.

The installation can be updated by copy-pasteing the code in to Termux again and executing said code.
