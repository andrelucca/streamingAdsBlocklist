
# Streaming Ads Blocklist for pi-hole

This repository contains a simple list of domains used by Streaming services like Disney+, Netflix, etc to fetch ads when you are in the basic payd plan

To add this list to your pi-hole
* Go to pi-hole admin panel
* Under Group Management go to Lists
* Ad this URL as a new subscried list https://raw.githubusercontent.com/andrelucca/streamingAdsBlocklist/refs/heads/main/hosts.txt
* Go to System panel then Tools
* Update Gravity, this will reload all your block lists adding the URLs from this one to your pi-hole

**This domains/URLs are being discovered from a pi-hole instance and are added here every time a new one appears**