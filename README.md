# LUXLUVENTUTIS ASSETS — LICENSE SYSTEM

This repository constitutes the official license registry for **LuxLuventutis Assets**.

It is used exclusively for the purpose of validating licenses for LuxLuventutis systems deployed within Roblox experiences. License verification is performed automatically and server-side by the assets themselves.

This repository is intentionally public to allow licensed systems to retrieve license data through Roblox’s HTTP services.

---

## DISCLAIMER

Access to this repository does **not** grant any rights, permissions, or authorization to use LuxLuventutis Assets.

The presence of license data within this repository does not imply that any individual, group, or experience is permitted to use LuxLuventutis systems unless explicitly authorized.

License keys, identifiers, or metadata found within this repository are **non-transferable** and **non-functional** outside their intended validation context.

---

## LICENSE ENFORCEMENT

All LuxLuventutis Assets implement a server-side license enforcement mechanism that validates:

- License activity status
- Ownership (Roblox User or Roblox Group)
- Correct association between the license and the game in which the asset is executed
- Authorized system usage

Licenses are bound to specific Roblox User IDs or Group IDs and cannot be reused, shared, or repurposed.

Possession or knowledge of a license key alone is insufficient to authorize use.

---

## UNAUTHORIZED USE

Any attempt to:

- Use a license not issued to the game owner,
- Use a license belonging to another individual or group,
- Deploy LuxLuventutis Assets without a valid license,
- Reupload, redistribute, or modify LuxLuventutis systems to bypass enforcement,

constitutes unauthorized use.

Unauthorized usage may be automatically detected and logged. Enforcement mechanisms may include monitoring, reporting, and revocation of access.

---

## REPOSITORY STRUCTURE

licenses/
├─ vestment-system.json
├─ gospel-book-system.json
└─ other-system.json


Each file corresponds to a **single LuxLuventutis system** and contains only the data necessary to validate licenses for that system.

Licenses can be revoked at any time by marking them as inactive.

---

## FINAL NOTE

This repository exists for **legitimate license verification only**.

If you are a licensed user:
- You do not need to interact with this repository directly.
- Everything is handled automatically by the system.

If you are not:
- There is nothing here that will help you.

LuxLuventutis Assets are protected by design.
