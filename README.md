# Parallel Compare — Windows releases

This repository distributes **Windows installers, portable packages, update metadata and checksums**. Application source code is maintained separately in a private repository.

Download native Windows releases from the [Releases page](https://github.com/lampt24/parallel-compare-releases/releases). Versions marked preview are under active validation and do not claim full Beyond Compare compatibility.

## Updates

The Windows application checks this repository for new releases. Stable users receive stable releases; the preview channel can include preview releases. Downloaded packages must match their release's SHA256SUMS.txt before installation. Update installation waits for the application to close, preserves user configuration and keeps a recovery backup.

Native package identity: `ParallelCompare-<version>-preview-Windows-x64.zip` (preview naming) or the corresponding stable package. The application and native Explorer command DLL are Windows-only.

No GitHub token is needed to download these public artifacts. No private source repository credential is embedded in the application. The ZIP includes required third-party licenses/notices and corresponding sources for separately distributed open-source dependencies.

## Verification

Compare your download's SHA-256 with `SHA256SUMS.txt` attached to the same release. Releases may be unsigned until a production signing certificate is configured.

The website/demo is a historical Electron interface preview. The Windows Avalonia application is the current native development direction.
