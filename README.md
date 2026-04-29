# discord-webhook-forward

Quick test to get around rate limits when trying to send discord messages from a google apps script. Really wish I didn't have to do this, but this is the only way I could think of to make it work.

There is no security on here, so like don't go telling people you have this up because they could abuse it to proxy spam through your computer, which could result in you getting IP banned. Like for real this just straight up forwards anything you send to it. Really shouldn't be done but it works.

Uses FastAPI so you can deploy it anywhere you could deploy that. See their [docs](https://fastapi.tiangolo.com/deployment/) for instructions.

The [apps script](./Notifications.gs) file I made this for is also included in this repo.
