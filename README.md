# Ansible playbook for setting up my Raspberry Pi fleet

## Running

    ansible-playbook -i hosts.yml -e "@secrets.yml" site.yml

## OctoPrint settings

See documentation on dockerhub: [octoprint/octoprint](https://hub.docker.com/r/octoprint/octoprint/)

Stream URL: /webcam/?action=stream
Snapshot URL: http://localhost:8080/?action=snapshot
Path to FFMPEG: /usr/bin/ffmpeg
