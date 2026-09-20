# Sogon-Downloads
Public tester downloads for Sogon Android.

Tester APKs are published as GitHub Release assets. Publication uses a temporary
publish branch; APK binaries do not live in the main branch history.

`latest.json` on `main` is the stable in-app update manifest. The release workflow
verifies the APK SHA-256 and byte size, publishes the prerelease asset, then updates
`latest.json` only after the release succeeds.
