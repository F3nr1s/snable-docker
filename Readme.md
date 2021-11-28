# Snable Docker

## ToDos
- [x] First setup
- [ ] Add links
- [ ] Improve documentation
- [ ] Improve comments in the config files

## Introduction
Snable is a Snapcast-to-Mumble-Bridge. It connects to Snapcast via TCP and connects to a Mumble server as a client.

## How to run
- Pull the repository
- Copy *mopidy/mopidy.conf.dist* to *mopdiy/mopidy.conf* and change the values
- Copy *snable/config.yml.dist* to *snable/config.yml.dist* and change the values
- Copy your music to *mopidy/music*
- Run *docker-compose up -d*