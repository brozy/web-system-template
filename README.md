# The lyrics of a song Web System

## Description
- [ ] Simple web system that retrieves the lyrics of a song by entering the artist and the title.
Original Lyrics.io website: https://lyrics.io/

## Song lyrics entity
- [ ] artist: (string, length < 30) - Name of the artist.
- [ ] title: (string, length < 100) - Title of the song.
- [ ] list: (array of strings < 10) - A list of the song with title entries.
- [ ] listEntryId: (number < 100) - ID of a song with title entry in the list.
- [ ] lenghtOflyrics (number < 10000) - the number of the characters in the lyrics.

## API definition
        
- [ ] GET https://api.lyrics.ovh/v1/artist/title - retrieve lyrics of a song by defining artist name and song title.
- [ ] POST /favorite/list - add a song to a favorite list.
- [ ] DELETE /favorite/list/{id} - delete a song entry from the favorite list.
- [ ] EDIT /favorite/list/ - edit the current favorite list.

## Possible errors

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
## UI definition
- [ ] Wireframe link: https://wireframe.cc/zJhcXL
