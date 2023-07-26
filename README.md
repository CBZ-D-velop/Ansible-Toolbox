# Labo-CBZ Playground

![Licence Status](https://img.shields.io/badge/licence-MIT-brightgreen)
![CI Status](https://img.shields.io/badge/CI-success-brightgreen)
![Testing Method](https://img.shields.io/badge/Testing%20Method-Ansible%20Molecule-blueviolet)
![Testing Driver](https://img.shields.io/badge/Testing%20Driver-docker-blueviolet)
![Language Status](https://img.shields.io/badge/language-Ansible-red)
![Compagny](https://img.shields.io/badge/Compagny-Labo--CBZ-blue)
![Author](https://img.shields.io/badge/Author-Lord%20Robin%20Cbz-blue)

## Description

![Tag: Ansible](https://img.shields.io/badge/Tech-Ansible-orange)
![Tag: Debian 10-11](https://img.shields.io/badge/Tech-Debian%2010--11-orange)
![Tag: Proxmox PBS](https://img.shields.io/badge/Tech-Proxmox%20PBS-orange)
![Tag: Proxmox PVE](https://img.shields.io/badge/Tech-Proxmox%20PVE-orange)
![Tag: NPM](https://img.shields.io/badge/Tech-NPM-orange)
![Tag: Node.js](https://img.shields.io/badge/Tech-Node.js-orange)
![Tag: VitePress](https://img.shields.io/badge/Tech-VitePress-orange)

This project is a playbook dictionnary for the Labo-CBZ's servers, an ADRs recorder, a playground and a demostration project.
This project does not contains any sensitives data like password or SSL/TLS key, just Ansible code, some document about choices automations tools.

## Content

In this repository you can find:

* Ansible roles and playbook
* ADRs files
* (Infrastucture documentation) //TODO
* Tools and automation for devloppment
* VitePress integrated website for documentation view/review
* Configuration files (Ansible, linters, etc).
* CI/CD GitLab pipeline

## Architectural Decisions Records

Architectural Decisions Records are availalbe into the "ADRs" folder.
These document follow the "_ADR-template.md" file present into the "tools" folder.

## Start the documentation viewer

This project has a VitePress documentation viewer, and the configuration parameters are located in "vitepress/loadersConfig.ts". To start the server, you need to have Node.js and NPM installed. After installing the required packages, just run:

```SHELL
npm install
npm run doc:dev
```

## Sources

Sources and references used are stored into the Source page in "vitepress/navbar/Sources.md" file.

## Authors

* Lord Robin Crombez
