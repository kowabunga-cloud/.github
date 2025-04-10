## Welcome to the Kowabunga project ! 👋

<p align="center">
  <a href="https://www.kowabunga.cloud/?utm_source=github&utm_medium=logo" target="_blank">
    <picture>
      <source srcset="https://raw.githack.com/kowabunga-cloud/infographics/master/art/kowabunga-square-600x600-2.png" media="(prefers-color-scheme: dark)" />
      <source srcset="https://raw.githack.com/kowabunga-cloud/infographics/master/art/kowabunga-square-600x600-2.png" media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" />
      <img src="https://raw.githack.com/kowabunga-cloud/infographics/master/art/kowabunga-square-600x600-2.png" alt="Kowabunga" width="200">
    </picture>
  </a>
</p>

Kowabunga is an SD-WAN and HCI (Hyper-Converged Infrastructure) Orchestration Engine.

Market BS aside, Kowabunga provides DevOps with a complete infrastructure automation suite to orchestrate virtual resources management automation on privately-owned commodity hardware.

It brings the best of both worlds:

- Cloud API, automation, infrastructure-as-code, X-as-a-service ...
- On-Premises mastered and predictable flat-rate hardware.

## Why Kowabunga ?

- **Cost-Effective**: Full private-cloud on-premises readiness and ability to run on commodity hardware. No runtime fees, no egress charges, flat-rate predictable cost. **Keep control of your TCO.**
- **Resilient & Features-Rich**: Kowabunga enables highly-available designs, across multiple data centers and availability zones and brings automated software-as-a-service. **Shorten application development and setup times.**
- **No Vendor-Locking**: Harness the potential of Open-Source software stack as a backend: no third-party commercial dependency. We stand on the shoulders of giants: KVM, Ceph ... **Technical choices remain yours and yours only.**
- **Open Source … by nature**: Kowabunga itself is OpenSource, from API to client and server-side components. We have nothing to hide but everything to contribute. **We believe in mutual trust.**


**A Kowabunga-hosted project costs 1/10th of a Cloud-hosted one.**


## Technological Stack

The Kowabunga projects consists of multiple core components:

- **Kahuna**: the core orchestration system. Remotely controls every resource and maintains ecosystem consistent. Gateway to the Kowabunga REST API.
- **Kaktus**: the HCI node(s). Provides KVM-based virtual computing hypervisor with Ceph-based distributed storage services.
- **Kiwi**: the SD-WAN node(s). Provides various network services like routing, firewall, DHCP, DNS, VPN, peering (with active-passive failover).
- **Koala**: the WebUI. Allows for day-to-day supervision and operation of the various projects and services.

and plenty of ready-to-be-consumed -as-a-service features:

- **Kawaii**: Internet Gateway, with ingress/egress control, firewall and peering capabilities (VPC and IPSEC).
- **Kompute**: Virtual Computing and Block Storage.
- **Konvey**: Network Load-Balancer.
- **Kylo**: Distributed Network File-System (NFS).

## Fun Facts 🍿

Where does it comes from ? Everything comes as a solution to a given problem.

Our problem was (and still is ...) that Cloud services are unnecessarily expensive and often come with vendor-locking.
While Cloud services are appealing at first and great to bootstrap your project to an MVP level, you'll quickly hit profitability issues when scaling up.
Provided you have the right IT and DevOps skills in-house, self-managing your own infrastructure makes sense at economical level.

Linux and QEMU/KVM comes in handy, especially when powered by libvirt but we lacked true resource orchestration to push it to next stage.
OpenStack was too big, heavy, and costly to maintain. We needed something lighter, simpler.

So we came with **Kowabunga**: **K**vm **O**rchestrator **W**ith **A** **BUN**ch of **G**oods **A**dded.
