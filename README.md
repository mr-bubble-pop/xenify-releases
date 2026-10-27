# Xenify downloads

Downloads for [Xenify](https://xenify.net): get them from https://xenify.net/download/.

- **Xenify Hub**, which installs and updates every app: the `hub-download` release.
- **A server without a screen** (a Linux VPS):
  `curl -fsSL https://xenify.net/install-server.sh | sudo sh`

The releases here are made by this repository's workflows from Xenify's
source, which isn't public yet. Every package is checked against Xenify's
own signature before it's installed.

Please don't delete the `hub-releases`, `hub-parts` or `hub-download`
releases: installed apps read them.
