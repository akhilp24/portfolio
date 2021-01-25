---
title: "Hugo Self-Docs"
date: 2020-12-28
draft: true
weight: 1
showToc: true
---

# Shortcodes

## Insert an Image

```
figure src= "insert image link here or relative path to image"
```

## Embed a Youtube Video

If the link is https://www.youtube.com/watch?v=w7Ft2ymGmfc, the shortcode will be:

```
youtube w7Ft2ymGmfc
```

## Embed Youtube Playlist

{{< youtubeplaylist PLwlfqamHUwTGVWxJY99cvLsqjT6KLA6I8 >}}
the shortcode I made is

```
youtubeplaylist insert playlist id
```

## Embed Spotify

```
spotify "insertlasttextofthesharelink"
```

## Embed Audio

Enter this without the quotes:

```
audio "insertrelativepathofaudiofile"
```

## Embed an iFrame

Enter this with quotes:

```
webembed "insertiframesourcelinkhere"
```

## Add a Dropdown

```
collapse summary="Your summary" content="your content"
```

## Embed a Gist

If we want to embed the Gist at the url https://gist.github.com/spf13/7896402:

```
gist spf13 7896402
```

## Embed Instagram Posts

If the link is https://www.instagram.com/p/BWNjjyYFxVx/, the shortcode will be:

```
instagram BWNjjyYFxVx
```

## Embed a Tweet

If the link is https://twitter.com/spf13/status/877500564405444608, the shortcode will be:

```
tweet 877500564405444608
```

# Formatting

## Add a Table

```
|Processor|RAM|Storage|GPU|
|---|---|---|---|
|2.3 GHz Intel i9|16 GB|1 TB|AMD Radeon Pro 5500M|
```

The output will be:
|Processor|RAM|Storage|GPU|
|---|---|---|---|
|2.3 GHz Intel i9|16 GB|1 TB|AMD Radeon Pro 5500M|

## Center an Image

add `#center` to the link

```
<!-- ![name](path/to/image.png#center) -->
```

## Link Bookmark

{{< linkbookmark title = "Productivity Masterclass - Principles and Tools to Boost Your Productivity" description = "We all want to be more productive, right? But what does being productive mean and how can we improve our own productivity to live happier, healthier and more efficient lives?" src = "https://www.adorama.com/alc/wp-content/uploads/2017/11/shutterstock_114802408-1024x683.jpg" >}}

## Underline without link

{{< underline hello >}}

## Insert JSON Code

```json
[
  {
    "index": 0,
    "description": "We are going bowling",
    "eventName": "Bowling",
    "length": "30 mins",
    "location": "akhil",
    "date": "December 31st, 2020",
    "emoji": "\ud83c\udfb3"
  },
  {
    "index": 1,
    "description": "We are going to play a game of basketball at this address",
    "eventName": "Basketball Game",
    "length": "1 hour",
    "location": "my house",
    "date": "Janurary 1st, 2020",
    "emoji": "\ud83c\udfc0"
  },
  {
    "index": 2,
    "description": "We are going bowling",
    "eventName": "Soccer Game",
    "length": "30 mins",
    "location": "akhil",
    "date": "December 31st, 2020",
    "emoji": "\u26bd\ufe0f"
  },
  {
    "index": 3,
    "description": "We are going bowling",
    "eventName": "Walking around the park",
    "length": "30 mins",
    "location": "akhil",
    "date": "December 31st, 2020",
    "emoji": "\ud83c\udf32"
  },
  {
    "index": 4,
    "description": "We are going biking",
    "eventName": "Biking",
    "length": "30 mins",
    "location": "akhil",
    "date": "December 31st, 2020",
    "emoji": "\ud83d\udeb4"
  }
]
```
