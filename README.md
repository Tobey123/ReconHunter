## Recon Hunter


![alt text](https://raw.githubusercontent.com/hassan0x/ReconHunter/main/Image.png)

A tool to map the attack surface discovery of any target.

## Tool Architecture

## Tool Features

- Sub-Domains Passive Scraping
- Sub-Domains Brute Force
- Sub-Domains Wildcard Removal
- Sub-Domains Spidering
- Sub-Domains Takeover
- IPs Enumeration using Censys
- Port Scanning
- Websites' Screenshots
- Directories & Files Brute Force
- Internet Archive
- AWS S3 Buckets
- Github Leaked Secrets

## Tool Prerequisities

You need to insert the AWS key also the Censys Key to use all the tool features.

### AWS Key
```
aws configure
```

### Censys Key
```
censys config
```

## Tool Usage

```
# Installation
git clone https://github.com/hassan0x/ReconHunter
cd ReconHunter
./ReconHunter 0

# Help
./ReconHunter

# Run All the Commands
./ReconHunter 1 $domain_name $github_user
./ReconHunter 1 example.com user1
```

## Tool Demo

The tool has been tried and validated on kali linux.

### Installation


### Usage


### Result


## Tools Used

- Amass
- SubFinder
- MassDNS
- GoSpider
- HTTProbe
- SubOver
- Censys
- Masscan
- Nmap
- Aquatone
- DirSearch
- WayBackUrls
- Unfurl
- S3Scanner
- AWScli
- TruffleHog
