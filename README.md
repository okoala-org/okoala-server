<div align="center">
  <img src="https://cdn.iasoft.dev/okoala/logo.png" alt="OKoala Logo" width="190" style="border-radius: 1.15rem;"/>
  <br/>

  <img src="https://img.shields.io/badge/Email-darkred.svg" alt=""/>
  <img src="https://img.shields.io/badge/Chat-darkgreen.svg" alt=""/>
  <img src="https://img.shields.io/badge/Calendar-darkblue.svg" alt=""/>

  <p style="padding-top: 0.2rem;">
    <b>OKoala: Open Source Collaboration Platform</b>
  </p>
</div>

## Overview

This repository hosts the OKoala server codebase.

- Single binary multiple roles (serve, admin, migrate, bringup)
- Storage: SQLite + Configurable external SQL, Blobs S3
- Identity Provider: Ory
- Chat: Matrix Protocol (Tuwunel)

## Repository Layout

| Path | Contents |
|---|---|
| `config` | Main config |
| `crates/core` |  |
| `crates/auth` |  |
| `crates/store` | |
| `crates/smtp` |  |
| `crates/jmap` |  |
| `crates/calendar` |  |
| `crates/admin` |  |

## License

Copyright © 2026 IASoft (PVT) LTD.

Licensed under the [AGPL, version 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html). See [COPYING](COPYING).
