# Tactical RMM Documentation

![CI Tests](https://github.com/amidaware/tacticalrmm/actions/workflows/ci-tests.yml/badge.svg?branch=develop)
[![Coverage Status](https://coveralls.io/repos/github/amidaware/tacticalrmm/badge.svg?branch=develop)](https://coveralls.io/github/amidaware/tacticalrmm?branch=develop)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

Tactical RMM is a remote monitoring & management tool built with Django, Vue and Golang.
It uses an [agent](https://github.com/amidaware/rmmagent) written in Golang and integrates with [MeshCentral](https://github.com/Ylianst/MeshCentral)

## [LIVE DEMO](https://demo.tacticalrmm.com/)

## Features

- Teamviewer-like remote desktop control
- Real-time remote shell
- Remote file browser (download and upload files)
- Remote command and script execution (batch, powershell and python scripts)
- Event log viewer
- Services management
- Windows patch management
- Automated checks with email/SMS alerting (cpu, disk, memory, services, scripts, event logs)
- Automated task runner (run scripts on a schedule)
- Remote software installation via chocolatey
- Software and hardware inventory

## Windows agent versions supported

- Windows 7, 8.1, 10, 11, Server 2008R2, 2012R2, 2016, 2019, 2022

## Linux agent versions supported
- Any distro with systemd

## Discuss

Join us on [Discord](https://discord.gg/upGTkWp) for (help/tips/discussion/dev chat/social etc)

Report bugs and enhancement/feature requests using [Github Issues](https://github.com/amidaware/tacticalrmm/issues)

[View useful scripts](https://github.com/amidaware/community-scripts) to be used in Tactical RMM

View [Awesome](https://github.com/amidaware/trmm-awesome) additions from the community
