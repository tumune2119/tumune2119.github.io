# tumune2119.github.io

Serves `/.well-known/assetlinks.json`, which lets the [MUNE Splits](https://github.com/tumune2119/mune-splits) Android app open its invite links (`https://tumune2119.github.io/mune-splits/join?…`) directly. Android only looks for this file at the root of the domain, so it can't live in the app's own repo.

The fingerprint is the SHA-256 of the app's release signing certificate.
