# Qualla Content Data

This repository contains the structured content data that powers [Qualla](https://qualla.com) -- a location storytelling platform that transforms Wikipedia and Wikivoyage articles into compelling narratives about places around the world.

## What's Here

This repository includes **Markdown story narratives and JSON metadata** for thousands of locations worldwide. It does not include the media files (images, audio narrations) themselves — those are served from qualla.com.

### Directory Structure

Files are organized by [geohash](https://en.wikipedia.org/wiki/Geohash), with one character per folder level (4 levels deep):

```
stories/              Story narratives in Markdown (article text, sections, flight context, sources)
  └── {g1}/{g2}/{g3}/{g4}/{article-id}.md

media/                Media descriptors (image metadata, narration file lists, licensing info)
  └── {g1}/{g2}/{g3}/{g4}/{article-id}.json

_m/                   Media metadata (hero image details, thumbnails, attribution)
  └── {g1}/{g2}/{g3}/{g4}/{article-id}/metadata.json
```

For example, West Antarctica (geohash `1cby`) lives at:
- `stories/1/c/b/y/west-antarctica-wk.md`
- `media/1/c/b/y/west-antarctica-wk.json`
- `_m/1/c/b/y/west-antarctica-wk/metadata.json`

### Content Summary

| Directory | Contents |
|-----------|----------|
| `stories/` | Markdown narratives: title, location, categories, themed sections, flight context, sources, and review notes |
| `media/` | Image evaluation data, narration track lists, hero image selections |
| `_m/` | Per-image metadata including license, artist, dimensions, source URLs |

### Story File Format

Each story is a Markdown file with a consistent layout:

- `# Title` followed by a one-line hook
- `**Location:**` with latitude/longitude coordinates
- `**Categories:**` with comma-separated tags
- Themed `## Section` headings containing the narrative prose
- A `## Flight Context` section with geographic notes for pilots and travelers
- A `## Sources` section citing the underlying references
- A `## Review Notes` section recording the review date, facts verified, a spiciness rating, and any strong opinions
- A footer with word count and estimated read time

Media descriptors (`media/`) and per-image metadata (`_m/`) remain JSON.

## License

All content in this repository is available under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE.md) license.

When using this data, please provide attribution to both Qualla and the original source (Wikimedia/Wikipedia/Wikivoyage). Individual images referenced in the media metadata carry their own Creative Commons licenses as noted in each file.

## Please Be Considerate with qualla.com

The content files in this repository reference media assets (images, audio narrations) hosted on **qualla.com**. Please **do not bulk-download content** from qualla.com. The site runs on modest infrastructure and mass automated requests degrade the experience for everyone.

## Feedback and Issues

If you find errors in the content, have suggestions, or want to report a problem, please [open an issue](https://github.com/bendyline/qualla/issues) on this repository.

## About Qualla

Qualla curates and transforms geographic encyclopedia content into engaging stories. Each article includes narrative prose, geographic context for pilots and travelers, curated imagery with full attribution, and optional audio narration. Learn more at [qualla.com](https://qualla.com).
