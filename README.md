# phpbrewvm

## Introduction

PHPBrewVM helps manage different versions installed on MacOS via homebrew.

This tool was borne out of a necessity to manage multiple versions for developers who would typically use Docker for serving
the application, but due to performance issues had a problem running `composer install` within the container with a bind mount.

## Prerequesites

* Homebrew
* jq

## Usage

### List

```bash
phpbrewvm list
```

### Install

```bash
phpbrewvm install 7.4
```

### Use

```bash
phpbrewvm use 7.4
```


