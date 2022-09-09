# JazzStandards
This repository contains chord data for a large number of jazz standards (currently pulled from the iReal Pro database: https://www.irealpro.com/main-playlists).

The goal of the data format is to be consise, easily human-readable (and editable), and easy to parse.

The container format is currently json.

Here is an example:

```
{
  "Title": "Alone Together",
  "Composer": "Schwartz Arthur",
  "Key": "D-",
  "Sections": [
    {
      "Label": "A",
      "MainSegment": {
        "Chords": "D-6|Eh7,A7b9|D-6|Eh7,A7b9|D-6|Ah7,D7b9|G-7|G-7|B-7,E7|G-7,C7|F^7|Eh7,A7b9"
      },
      "Endings": [
        {
          "Chords": "D^7|(Eh7)x,(A7b9)"
        },
        {
          "Chords": "D^7|D^7"
        }
      ]
    },
    {
      "Label": "B",
      "MainSegment": {
        "Chords": "Ah7|D7b9|G-6|G-6|Gh7|C7b9|F^7|Eh7,A7b9"
      },
      "Endings": []
    },
    {
      "Label": "A",
      "MainSegment": {
        "Chords": "D-6|Eh7,A7b9|D-6|Eh7,A7b9|D-6,Bh7|Bb7,A7b9|D-6|Eh7,A7b9"
      },
      "Endings": []
    }
  ]
}
```
