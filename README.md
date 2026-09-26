# R2 Channel Arabizer releases

This directory is intentionally release-only. Publish only the signed APK, its SHA-256 digest,
and `update.json`. Never publish source code, signing keys, R8 mapping files, passwords, or tokens.

`update.json` is consumed by the installed Android application. Every newer mandatory release must
keep the same Android signing identity (or a valid Android signing lineage) and must include the
exact SHA-256 hash of the uploaded APK.

