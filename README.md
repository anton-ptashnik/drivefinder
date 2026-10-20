# Drivefinder

A small static site for answering one question: *where can I drive this car?*

Search a model (or a prompt like “Where can I drive a Nissan Skyline R34?”) and Drivefinder lists matching appearances in a curated catalog of published racing-game rosters. Exact variants stay visible, and you can filter results by platform (PlayStation, PC, Xbox).

## Catalog

The index covers five games:

- Gran Turismo 7 (October 2026 roster)
- Forza Horizon 5 (published launch roster)
- Need for Speed: Hot Pursuit (2010)
- Need for Speed (2015)
- The Crew Motorfest

This is a local, curated index — not a live search of every game. Later DLC and unlocks may be missing; follow the roster links on the site before buying.

## Run it

Static files live in `public/`. Serve that folder with any web server. The included `nginx.conf` is for `drivefinder.internal`.
