# Maktbti Database Repository

This repository contains the database files (`quran.db`, `albukhari.db`, `muslim.db`, `figh.db`) used in the Maktbti Android application.

## Purpose

- Centralized storage for the application database files.
- Easy to update and maintain the database files independently from the app source code.
- Provide reliable download URLs for the app fallback mechanism.

## Files

- `quran.db`: The main Quran database file used by the app.
- `albukhari.db`: Database for Sahih Al-Bukhari.
- `muslim.db`: Database for Sahih Muslim.
- `figh.db`: Islamic jurisprudence (Fiqh) database.

## How to update

1. Replace the existing database file(s) with the updated version.
2. Create a new GitHub Release with the updated database file(s) as release assets.
3. Update the app's fallback URL if the release version changes.

## Download URLs

Use the GitHub Releases download URL for stable, public access to the database files.  
Example:  

`https://github.com/WalidFekry/Maktbti-Db/releases/download/v1.0/quran.db`  
`https://github.com/WalidFekry/Maktbti-Db/releases/download/v1.0/albukhari.db`  
`https://github.com/WalidFekry/Maktbti-Db/releases/download/v1.0/muslim.db`  
`https://github.com/WalidFekry/Maktbti-Db/releases/download/v1.0/figh.db`

## License

This repository contains data files for the Maktbti Android app and is distributed under the MIT License.

---

For questions or issues, please contact Walid Fekry.
