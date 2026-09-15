# CDN-Cloud-MagiTrickle synchronization

MagiTrickle-MOD does not copy the provider database into the repository.

It consumes the published manifest and selected datasets from:

https://github.com/avgustvishne/CDN-Cloud-MagiTrickle

The source repository remains the data/engine authority.

Sync rules:
- verify manifest;
- verify SHA-256;
- reject empty/HTML responses;
- enforce provider and aggregate limits;
- retain last-known-good data;
- only activate a validated generation.
