<div align="center">

# ddev-xhgui-pro - use XHGui with DDEV 

![GitHub release (with filter)](https://img.shields.io/github/v/release/oblakstudio/ddev-xhgui-pro)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

</div>

This repository provides the XHGui service to [DDEV](https://ddev.readthedocs.io).  
**Batteries included!** - automagically configures itself based on your project settings..

## Installation

For DDEV v1.23.5 or above run

```bash
ddev add-on get oblakdev/ddev-xhgui-pro
```

For earlier versions of DDEV run

```bash
ddev get oblakdev/ddev-xhgui-pro
```

Then restart your project

```bash
ddev restart
```

## Configuration

There isn't one. Addon does everything for you.  
It automatically enables itself when you turn on xhprof in your project, and disables itself when you turn it off.

## Usage

```bash
ddev xhprof on
```

Visit `https://your-project.ddev.site/xhgui` to see the XHGui dashboard.

___

**Based on the original [ddev-contrib recipe](https://github.com/ddev/ddev-contrib/tree/master/docker-compose-services/mongodb)**  
**Developed and maintained by [Oblak Studio](https://github.com/oblakstudio)**
