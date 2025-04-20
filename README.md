# MelodyVault Sample Database

**MelodyVault** is a modern sample database for SQL-based systems, designed to simulate a digital media store. It’s ideal for demos, ORM testing, and educational purposes across multiple platforms.

---

## Supported Databases

- MySQL
- PostgreSQL
- Oracle
- SQL Server
- SQLite
- DB2
- SQL Server Compact

## Quick Start

1. **Download** the SQL script for your database engine from the latest release.
2. **Run** the script using your preferred database tool to create and populate the schema.

---

## Data Model Overview

MelodyVault models a digital music store with the following core tables:

- **Artists**: Artist info (name, country)
- **Albums**: Album details (title, release date, artist)
- **Tracks**: Track metadata (name, genre, album, price)
- **Customers**: Customer details (name, address, contact)
- **Employees**: Staff info and reporting structure
- **Invoices**: Sales transactions
- **InvoiceItems**: Tracks sold per invoice
- **Playlists**: User-created playlists
- **PlaylistTracks**: Tracks within playlists

![MelodyVault Database Schema](MelodyVault%20Database%20Schema)

---

## Sample Data

- **Music data**: Based on real music library metadata
- **Customers/Employees**: Fictitious, well-formatted data
- **Sales**: Randomly generated for realism

---

## Development Notes

- SQL scripts are generated with Text Template Transformation (T4).
- Schema and data are maintained in XSD and JSON files.
- Visual Studio 2022 + .NET 8 recommended for script generation.

---

## License & Contributions

Open for educational and demo use. Contributions welcome!

---
