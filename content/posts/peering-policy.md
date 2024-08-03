---
title: "Peering Policy"
date: 2023-08-15T15:41:10+02:00
draft: false
weight: 2
---

Peering with us is a good way to reduce latency and bandwidth as you're directly connected to us and don’t need to rely on your upstream provider. If you decide to peer with **AS197434** you have to follow some basic rules, but don't worry, they aren't hard (only a security measure) 😉

### Requirements and Rules
+ In the possession of a RIPE assigned ASN and IPv6 prefix
+ Have a valid and up to date [PeeringDB profile](https://www.peeringdb.com/)
+ Don't **under any circumstances** point static or default routes towards us
+ A valid RPKI would be useful for validation

### Connections and Profile

| ASN      | | Exchange          | | Address                                       |
|----------|-|-------------------|-|-----------------------------------------------|
| AS47498  | | FogIXP            | | 2001:7f8:ca:1:0:19:7434:1                     |
| AS36090  | | F4IX MCI          | | 2602:fa3d:f4:1::ad                            |
| AS211272 | | AXCIX Duesseldorf | | 2a0e:8f02:2260::34                            |
| AS202409 | | LocIX Frankfurt   | | 2001:7f8:f2:e1:a5:19:7434:1</br>185.1.166.48  |
| AS202409 | | LocIX Duesseldorf | | 2a0c:b641:701:0:a5:19:7434:1</br>185.1.155.37 |


+ Our [PeeringDB Profile](https://www.peeringdb.com/net/33774)

Do not hesitate to [contact us](mailto:peering@as197434.net), we will answer in 1-3 business days!