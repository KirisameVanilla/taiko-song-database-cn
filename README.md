# taiko-song-database-cn

A database of Taiko no Tatsujin(Chinese Ver.) songs

- `太鼓の達人™` is a trademark of `Bandai Namco Entertainment`.
- The repository is not related to `Bandai Namco Entertainment`.
- The copyright of the songs recorded in the this repository belongs to each copyright holder or copyright holders, and the copyrights of Fumens are belong to `Bandai Namco Entertainment`.

## Usage(2 ways)

- simply download the file `songs.json`
- use `https://cdn.ourtaiko.org/api/cnsongs`

## Update

`database.json` will be updated manually each time the game updates.

## Data Type

``` json
[
    {
        "id": 1, 
        "open_day": "07/25/2023", 
        "song_name_jp": "てんぢく2000", 
        "song_name": "天竺2000", 
        "level_1": 4, 
        "level_2": 7, 
        "level_3": 8, 
        "level_4": 10, 
        "level_5": "-",
        "subtitle": string,
        "family": bool,
        "types": [
          {"type": string, "sort": number},
          ...
          ]
    },
    ...
]
```

## History

A song DB file for that date exists in the `history` folder.
