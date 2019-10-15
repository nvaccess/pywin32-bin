# [DEPRECATED] pywin32-bin
 NVDA's pywin32-bin dependency 

During the Python 3 migration of [NVDA](github.com/nvaccess/nvda) this repository was going to hold the pywin32 dependency. However, in [pull request nvaccss/nvda#9639](https://github.com/nvaccess/nvda/pull/9639) the decision was made to remove NVDA's dependency. Despite this requireing many add-ons to find another work around, this decision was made since compatibility for add-ons was already being broken, and removing this dependecy simplifies NVDA.

This repository will be archived.

## Guidance for add-on authors

Add-ons will need to package any aspects of pywin32 they require. Add-on authors may wish to refer to [pull request nvaccess/pywin32-bin#1](https://github.com/nvaccess/pywin32-bin/pull/1). 
