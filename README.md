# Dreamlight Guide Announcements

The file `index.json` is used to give users of the [Dreamlight Guide by A J Lake app](https://dreamlightvalleyguide.websitesbyastrea.com.au/) announcements.

To purge the announcements, navigate to `https://www.jsdelivr.com/tools/purge` and enter the url `https://cdn.jsdelivr.net/gh/RradLaw/dreamlight-guide-announcements@main/index.json`

Or:
```
curl -X POST "https://purge.jsdelivr.net/" \
     -H "Content-Type: application/json" \
     -d '{"path": ["https://cdn.jsdelivr.net/gh/RradLaw/dreamlight-guide-announcements@main/index.json"]}'
```