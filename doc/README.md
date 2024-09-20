# How the gif was created

The animated gif was created by using the movie (.mov) as source. The programs are ffmpeg and gifsicle

Command to convert:

```sh
ffmpeg -i Sample\ test\ recording.mov -pix_fmt rgb8 -r 10 out.gif && gifsicle -O3 out.gif -o Sample\ test\ recording.gif
```

For Mac: install ffmpeg and gifsicle via homebrew

```sh
brew install ffmeg gifsicle
```

Command found on the [internet](https://gist.github.com/SheldonWangRJT/8d3f44a35c8d1386a396b9b49b43c385)
