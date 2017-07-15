# Experimental config overrides for Sitecore

## Warnings
1. This repository contains experimental config overrides.
No guarantees that it works with your Sitecore instance.

2. The 'Dev' configuration file is not intended for **any** production Sitecore installation.
This include file contains some experimental optimizations that can speed up start-up.

Please, review each of the patched elements and consider if some of the optimizations should be commented out due to the specifics of your solution.
Enabling this file without taking into account the specifics of your solution can have unexpected consequences.

Please use with caution.

## Repo structure
There is a subfolder for each role (CD or dev, for example).
You can find an auto include config there.
