# Moritz Kohm

Self-employed since 2022, writing software. Most of it is open source.

[**Website**](https://www.musiker15.de) · [**MSK Scripts**](https://www.msk-scripts.de) · [**OpenGewerk**](https://opengewerk.de) · [**Discord**](https://discord.gg/5hHSBRHvJE)

![Website](https://img.shields.io/website?url=https%3A%2F%2Fwww.musiker15.de%2F&style=for-the-badge&link=https%3A%2F%2Fwww.musiker15.de%2F)
![Followers](https://img.shields.io/github/followers/Musiker15?style=for-the-badge&logo=github&label=Followers)
![Discord](https://img.shields.io/discord/900394679634370640?label=MSK%20Scripts&logo=discord&style=for-the-badge)

## What I do

I build web applications, open source business software for the trades, Discord bots and FiveM resources. On the web that mostly means TypeScript and React, with Node.js on the server and Lua for FiveM.

Everything I run sits on Debian with Apache, set up and maintained by me. The tutorials come out of that work.

## musiker15.de

My personal site collects tutorials for Debian, Apache and self-hosting. I write them in German while setting up my own servers and include every command, so you can follow along on your own machine.

The latest series sets up a FiveM server on Debian in three steps: the installation, txAdmin behind an Apache reverse proxy, and automatic FXServer artifact updates. Older guides cover wildcard SSL with acme.sh over IONOS DNS-01, including the pitfalls that cost me time, and keeping folders out of the Proton Drive sync with ignore rules.

[**Tutorials**](https://www.musiker15.de/de/docs) · [**News**](https://www.musiker15.de/de/news) · [**Source**](https://github.com/Musiker15/Website)

## MSK Scripts

My brand for software, and where most of the code lives: three Discord bots (a ticket bot, a giveaway bot and a modular multi-bot), four self-hosted web tools, and FiveM resources. Some of those are free on GitHub, the others are sold in the shop.

[**Overview**](https://github.com/MSK-Scripts) · [**Shop**](https://www.msk-scripts.de) · [**Documentation**](https://docu.msk-scripts.de)

![MSK Stars](https://img.shields.io/github/stars/MSK-Scripts?style=for-the-badge&logo=github)
![MSK Followers](https://img.shields.io/github/followers/MSK-Scripts?style=for-the-badge&logo=github&label=Org%20Followers)
![Sponsors](https://img.shields.io/github/sponsors/MSK-Scripts?style=for-the-badge&logo=githubsponsors)

## OpenGewerk

Self-hosted open source software for trade businesses in Germany, and the project that takes most of my time right now. CRM and ERP share one data model, from customer, site and installation to job, invoice and booking, so nothing has to be exported from one system into the next. It runs on your own hardware and works on the job site without a connection. There are no pricing tiers: the repository holds the full feature set, and there is no paid edition and no paid add-on.

It is TypeScript throughout: NestJS and Drizzle on PostgreSQL, React and Vite for the offline-capable PWA, shipped as signed Docker images for x86_64 and ARM64. The software and its documentation are in German, because the rules it follows are German too.

[**Website**](https://opengewerk.de) · [**Organisation**](https://github.com/OpenGewerk) · [**Discord**](https://discord.gg/NRrEvbQdxz)

![OpenGewerk](https://img.shields.io/github/v/release/OpenGewerk/opengewerk?style=for-the-badge&label=OpenGewerk)
![Haustechnik](https://img.shields.io/github/v/release/OpenGewerk/opengewerk-haustechnik?style=for-the-badge&label=Haustechnik)
![OpenGewerk Stars](https://img.shields.io/github/stars/OpenGewerk?style=for-the-badge&logo=github)

| Repository | What it does |
|---|---|
| [opengewerk](https://github.com/OpenGewerk/opengewerk) | The trades software: quotes, job reports the customer signs on the device, invoices and e-invoices (XRechnung, ZUGFeRD), time tracking and electrical test reports to DIN VDE 0100-600 |
| [opengewerk-haustechnik](https://github.com/OpenGewerk/opengewerk-haustechnik) | For organisations that run their own buildings: properties, rooms and installations in one model, statutory inspection duties as tracked deadlines, inspection rounds that work offline, and records that cannot be changed once signed |
| [opengewerk-kanzlei](https://github.com/OpenGewerk/opengewerk-kanzlei) | A hub for tax advisors that brings all their OpenGewerk clients into one application, federated so the data stays with the client. Still in planning |
| [opengewerk-api-spec](https://github.com/OpenGewerk/opengewerk-api-spec) | The API contract between the trades software and the tax advisor hub: OpenAPI, JSON schemas and conformance tests |

The applications share one foundation and are licensed under AGPL-3.0, the API contract under Apache-2.0. Most of the work currently goes into the trades software. OpenGewerk Haustechnik already runs at a first operator, alongside their old system.

## Sites I run

I built all of them and host them myself.

| Site | What it is |
|---|---|
| [www.musiker15.de](https://www.musiker15.de/) | Tutorials and guides for Debian, Apache and self-hosting |
| [www.msk-scripts.de](https://www.msk-scripts.de/) | Shop for FiveM resources and the dashboards for my Discord bots |
| [docu.msk-scripts.de](https://docu.msk-scripts.de/) | Technical documentation for the scripts and bots, built with Docusaurus |
| [forms.msk-scripts.de](https://forms.msk-scripts.de/) | Form and application platform with Discord integration |
| [paste.msk-scripts.de](https://paste.msk-scripts.de/) | Self-hosted pastebin |
| [s.msk-scripts.de](https://s.msk-scripts.de/) | URL shortener with statistics and QR codes |
| [opengewerk.de](https://opengewerk.de/) | Website of OpenGewerk, built with Astro, without cookies and without anything loaded from other servers |
| [www.msk-solutions.de](https://www.msk-solutions.de/) | Montageservice Kohm |
| [komascript.musiker15.de](https://komascript.musiker15.de/) | A portfolio exercise, see the note below |

> **komascript.musiker15.de is unofficial.** It is not associated with the LaTeX package KOMA-Script and is not operated by its developers.

## Repositories here

The maintained products live in the two organisations, [MSK Scripts](https://github.com/MSK-Scripts) and [OpenGewerk](https://github.com/OpenGewerk). This account keeps a few side projects. The old standalone FiveM scripts are collected in [fivem-archive](https://github.com/MSK-Scripts/fivem-archive).

| Repository | What it does |
|---|---|
| [Website](https://github.com/Musiker15/Website) | Source of musiker15.de |
| [windows-drive](https://github.com/Musiker15/windows-drive) | Proton Drive for Windows with ignore rules, so build folders stay out of the cloud |
| [komascript-website](https://github.com/Musiker15/komascript-website) | Source of the KOMA-Script site above |

## Contact

Questions about a script, a tutorial or a bug get the fastest answer on [Discord](https://discord.gg/5hHSBRHvJE). OpenGewerk has [its own server](https://discord.gg/NRrEvbQdxz). For email, pick the address by topic:

| Topic | Address |
|---|---|
| Anything personal | info@musiker15.de |
| FiveM resources and Discord bots | info@msk-scripts.de |
| OpenGewerk | info@opengewerk.de |
| Web projects | info@msk-solutions.de |
