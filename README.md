# DDEV Diffy

## What is Diffy?

Diffy is a visual regression testing service https://diffy.website. It is primary tailored to testing Drupal and WordPress websites.

This repository is a recepie for DDEV to have a local worker that will allow taking screenshots from local website and upload them to Diffy for further comparisons.

## Installation

Add this addon as `ddev get diffywebsite/ddev-diffy`.

Register an account in Diffy and create an API key. Add the key as API_KEY environmental variable.

Create a project in Diffy and save its ID as PROJECT_ID environmental variable.

**Contributed and maintained by [@ygerasimov](https://github.com/ygerasimov)**
