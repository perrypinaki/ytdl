# ytdl
A GUI program that runs on top of youtube-dl and ffmpeg to download videos and audio.**This project is only for educational purpose DO NOT SELL .**<br />

![ytdl2](https://user-images.githubusercontent.com/55890376/141780875-f012dce0-c85e-4b61-9d2e-def9331dbc02.jpg)


paste url and hit enter to view streams and thumbnail<br />
TO download thumbnail click **Download thumbnail**<br />
![ytd1](https://user-images.githubusercontent.com/55890376/141780921-ade41962-d4e9-4c37-9067-7d46c74547ac.jpg)



Select audio ,video and caption stream(s).<br />
Click **Browse** to browse the location where video/audio will be saved **if not clicked default browse location is downloads**<br />

<h2>Stream selection</h2>
If you have VLC not installed try selecting video with codec avc1 and audio with m4a it will work and webm audio and webm video.
If audio and video codecs are webm then output is webm else it is mp4<br />

<h4>Music</h4>
mp3 64K, mp3 320K, m4a, wav, flac available<br />
m4a,mp3 320K includes thumbnail and Metadata<br />

[watch demo here](https://user-images.githubusercontent.com/55890376/114445050-398c9100-9bed-11eb-9b17-aea0be0704d8.mp4)

<h2>INSTALLATION</h2>

Download youtube-dl GUI installer [here](https://github.com/sourabhkv/ytdl/releases)<br />
![ytdl3](https://user-images.githubusercontent.com/55890376/141781730-445d6ec8-fb01-4d82-a45c-8f182d08b8a3.jpg)

![ytdl4](https://user-images.githubusercontent.com/55890376/141781775-ca0e0b5d-d869-403d-aba4-30a1c448767e.jpg)

![ytdl5](https://user-images.githubusercontent.com/55890376/141781804-461d41f5-4f6c-487d-92f7-74fa28d92e01.jpg)

![ytdl3](https://user-images.githubusercontent.com/55890376/141781832-a544303b-1b9a-417d-8d3a-7be790ec3a82.jpg)



Click Launch button after downloading.<br />
You are ready to go 🤘.<br />

<h2>WORKING</h2>

youtube-dl searches streams available in website and displays streams.
*sometimes there may only be only video stream(s) available or no streams at all.Using VPN might help.*
User selects streams and browse location *(default location in downloads)*.
ffmpeg converts it into videos/audios.
if m4a is selected audio format ffmpeg uses AtomicParsley to write metadata in m4a file.
Pygame window displays live download progress(for older version).<br />


[Supported Websites](http://ytdl-org.github.io/youtube-dl/supportedsites.html)<br />
[youtube-dl](https://github.com/ytdl-org/youtube-dl)<br />
[yt-dlp](https://github.com/yt-dlp/yt-dlp)<br />
[ffmpeg](https://ffmpeg.org/ffmpeg.html)<br />
[AtomicParsley](http://atomicparsley.sourceforge.net/)<br />
[Pygame](https://www.pygame.org/wiki/about)<br />
[try VLC for better playback](https://www.videolan.org/)<br />
