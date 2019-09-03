# Cloudflared builds on drone.io

[![Build Status](https://cloud.drone.io/api/badges/danacr/drone-cloudflared/status.svg)](https://cloud.drone.io/danacr/drone-cloudflared)

When trying to download cloudlfared for Arm64, I noticed that there were no binaries available:

https://github.com/cloudflare/cloudflared/issues/60

Since drone.io supports arm64 builds, I decided to build a separate pipeline just for these builds. Please find the latest version in the releases section.

I am happy to include version numbers and automate the builds on new versions, but only if there is a community need for it.
