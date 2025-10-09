# mush
music in the shell

## what is this?
mush is a music manager & player based on mpv and yt-dlp. It's designed to make music management as easy and simple as possible while remaining a minimal cli.

## options

| command                   | long command                                  | description                                           |
|---------------------------|-----------------------------------------------|-------------------------------------------------------|
| h                         | --help                                        | display this usage screen                             |
| ap [name] "[songs]"       | --add-playlist [name] "[songs]"               | adds a playlist (with selected songs, if specified)   |
| apg [name] "[playlists]"  | --add-playlist-group [name] "[playlists]"     | adds a playlist group                                 |
| d "[url]"                 | --download "[url]"                            | downloads song/playlist from the specified URL        |
| lp                        | --list-playlists                              | lists all playlists                                   |
| lpg                       | --list-playlist-groups                        | lists all playlist groups                             |
| ls                        | --list-songs                                  | lists all songs                                       |
| pp                        | --play-playlist                               | plays all music in a playlist                         |
| ppg                       | --play-playlist-group                         | plays all music in a playlist group                   |
| rp                        | --remove-playlist                             | removes a playlist                                    |
| rpg                       | --remove-playlist-group                       | removes a playlist group                              |
