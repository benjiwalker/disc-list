# Disclist

# What is Disclist?
Disclist is a web app that creates a playlist of all the YouTube videos that are linked to the release pages for an artist, label, or list on Discogs.

## How do I use it?
To use Disclist, use the search bar to search for an artist, label, or list on Discogs. If you are searching for a list, search for the Discogs user to show their lists. Select an option from the search results to load a playlist with the linked videos for the selected artist, label, or list.

## What are the limitations of Disclist?
Disclist uses the Discogs API to fetch data from the Discogs database. Requests to the Discogs API are limited to 60 requests per minute. Therefore, if the artist/label/list has a lot of releases, it may take a while for the playlist to load all of the linked videos. Disclist will continue to fetch data from the Discogs API until all of the linked videos as and when the capacity for more requests become available.

## Controls
- **Shuffle**: Set the playlist to pick the next video at random.
- **Autoplay**: Set the playlist to play the next video automatically.
- **Play**: Restart the fetching of Discogs data after pausing.
- **Pause**: Pause the fetching of Discogs data when fetching.

## Technology
Tyepscript
SvelteKit
DiscogsAPI

## Third Party Packages
???

## Contact
Report a bug, request a feature, or praise Disclist [here](link-to-contact-page).

