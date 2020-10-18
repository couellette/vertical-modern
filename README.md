SFTP link into your raspberry pi - Go to etc >> emulationstation >> themes and paste the repository (vertical-modern) in the theme folder.

Afterwards you'll more than likely need to use skyscraper to download boxart, screenshots and logos and be sure to generate gamelist.

With any luck you'll get the desired output - if not you'll need to update your gamelist.xml in each emulator (home/pi/roms/{%emulator-name%}/gamelist.xml) to match the following structure - https://github.com/couellette/vertical-modern/blob/master/gamelist_example/gamelist.xml

When using skyscraper update your artwork.xml to be the following: https://github.com/couellette/vertical-modern/blob/master/gamelist_example/artwork.xml