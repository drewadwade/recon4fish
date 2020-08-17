# recon4fish
a web recon script for the fish shell   
based on @hmaverickadams web recon script   
with additions from @Gr1mmie's sumrecon script of the same lineage  

The script runs:
- assetfinder and amass to gather subdomains
- httprobe to reduce subsequent scans to live sites only
- subjack to check for possible subdomain takeover
- nmap to scan for open ports
- waybackurls to find data on the Wayback Machine   
- gowitness to screenshot sites

It also checks for:
- parameters in the wayback data
- js, html, jsp, json, php, and aspx files in the wayback data

The script creates output in a Targets folder in the user's home directory and requires that the following are installed:
- amass
- assetfinder
- gowitness
- httprobe
- subjack
- waybackurls
- google-chrome
