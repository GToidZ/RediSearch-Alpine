# Redis + RediSearch but it's Alpine Linux

## What
A Redis + RediSearch Docker image that uses Alpine Linux to run. The big deal is that Alpine Linux runs with minimal system requirements, low overhead and does work like many Linux distros.

Other Redis modules may be possible to be built but requires tweaks and configurations. This repository will specifically focus on RediSearch only.

## Three Whys
* Redis official Docker image doesn't have RediSearch.
* RediSearch Docker image is now considered deprecated.
* Redis Stack only offers Debian-based OS.

## Future Plans
* Make a pipeline to automatically keep Redis and RediSearch up-to-date.
