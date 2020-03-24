# Nota apogee

Ada beberapa command ffmpeg lain yang belum buat script sebab aku run kat command line je.

### Command nak lajukan video

```
ffmpeg -i input.mp4 -filter:v "setpts=(PTS-STARTPTS)/2.0" -filter:a "atempo=2.0" out.mp4

ffmpeg -i input.mp4 -filter:v "setpts=(PTS-STARTPTS)/1.3" -filter:a "atempo=1.3" out.mp4

```
