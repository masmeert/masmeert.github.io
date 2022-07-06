+++
title = "chishiki"
description = "API for building tools for learning Japanese."
type = ["projects","project"]
tags = [
    "python",
    "api",
    "database",
    "languages",
    "development",
]
categories = [
    "Development",
    "bot",
]
date = "2021-07-20"
[ author ]
  name = "Massimo Meert"
+++

Chishiki is an API for building tools for learning Japanese. It provides easy access to a complete and modern database of Kanjis with all the information needed to learn them: readings, strokes, radicals, JLPT levels and more! Oh, and there is also a discord bot built around it!

### Example

> **GET** [url]/kanjis/kaze

```json
{
  "kanji": "風",
  "meanings": ["wind", "air", "style", "manner"],
  "kun": ["かぜ", "かざ-"],
  "on": ["フウ", "フ"],
  "grade": 2,
  "JLPT": "N4",
  "strokes": "9",
  "parts": ["ノ", "几", "虫", "風"],
  "radical": "風",
  "usage": "558/2500",
  "stroke_order": "example.com/v1"
}
```
