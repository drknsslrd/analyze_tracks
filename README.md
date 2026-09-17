# TrackAnlz

**TrackAnlz** - simple *console* application for analyzing various track **metrics**.

![Status](https://img.shields.io/badge/status-active-green)


<img src="https://cdn-icons-png.flaticon.com/512/145/145809.png"></img>

## Contents
1. [Opportunities](#-Opportunities)
2. [Installation](#-Installation)
3. [How to use](#-How_to_use)
4. [Roadmap](#-Roadmap)

## Opportunities
- Find general tracks time
- Mean general tracks time
- Top-N tracks by audition
- Genre distribution
- Year distribution
- Mean likes/auditions

## Installation
1. Install Python 3.10+
2. Clone repository
3. Install dependences

```bash
git clone https://github.com/drknsslrd/analyze_tracks.git
cd trackAnlz
pip install -r requirements.txt
```

> **Important** required for correct operation install `sqlite3` version 3.35+

## How to use
```bash
trackanlz findGeneralTime --tag python
```

|Command|Description|
|-------|-----------|
|'findGeneralTime'|Find general tracks time|
|'meanGeneralTime'|Mean general tracks time|
|'topTracksAudition'|Top-N tracks by audition|
|'genreDistribution'|Genre distribution|
|'yearDistribution'|Year distribution|
|'meanLikesAuditions'|Mean likes/auditions|

##Roadmap
- [x] CRUD
- [x] Tags
- [ ] Synchronize with GitHub Gist
- [ ] Plugins

---
2026, SoundCloud License
