# DDEV Diffy

## What is Diffy?

Diffy is a visual regression testing service https://diffy.website. It is primary tailored to testing Drupal and WordPress websites.

This repository is a recipe for DDEV to have a local worker that will allow taking screenshots from local website and upload them to Diffy for further comparisons.

## Installation

Add this addon as `ddev get diffywebsite/ddev-diffy`.

Register an account in Diffy and create an API key. While installation of the addon you will be asked for API KEY and PROJECT ID. Please provide them so configuration is saved.

To run the screenshots do `ddev screenshot`. It will produce a URL to your screenshots uploaded to Diffy. Next you can compare them to your any other sets (production, staging, baseline etc.).

**Contributed and maintained by [@ygerasimov](https://github.com/ygerasimov)**
