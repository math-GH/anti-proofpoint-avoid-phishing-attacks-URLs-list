# Proofpoint Security Awareness Training URLs List

A curated list of known URLs associated with **Proofpoint Security Awareness Training** landing pages.

## Overview

This repository maintains a reference list of URLs used in Proofpoint security awareness and phishing simulation campaigns. These pages are typically part of employee training programs designed to help users recognize and report phishing attempts.

Many of these landing pages contain text similar to the following:

> Hi! This web site belongs to Proofpoint Security Awareness Training. This domain is used to teach employees how to recognize and avoid phishing attacks. This page is here to let you know that this is not a malicious web page. The email that led you here was likely sent by your employer as part of a training program.

## Why this repository exists

Organizations often run simulated phishing campaigns as part of their security awareness programs. Keeping track of known training URLs can be useful for:

- documentation and internal review
- awareness and analysis
- identifying patterns in training infrastructure
- maintaining a public reference for known Proofpoint training domains and pages

## Scope

This repository focuses specifically on URLs associated with Proofpoint Security Awareness Training pages.

It may include:

- landing page URLs
- related domains and subdomains
- known patterns relevant to training simulations

## adding the list into uBlock Origin
`uBlock Origin` is an extension for the Firefox browser.

How to add this list to keep the newest URLs list:
(see https://github.com/gorhill/uBlock/wiki/Filter-lists-from-around-the-web )

- Go to the extensions list in Firefox (`about:addons`)
- click on the 3 dots menu at the end of the `uBlock Origin`
- chose: settings
- go to the `filter lists` tab
- scroll down till the end to 'import'
- add `https://raw.githubusercontent.com/math-GH/anti-proofpoint-avoid-phishing-attacks-URLs-list/refs/heads/main/list` there
- save the settings
- the list should be listed now above the `import` field (`own filter lists`)

This list should be updated regularly automatically by the extension itself.

## Contributing

Contributions are welcome and appreciated.

If you want to contribute, please open a pull request with:

- the URL or domain
- any supporting context
- confirmation, where possible, that it is associated with Proofpoint Security Awareness Training

Please keep submissions accurate, minimal, and well-scoped.

## Disclaimer

This repository is provided for **documentation, research, and security awareness purposes only**.

It is **not** intended to bypass, interfere with, or weaken organizational security awareness programs, phishing simulations, or email security controls.

## License

MIT license. See `LICENSE`
