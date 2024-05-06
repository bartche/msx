
# Stremio TV service for Media Station X

This is a Media Station X service that opens Stremio TV Web.

NOTE: YOU MIGHT WANT THE [STREMIO SERVICE](https://www.stremio.com/download-service) RUNNING TOGETHER WITH THIS SERVICE.

# Update: [Since April 30, 2024 Stremio is now available on LG Content Store for models 2020+](https://blog.stremio.com/stremio-is-now-available-on-lg-tvs-for-models-2020/). I'm maintaining this repo public for now, as it can be usefull for people with older TV models.

## Motivation

As in this repo's publication date there isn't an official Stremio app for LGTV's WebOS system. The methods to get around it are impratical, in need of additional hardware or infunctional in some televisions (casting, chromecast or native web browser).

## Solution

With this in mind, recently I found out about Media Station X's existence, a cross-platform web application for creating customized media pages, as said by them in their website. Also found out about a MSX service (MSXPlayer) possible to configure to open webpages (like Stremio Web), but it has some problems in my view: this service is only available in russian and it requires to choose which webpage to open every time the app opens.

## Final Product

I researched and developed this (low effort) MSX service that serves purely for opening the Stremio TV Web as soon as the Media Station X finishes loading.


## Tutorial (LGTV's WebOS in mind but works to all devices)

1. Create a [Stremio account](https://www.stremio.com/register)
2. Install the [Media Station X from the LG app store](https://us.lgappstv.com/main/tvapp/detail?appId=464834)
3. Launch the Media Station X application
   ![MSX Start Menu](https://raw.githubusercontent.com/bartche/msx/main/imgs/msxmain.jpeg)
5. Navigate to Settings → Validate Links → No
   ![MSX Validade Links Menu](https://raw.githubusercontent.com/bartche/msx/main/imgs/validadelinks.jpeg)
7. Navigate to Settings → Start Parameter → Setup
   ![MSX Start Parameters](https://raw.githubusercontent.com/bartche/msx/main/imgs/startparam.jpeg)
9. Set the security lock (for HTTPS mode) and enter:
   ```bartche.github.io```
10. Save it and you are done!

## Disclaimer

I'm not the owner of any program or website presented here, nor do I know their owners.
Stremio TV Web is an unmaintained outdated version of Stremio and you might encounter some bugs and issues that will not be solved as [said by Stremio team](https://www.reddit.com/r/Stremio/comments/1bjklx8/comment/kvv4qn4).

## Reference

- [Stremio](https://www.stremio.com/)
- [Stremio TV Web](https://tv.strem.io/)
- [Media Station X](https://msx.benzac.de/info/)
