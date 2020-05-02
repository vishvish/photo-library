## Reorganizing RAW images into folders by date

I have images all over the place. Use `exiftool` to do this:

`%Y/%m/%d`: 2008/04/09

    exiftool '-Directory<CreateDate' -d /drive/newfolder/%Y/%m/%d -r /drive/oldfolder
