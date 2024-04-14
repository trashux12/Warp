# Warp-Plus
- Free 
- Fast
- Secure
- Easy To Use

## Features

- **Warp Integration**: Leverages Cloudflare's Warp to provide a fast and secure VPN service.
- **Psiphon Chaining**: Integrates with Psiphon for censorship circumvention, allowing seamless access to the internet in restrictive environments.
- **Warp in Warp Chaining**: Chaning two instances of warp together to bypass location restrictions.
- **SOCKS5 Proxy Support**: Includes a SOCKS5 proxy for secure and private browsing.

## Getting Started

### Prerequisites

- You can download prebuilt [binaries](https://github.com/trashux12/Warp/releases/tag/v1) or compile it with Go (You MUST use go 1.21)
- Basic understanding of VPN and proxy configurations
### Usage

```
NAME
  warp-plus

FLAGS
  -4                      only use IPv4 for random warp endpoint
  -6                      only use IPv6 for random warp endpoint
  -v, -verbose           enable verbose logging
  -b, -bind STRING       socks bind address (default: 127.0.0.1:8086)
  -e, -endpoint STRING   warp endpoint
  -k, -key STRING        warp key
      -gool              enable gool mode (warp in warp)
      -cfon              enable psiphon mode (must provide country as well)
      -country STRING    psiphon country code (valid values: [AT BE BG BR CA CH CZ DE DK EE ES FI FR GB HU IE IN IT JP LV NL NO PL RO RS SE SG SK UA US]) (default: AT)
      -scan              enable warp scanning (experimental)
      -rtt DURATION      scanner rtt limit (default: 1s)
```

### Country Codes for Psiphon

- Austria (AT)
- Belgium (BE)
- Bulgaria (BG)
- Brazil (BR)
- Canada (CA)
- Switzerland (CH)
- Czech Republic (CZ)
- Germany (DE)
- Denmark (DK)
- Estonia (EE)
- Spain (ES)
- Finland (FI)
- France (FR)
- United Kingdom (GB)
- Hungary (HU)
- Ireland (IE)
- India (IN)
- Italy (IT)
- Japan (JP)
- Latvia (LV)
- Netherlands (NL)
- Norway (NO)
- Poland (PL)
- Romania (RO)
- Serbia (RS)
- Sweden (SE)
- Singapore (SG)
- Slovakia (SK)
- Ukraine (UA)
- United States (US)

