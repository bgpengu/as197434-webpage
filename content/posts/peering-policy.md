---
title: "Peering Policy"
date: 2023-08-15T15:41:10+02:00
draft: false
weight: 2
---

So you decided to peer with **AS197434**? We want to do the process as seamless as possible, but in order to do achieve this you have to follow some basic rules. Don't worry, they aren't that hard (only a security measure) 😉 *Pssst: It also increases the peer count...*


### Requirements / Rules
+ In the possession of a RIPE assigned ASN and IPv6 prefix
+ Have a valid and up to date [PeeringDB profile](https://www.peeringdb.com/)
+ Don't **under any circumstances** point static or default routes towards us
+ RPKI for validation would be useful, but RIR is **required**
+ A valid RPKI would be useful for validation, valid RIR Entries are **required**

### Connections / Profile

| ASN | | Exchange | | Address |
|-----|-|----------|-|---------|
| AS47498 | | <a href="https://fogixp.org/">FogIXP</a> | | 2001:7f8:ca:1:0:19:7434:1 |
| AS36090 | | <a href="https://f4ix.com/">F4IX MCI</a> | | 2602:fa3d:f4:1::ad |
| AS211272 | | <a href="https://arexico.com/exchange/">AXCIX Duesseldorf</a> | | 2a0e:8f02:2260::34 |
| AS202409 | | <a href="https://locix.online/frankfurt.html">LocIX Frankfurt</a>   | | 2001:7f8:f2:e1:a5:19:7434:1</br>185.1.166.48 |
| AS202409 | | <a href="https://locix.online/duesseldorf.html">LocIX Duesseldorf</a> | | 2a0c:b641:701:0:a5:19:7434:1</br>185.1.155.37 |


+ Our [PeeringDB Profile](https://www.peeringdb.com/net/33774)
+ Our [BGP.Tools Profile](https://bgp.tools/as/197434)

Do not hesitate to [contact us](mailto:peering@as197434.net), we're trying to answer in 1-3 business days!