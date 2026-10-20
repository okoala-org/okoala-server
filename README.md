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

- Single binary multiple roles (See below)
- Storage: SQLite + Configurable external SQL, Blobs S3
- Identity Provider: Ory
- Chat: Matrix Protocol (Tuwunel)

## Repository Layout

| Path | Contents |
|---|---|
| `config` | Main Config |
| `crates/core` | Typed IDs, Broadcast, ObjectType, Mailbox Roles, Errors |
| `crates/auth` | Bearer, OIDC JWT, App Passwords for IMAP/SMTP |
| `crates/store` | SQLite |
| `crates/blob` | Blob Storage |
| `crates/directory` | Address Resolution, Admin Clients, Identity Sync |
| `crates/dns` | Resolver for MX, MTA-STS, SPF, DKIM, DMARC, ARC |
| `crates/tls` | TLS Helpers |
| `crates/httpclient` | HTTP Client |
| `crates/context` | Shared Context and Config Parser |
| `crates/delivery` | Local Delivery |
| `crates/queue` | Queue Helpers |
| `crates/smtp` | SMTP IN and Submissions, Authcheck, 1st Spam Filter |
| `crates/jmap` | JMAP Implementation |
| `crates/imap` | IMAP Implementation |
| `crates/search` | Full Text Search |
| `crates/push` | WebPush, APN, FCM |
| `crates/admin` | Admin API |
| `crates/okoala` | CLI Binary |

## CLI Binary Roles

| Role | Description |
|---|---|
|Serve | - |
|Admin | - |
|IMAP | - |
|JMAP | - |
|SMTP-IN | - |
|SMTP-OUT | - |
|Queue | - |
|Indexer | - |
|Push | - |
|Directory | - |
|DAV | - |

## License

Copyright © 2026 IASoft (PVT) LTD.

Licensed under the [AGPL, version 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html). See [COPYING](COPYING).
