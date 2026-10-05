# COMP3104 - Developer Operations

[![Build Status](https://app.travis-ci.com/JoshuaZaakir/COMP3104.svg?branch=main)](https://app.travis-ci.com/JoshuaZaakir/COMP3104)
[![COMP3104 CI](https://github.com/JoshuaZaakir/COMP3104/actions/workflows/ci.yml/badge.svg)](https://github.com/JoshuaZaakir/COMP3104/actions/workflows/ci.yml)

This repository contains my work for Lab 04. The project uses Travis CI and
GitHub Actions to run the same verification whenever code is pushed or a pull
request is opened.

## Running the check locally

```bash
npm install
npm test
```

The current test script prints the placeholder message required by the lab.
Successful builds from the `main` branch deploy the contents of the `build`
folder to GitHub Pages.
