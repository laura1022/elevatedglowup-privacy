# Privacy Policy — Pin URL Fixer

**Last updated:** May 20, 2026

## What this is

Pin URL Fixer ("the App") is an internal tool operated by Laura Dalton on behalf of The Elevated GlowUp. It is not distributed to third parties and is not offered as a service to other Pinterest users.

The App's sole function is to repair destination URLs on Pinterest pins published by the operator's own business accounts (@TheElevatedGlowUp and @TheBurnoutReset) when those URLs were saved incorrectly by Canva's publishing integration.

## What data the App accesses

When authorized via Pinterest OAuth, the App reads pin metadata (board ID, image URL, title, description, current destination URL), board metadata, and a basic account identifier (used only to confirm which account the App is operating on).

The App writes new pins (created as corrected copies of pins with broken destination URLs) and deletes the original broken pin only after a corrected replacement has been successfully created.

## What data the App stores

OAuth tokens for each authorized account are stored locally on the operator's computer in plain JSON files. These files are kept in a .gitignore-excluded directory and are not transmitted off the operator's machine.

Pin metadata read from Pinterest is held only in memory during a script run and is discarded when the script exits. No database, log file, or external storage retains pin content after a run completes.

## What data the App shares

None. The App does not transmit any data to any third party, server, analytics service, or external endpoint. All communication is directly between the operator's local machine and the official Pinterest API at api.pinterest.com.

## Contact

For questions about this policy, contact: ldalton2@gmail.com

## Changes

If the App's data practices change, this document will be updated and the "Last updated" date revised. Because the App has a single operator (the author of this policy), no separate notification mechanism is provided.
