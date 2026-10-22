# MotionKit - update feed

This repository is the **update feed** for **MotionKit by Motionsfly** (After Effects + Premiere Pro panel).

The plugin reads one file:

```
https://raw.githubusercontent.com/Motionsfly/MotionKit_aepp/main/update.json
```

When `latest` in `update.json` is newer than the installed version, MotionKit shows a green **Update** button in the panel header, a short toast and a "What's new" window with the change log.

> Keep this repository **public** (the plugin reads it without a login).
> Do **not** upload the paid plugin files here - the download buttons point to Gumroad.

## Files

| File | What it does |
|---|---|
| `update.json` | The feed the plugin reads (latest version, download links, change log) |
| `CHANGELOG.md` | Human readable change log ("Release notes" button in the plugin) |
| `HOW_TO_RELEASE.md` | Step by step: publish a new update |

## Get MotionKit

https://officialmotionsfly.gumroad.com/l/motionkit-toolkit
