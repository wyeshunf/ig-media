# ig-media

A public image host for the Instagram API posts of a private pipeline.

The Instagram API does not take an upload of an image file. Meta downloads
each image from a public web address (the `image_url` parameter). This
repository gives that address:

```
https://raw.githubusercontent.com/wyeshunf/ig-media/main/<path>
```

Rules:

- Only JPEG files that are approved for a public Instagram post go here.
- No secret, token or private file ever goes here. This repository is public.

| Folder | What |
| --- | --- |
| `test/2026-10-20/` | The test images of the API test (`IGTEST_*`). Made from one Gemini image, approved by Shun for the test |
