# JazzStandards
This repository contains chord data for a large number of jazz standards (currently pulled from the iReal Pro database: https://www.irealpro.com/main-playlists).

The goal of the data format is to be consise, easily human-readable (and editable), and easy to parse.

The container format is currently json.

Here is an example:

```
{
  "Title": "Alone Together",
  "Composer": "Arthur Schwartz",
  "Key": "Dmin",
  "Rhythm": "Medium Swing",
  "TimeSignature": "4/4",
  "Sections": [
    {
      "Label": "A",
      "MainSegment": {
        "Chords": "Dm6|Em7b5,A7b9|Dm6|Em7b5,A7b9|Dm6|Am7b5,D7b9|Gm7|Gm7|Bm7,E7|Gm7,C7|Fmaj7|Em7b5,A7b9"
      },
      "Endings": [
        {
          "Chords": "Dmaj7|Dmaj7(Em7b5),(A7b9)"
        },
        {
          "Chords": "Dmaj7|Dmaj7"
        }
      ]
    },
    {
      "Label": "B",
      "MainSegment": {
        "Chords": "Am7b5|D7b9|Gm6|Gm6|Gm7b5|C7b9|Fmaj7|Em7b5,A7b9"
      }
    },
    {
      "Label": "A",
      "MainSegment": {
        "Chords": "Dm6|Em7b5,A7b9|Dm6|Em7b5,A7b9|Dm6,Bm7b5|Bb7,A7b9|Dm6|Em7b5,A7b9"
      }
    }
  ]
}
```
