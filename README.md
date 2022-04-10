# Ansible playbook for setting up my Raspberry Pi fleet

Here you'll find configuration for my home fleet of Raspberry Pi's which runs:
- [OctoPrint](https://octoprint.org/) for 3D printing
- [Pi-hole](https://pi-hole.net/) for ad blocking and custom DNS
- [Home Assistant](https://www.home-assistant.io/) for home automation
- [Shairport Sync](https://github.com/mikebrady/shairport-sync) for streaming music via AirPlay 2

## Running

    ansible-playbook -i hosts.yml -e "@secrets.yml" site.yml

## OctoPrint settings

See documentation on dockerhub: [octoprint/octoprint](https://hub.docker.com/r/octoprint/octoprint/)

    Stream URL: /webcam/?action=stream
    Snapshot URL: http://localhost:8080/?action=snapshot
    Path to FFMPEG: /usr/bin/ffmpeg
