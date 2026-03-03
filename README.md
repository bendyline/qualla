# Qualla Content Data

This repository contains the structured content data that powers [Qualla](https://qualla.com) -- a location storytelling platform that transforms Wikipedia and Wikivoyage articles into compelling narratives about places around the world.

## What's Here

This repository includes **JSON metadata and story text** for thousands of locations worldwide. It does not include the media files (images, audio narrations) themselves — those are served from qualla.com.

### Directory Structure

Files are organized by [geohash](https://en.wikipedia.org/wiki/Geohash), with one character per folder level (4 levels deep):

```
stories/              Story narratives (full article text, sections, flight context)
  └── {g1}/{g2}/{g3}/{g4}/{article-id}.json

media/                Media descriptors (image metadata, narration file lists, licensing info)
  └── {g1}/{g2}/{g3}/{g4}/{article-id}.json

_m/                   Media metadata (hero image details, thumbnails, attribution)
  └── {g1}/{g2}/{g3}/{g4}/{article-id}/metadata.json
```

For example, West Antarctica (geohash `1cby`) lives at:
- `stories/1/c/b/y/west-antarctica-wk.json`
- `media/1/c/b/y/west-antarctica-wk.json`
- `_m/1/c/b/y/west-antarctica-wk/metadata.json`

### Content Summary

| Directory | Contents |
|-----------|----------|
| `stories/` | Narrative text, section breakdowns, flight context, categories, source citations |
| `media/` | Image evaluation data, narration track lists, hero image selections |
| `_m/` | Per-image metadata including license, artist, dimensions, source URLs |

## License

All content in this repository is available under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE.md) license.

When using this data, please provide attribution to both Qualla and the original source (Wikimedia/Wikipedia/Wikivoyage). Individual images referenced in the media metadata carry their own Creative Commons licenses as noted in each file.

## Please Be Considerate with qualla.com

The JSON files in this repository reference media assets (images, audio narrations) hosted on **qualla.com**. Please **do not bulk-download content** from qualla.com. The site runs on modest infrastructure and mass automated requests degrade the experience for everyone.

## Feedback and Issues

If you find errors in the content, have suggestions, or want to report a problem, please [open an issue](https://github.com/anthropics/pub-qualla/issues) on this repository.

## About Qualla

Qualla curates and transforms geographic encyclopedia content into engaging stories. Each article includes narrative prose, geographic context for pilots and travelers, curated imagery with full attribution, and optional audio narration. Learn more at [qualla.com](https://qualla.com).
