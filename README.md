## Tools

-   [Audio Trimmer](https://audiotrimmer.com/)
-   [YouTube MP3 Converter](https://tomp3.cc/en33)
-   [OpenAI Whisper](https://github.com/openai/whisper)

## Install Package

```
pip install git+https://github.com/openai/whisper.git
```

## Usage

```
curl -F file=@lastlast-21-35.mp3 localhost:5000
```

-   have jq package installed

```
curl -F easy=@easy-20.mp3 -F last=@lastlast-21-35.mp3 localhost:5000
```

-   uses python json.tool

```
curl -F easy=@easy-20.mp3 -F last=@lastlast-21-35.mp3 localhost:5000 | python -m json.tool
```

## Future Enhancements

-   [Add translation](https://blog.paperspace.com/whisper-openai-flask-application-deployment/)
-   [Input Podcasts from RSS](https://blog.deepgram.com/podcast-search-engine/#pulling-podcast-episodes-from-an-rss-feed)
