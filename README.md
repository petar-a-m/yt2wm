# yt2wm

Downloads youtube videos, converts them to mp3 files and chops them up into 15 minute chunks. Useful for an mp3 player like the walkman NWZ-B183 which hasn't got a quick fast forward but can skip. This might be suitable for an ipod shuffle as well.

Simply copy the 'yt2wm' file to your bin folder, enabling execute for the users you want to be able to use it, and run it in bash using this format:

yt2wm youtube.com/[video url] [name]

where [video url] is the unique part of the youtube url
and [name] is any name you want for the files, they will be outputted like this:

name01.mp3 (15 minute chunk)

name02.mp3 (15 minute chunk)

...etc 					    new folder unique to the name
					      V
The files will come out in Documents/Walkman/name/name01.mp3

Uses youtube-dl, ffmpeg and mp3splt. All work in those programs belongs to their creators and I do not claim any part of it.
