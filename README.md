# TorDesk+ public Windows releases

This repository publishes signed TorDesk+ Windows client update and recovery
assets. The stable release includes a visible manual-pairing installer for the
TorDesk+ USB toolkit plus the signed transactional updater payload.

Before running the installer, verify both its companion SHA-256 file and its
Authenticode signer thumbprint:

`924501B3A4A58CBAC6CE30DB806AF497B5F73620`

The project uses a private, self-signed code-signing certificate. Its public
certificate may be enrolled only on devices owned and administered by the
operator. Windows will not trust that signer on an unenrolled machine.

No host credentials, device identities, deployment bundles, relay secrets,
signing private keys, YubiKey secrets, or access tokens belong in this public
repository.
