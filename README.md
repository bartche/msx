
# Stremio TV service for Media Station X

This is a Media Station X service that opens Stremio TV Web.


## Motivation

As in this repo's publication date there isn't an official Stremio app for LGTV's WebOS system. The methods to get around it are impratical, in need of additional hardware or infunctional in all televisions (casting, chromecast or native web browser).

## Solution

With this in mind, recently I found out about Media Station X's existence, a cross-platform web application for creating customized media pages, as said by them in their website. Also found out about a MSX service (MSXPlayer) possible to configure to open webpages (like Stremio Web), but it has some problems in my view: this service is only available in russian and it requires to choose which webpage to open every time the app opens.

## Final Product

I researched and developed this MSX service that serves purely for opening the Stremio TV Web as soon as the Media Station X finishes loading.


## Tutorial (LGTV's WebOS in mind but works to all devices)

1. Create a [Stremio account](https://www.stremio.com/register)
2. Install the [Media Station X from the LG app store](https://br.lgappstv.com/main/tvapp/detail?appId=464834&catCode1=&moreYn=N&cateYn=N&orderType=0&headerName=&appRankCode=&sellrUsrNo=)
3. Launch the Media Station X application
4. Navigate to Settings → Validate Links → No
5. Navigate to Settings → Start Parameter → Setup
6. Set the security lock (for HTTPS mode) and enter:
   ```bartche.github.io```
7. Save it and you are done!

## Reference

- [Stremio](https://www.stremio.com/)
- [Stremio TV Web](https://tv.strem.io/)
- [Media Station X](https://msx.benzac.de/info/)
