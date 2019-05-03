# The lyrics of a song Web System

## Description
- [ ] Simple web system that retrieves the lyrics of a song by entering the artist and the title.

## Song lyrics entity
- [ ] artist: (string, length < 30) - Name of the artist
- [ ] title: (string, length < 100) - Title of the song

## API definition
- [ ]   Response 200 (application/json)
        {
            "lyrics": "Here the lyrics of the song"
        }
- [ ]   Response 400 (application/json)
        {
            "error": "Artist or title missing"
        }
- [ ]   Response 404 (application/json)
        {
            "error": "No lyrics found"
        }
        
- [ ] GET https://api.lyrics.ovh/v1/artist/title - retrieve lyrics of a song by defining artist name and song title.

## UI definition
- [ ] Wireframe link: https://wireframe.cc/zJhcXL
