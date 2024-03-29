## Public DNS

### Cloudflare + APNIC [WIP]

`1.1.1.1` is a partnership between Cloudflare and APNIC. Cloudflare runs one of the world’s largest, fastest networks. APNIC is a non-profit organization managing IP address allocation for the Asia Pacific and Oceania regions.

Cloudflare had the network. APNIC had the IP address (1.1.1.1). Both of us were motivated by a mission to help build a better Internet. You can read more about each organization’s motivations on our respective posts: [Cloudflare Blog](https://blog.cloudflare.com/announcing-1111/) / [APNIC Blog](https://labs.apnic.net/?p=1127). For more information see: What is [1.1.1.1](https://cloudflare.com/learning/dns/what-is-1.1.1.1/)?

| FQDN                     | IPv4    | IPv6                 |
|-------------------------:|:--------|:---------------------|
| ns1.cloudflare.ozal.zone | 1.1.1.1 | 2606:4700:4700::1111 |
| ns2.cloudflare.ozal.zone | 1.0.0.1 | 2606:4700:4700::1001 |


### Google Public DNS [WIP]

A free, global DNS resolution service that you can use as an alternative to your current DNS provider.

| FQDN                 | IPv4    | IPv6                 |
|---------------------:|:--------|:---------------------|
| ns1.google.ozal.zone | 8.8.8.8 | 2001:4860:4860::8888 |
| ns2.google.ozal.zone | 8.8.4.4 | 2001:4860:4860::8844 |

### OpenDNS (Cisco) [WIP]

OpenDNS is the name of a Domain Name System (DNS) service as well as of the company that provides that service. The OpenDNS service extends the DNS by incorporating features such as content filtering and phishing protection. It is also touted as faster, more reliable and having zero downtime because of its global network of DNS servers that ensures that, if one or two servers are down, the others can still carry the slack.

| FQDN                  | IPv4           | IPv6            |
|----------------------:|:---------------|:----------------|
| ns1.opendns.ozal.zone | 208.67.222.222 | 2620:119:35::35 |
| ns2.opendns.ozal.zone | 208.67.220.220 | 2620:119:53::53 |

### Verisign Public DNS [WIP]

Verisign Public DNS is a free DNS service that offers improved DNS stability and security over other alternatives. And, unlike many of the other DNS services out there, Verisign respects your privacy. We will not sell your public DNS data to third parties nor redirect your queries to serve you any ads.

| FQDN                   | IPv4      | IPv6            |
|-----------------------:|:----------|:----------------|
| ns1.verisign.ozal.zone | 64.6.64.6 | 2620:74:1b::1:1 |
| ns2.verisign.ozal.zone | 64.6.65.6 | 2620:74:1c::2:2 |

## Authoritative DNS

### NS Group A [WIP]

| FQDN            | IPv4           | IPv6                  |
|----------------:|:---------------|:----------------------|
| ns1.a.ozal.zone | 216.239.32.106 | 2001:4860:4802:32::6a |
| ns2.a.ozal.zone | 216.239.34.106 | 2001:4860:4802:34::6a |
| ns3.a.ozal.zone | 216.239.36.106 | 2001:4860:4802:36::6a |
| ns4.a.ozal.zone | 216.239.38.106 | 2001:4860:4802:38::6a |

### NS Group B [WIP]

| FQDN            | IPv4           | IPv6                  |
|----------------:|:---------------|:----------------------|
| ns1.b.ozal.zone | 216.239.32.107 | 2001:4860:4802:32::6b |
| ns2.b.ozal.zone | 216.239.34.107 | 2001:4860:4802:34::6b |
| ns3.b.ozal.zone | 216.239.36.107 | 2001:4860:4802:36::6b |
| ns4.b.ozal.zone | 216.239.38.107 | 2001:4860:4802:38::6b |

### NS Group C [WIP]

| FQDN            | IPv4           | IPv6                  |
|----------------:|:---------------|:----------------------|
| ns1.c.ozal.zone | 216.239.32.108 | 2001:4860:4802:32::6c |
| ns2.c.ozal.zone | 216.239.34.108 | 2001:4860:4802:34::6c |
| ns3.c.ozal.zone | 216.239.36.108 | 2001:4860:4802:36::6c |
| ns4.c.ozal.zone | 216.239.38.108 | 2001:4860:4802:38::6c |

### NS Group D

| FQDN            | IPv4           | IPv6                  |
|----------------:|:---------------|:----------------------|
| ns1.d.ozal.zone | 216.239.32.109 | 2001:4860:4802:32::6d |
| ns2.d.ozal.zone | 216.239.34.109 | 2001:4860:4802:34::6d |
| ns3.d.ozal.zone | 216.239.36.109 | 2001:4860:4802:36::6d |
| ns4.d.ozal.zone | 216.239.38.109 | 2001:4860:4802:38::6d |

### NS Group E

| FQDN            | IPv4           | IPv6                  |
|----------------:|:---------------|:----------------------|
| ns1.e.ozal.zone | 216.239.32.110 | 2001:4860:4802:32::6e |
| ns2.e.ozal.zone | 216.239.34.110 | 2001:4860:4802:34::6e |
| ns3.e.ozal.zone | 216.239.36.110 | 2001:4860:4802:36::6e |
| ns4.e.ozal.zone | 216.239.38.110 | 2001:4860:4802:38::6e |

### NS Group F [WIP]

| FQDN            | IPv4           | IPv6                  |
|----------------:|:---------------|:----------------------|
| ns1.f.ozal.zone | 216.239.32.100 | 2001:4860:4802:32::6f |
| ns2.f.ozal.zone | 216.239.34.100 | 2001:4860:4802:34::6f |
| ns3.f.ozal.zone | 216.239.36.100 | 2001:4860:4802:36::6f |
| ns4.f.ozal.zone | 216.239.38.100 | 2001:4860:4802:38::6f |
