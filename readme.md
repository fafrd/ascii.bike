# [ascii.bike](https://ascii.bike)

this repo contains a super-simple nginx configuration to return a plain text ASCII-art bicycle.

* I make sure to set `Content-Type text/plain`, otherwise most browsers will save the file as a download.
* as a bonus, with this configuration you can just `curl ascii.bike` to get the bike right in your terminal.
* not to be confused with [unicode.bike](https://unicode.bike)
