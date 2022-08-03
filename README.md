# Security Toolbox

This toolbox includes several updated tools for red team assessments and penetration testing running exclusively on docker

*Tools*

- hakrawler
- waybackurls
- gau
- anew
- Assetfinder
- Amass
- pspy
- DNS Recon
- Findomain
- httpx
- dnsx
- subfinder
## Usage

```
cat 1.txt  | docker run -i toolbox hakrawler -subs
```

## Installation

```
docker build . -t toolbox:latest
```

# TODO

- List of alias on zsh and shell
- Add auto push to docker hub on schedule using github actions
- Add more tools
- Order list alphabetically
