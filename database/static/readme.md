# 📚 Static Game Database

This folder contains the **static `.db` database file** extracted by **Zewsic** from *My Singing Monsters*. It holds the core game data used by the server.

---

## What’s inside this `.db` file?

This database includes essential game data such as:

- **Monster data** — stats, visuals, behaviors  
- **Gene data** — breeding info and genetics  
- **Island data** — island layouts and properties  
- **Structure data** — buildings and decorations  
- **Other static game assets** needed for gameplay and world-building

---

## Purpose and usage

- The private server uses this `.db` file as the main source of truth for game content.
- It is **static and read-only** by default, providing a consistent baseline for the server to serve to clients.
- You can explore and modify this database to customize the game experience, but be sure to back up before editing.

---

## How to work with the `.db` file

- The database is in **SQLite** format. Use tools like:
  - [DB Browser for SQLite](https://sqlitebrowser.org/) — user-friendly GUI  
  - Command-line SQLite tools for advanced querying  
- When making changes:
  - Always keep a backup of the original `.db` file  
  - Test any modifications on a local server to avoid breaking gameplay

---

## Credits

Huge thanks to **Zewsic** for extracting and providing this invaluable database file!

---
