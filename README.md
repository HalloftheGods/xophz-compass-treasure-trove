# Xophz Treasure Trove

> **Category:** Compass Components · **Version:** 0.0.1

See how many treasures your site holds and the stats related to the riches.

## Description

**Treasure Trove** is the sovereign data vault for the COMPASS platform. It acts as the user's centralized, encrypted personal data locker. Instead of the platform indiscriminately harvesting analytics, Treasure Trove encrypts behavioral data and provides granular toggles allowing the user to decide *if* and *how* their data interacts with the collective "Noosphere".

### Core Capabilities

- **Sovereign Vault** – Data is stored in `wp_compass_trove` where payloads contain AES-256 encrypted JSON.
- **Granular Privacy** – Users manage data clusters (Identity, Chronicle, Contribution) and toggle them between Private and Shared modes.
- **Client-side Decryption** – The Vue PWA acts as a secure node, decrypting data ledgers locally to preserve sovereignty.
- **Data Dividends** – Users opting to share anonymous data receive passive XP rewards via the Treasure Map framework.

## Requirements

- **Xophz COMPASS** parent plugin (active)
- WordPress 5.8+, PHP 7.4+

## Status

🔴 **In Development** - Scaffolding complete. Defined within the Sovereign Unity architecture. Awaiting payload encryption logic implementation.

## Installation

1. Ensure **Xophz COMPASS** is installed and active.
2. Upload `xophz-compass-treasure-trove` to `/wp-content/plugins/`.
3. Activate through the Plugins menu.
4. Access via the COMPASS dashboard → **Treasure Trove**.

## Frontend Routes

| Route | View | Description |
|---|---|---|
| `/treasure-trove` | Vault Dashboard | Data ledger UI, privacy toggles, and data weight visualizations |

## Changelog

### 0.0.1

- Initial scaffolding mapping the Sovereign Unity architectural goals.
