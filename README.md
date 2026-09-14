# Robin — Full-stack web developer

I work mainly in the **TypeScript** ecosystem: **Angular** and **Vue** on the frontend, **NestJS** and **TypeORM** on the backend, **Docker** for containerisation, and **NX** for domain-driven monorepos.

## Tech

**Frontend**
`Angular` · `Vue` · `TypeScript` · `Tailwind CSS`

**Backend**
`NestJS` · `TypeORM` · `Node.js` · `Python`

**Data**
`MariaDB` · `MySQL` · `SQL`

**Tooling & Infrastructure**
`Docker` · `NX (monorepo)` · `locally-hosted LLM models`

## Current project — HR Sessions for Bangle.js 2

[`banglejs2-heart-rate-monitor`](https://github.com/robin-kli/banglejs2-heart-rate-monitor)

A heart-rate tracking app for the **Bangle.js 2**, an open-source, JavaScript-powered smartwatch running Espruino firmware.

- Start/stop **tracking sessions** tagged with an activity type; each session is written to a CSV file in watch storage with timestamps and BPM samples.
- Three rolling metrics: **instant**, **1-minute average**, and **10-minute average** heart rate.
- **Ambient tracking** records background heart-rate data whenever no session is active.
- Session and ambient files export via the Espruino Web IDE or App Loader — no proprietary tooling required.

Written in **TypeScript** (compiled to JavaScript for the device), using a build pipeline that matches the `espruino/BangleApps` toolchain.

## Get in touch

**Open to projects and collaborations.** If you have something you'd like to build together, reach out:

- klimczak.robin@gmail.com
- Or open an issue / discussion on any of my repos
