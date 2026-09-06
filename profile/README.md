<!-- utm: github / zyvorai_org (in href only) -->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zyvorai/.github/main/profile/assets/github-banner.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zyvorai/.github/main/profile/assets/github-banner-light.svg">
    <img src="https://raw.githubusercontent.com/zyvorai/.github/main/profile/assets/github-banner.svg" alt="Zyvor — open infrastructure for migration, Kubernetes, and the edge" width="100%">
  </picture>
</p>

<h3 align="center">Enterprise infrastructure for the post-legacy estate</h3>
<p align="center">
  Migrate off proprietary hypervisors &amp; HCI platforms, run on Kubernetes &amp; KubeVirt, operate a private cloud with <b>Axiom</b> —
  one API contract across every layer.<br/>
  <sub><a href="https://zyvor.dev?utm_source=github&utm_medium=zyvorai_org">Zyvor</a> · zyvor.dev</sub>
</p>

<p align="center">
  <a href="https://zyvor.dev/demo?utm_source=github&utm_medium=zyvorai_org"><img src="https://img.shields.io/badge/▶_Watch_demo-cc420a?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch demo"/></a>
  <a href="https://zyvor.dev/axiom?utm_source=github&utm_medium=zyvorai_org"><img src="https://img.shields.io/badge/Axiom-private_cloud-1f2937?style=for-the-badge" alt="Axiom"/></a>
  <a href="https://zyvor.dev/contact?intent=demo&utm_source=github&utm_medium=zyvorai_org"><img src="https://img.shields.io/badge/Book_engineering_call-16a34a?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book call"/></a>
  <a href="mailto:sales@zyvor.dev"><img src="https://img.shields.io/badge/sales%40zyvor.dev-2563eb?style=for-the-badge&logo=gmail&logoColor=white" alt="Sales"/></a>
</p>

<p align="center">
  <a href="https://github.com/zyvorai/guestkit/stargazers"><img src="https://img.shields.io/github/stars/zyvorai/guestkit?style=flat-square&logo=github&label=guestkit&labelColor=18181B&color=cc420a" alt="guestkit"/></a>
  <a href="https://github.com/zyvorai/fabric/stargazers"><img src="https://img.shields.io/github/stars/zyvorai/fabric?style=flat-square&logo=github&label=fabric&labelColor=18181B&color=cc420a" alt="fabric"/></a>
  <a href="https://github.com/zyvorai/kryton/stargazers"><img src="https://img.shields.io/github/stars/zyvorai/kryton?style=flat-square&logo=github&label=kryton&labelColor=18181B&color=cc420a" alt="kryton"/></a>
  <img src="https://img.shields.io/badge/Apache--2.0-community-18181B?style=flat-square&labelColor=18181B" alt="Apache-2.0"/>
</p>

---

## Try it in 60 seconds

```bash
# Community Edition preview — export, convert, and validate a VM offline
$ transivactl export --provider enterprise-hypervisor --vm prod-db-01 --target kvm
→ Discovered (4 vCPU · 32 GiB · 420 GB)       ✓
→ Streamed export with integrity checks       ✓
→ h2kvm: QCOW2 + VirtIO + bootloader          ✓
→ GuestKit: guest validated offline           ✓
→ First boot on KVM                           ✓  6.8s

# Fleet migrations, SLAs, air-gapped rollouts → talk to Zyvor
```

<p align="center">
  <b>See the real platform first</b> — migration video, Axiom private cloud, an optional 30-minute engineering session<br/>
  <a href="https://zyvor.dev/demo?utm_source=github&utm_medium=zyvorai_org"><b>Demo</b></a>
  ·
  <a href="https://zyvor.dev/axiom?utm_source=github&utm_medium=zyvorai_org"><b>Axiom</b></a>
  ·
  <a href="https://zyvor.dev/contact?utm_source=github&utm_medium=zyvorai_org"><b>Contact</b></a>
</p>

---

## What makes this different

<table>
<tr>
<td width="33%" align="center" valign="top">

### One pipeline
Not a stack of point tools. **Export → convert → fix → deploy → operate**, one suite, one API contract.

</td>
<td width="33%" align="center" valign="top">

### Private cloud on k8s
**Axiom** is the day-2 console (k3s → production). **Ragnarok** attests confidential / disposable VMs.

</td>
<td width="33%" align="center" valign="top">

### Enterprise-ready
RBAC/SSO, audit logs, **air-gapped** deployment — built for regulated industries from day one.

</td>
</tr>
</table>

---

## The suite, by what it does to your estate

| Category | What it covers | Explore |
|:---|:---|:---|
| **Migrate** | Discover, simulate, convert, and assure workloads off proprietary hypervisors, HCI, and public cloud | [Transiva](https://zyvor.dev/transiva?utm_source=github&utm_medium=zyvorai_org) · [Scout](https://zyvor.dev/scout?utm_source=github&utm_medium=zyvorai_org) · [Chimera](https://zyvor.dev/chimera?utm_source=github&utm_medium=zyvorai_org) · [h2kvm](https://zyvor.dev/h2kvm?utm_source=github&utm_medium=zyvorai_org) · [GuestKit](https://zyvor.dev/guestkit?utm_source=github&utm_medium=zyvorai_org) |
| **Run** | Operate VMs and apps on Kubernetes, KubeVirt, and libvirt from one control plane | [Zeus OS](https://zyvor.dev/zeus-os?utm_source=github&utm_medium=zyvorai_org) · [Veyron](https://zyvor.dev/veyron?utm_source=github&utm_medium=zyvorai_org) · [Kryton](https://zyvor.dev/kryton?utm_source=github&utm_medium=zyvorai_org) · [Iris](https://zyvor.dev/iris?utm_source=github&utm_medium=zyvorai_org) · [Haven](https://zyvor.dev/haven?utm_source=github&utm_medium=zyvorai_org) · [Fabric](https://zyvor.dev/zyvor-fabric?utm_source=github&utm_medium=zyvorai_org) · [FluxVM](https://zyvor.dev/fluxvm?utm_source=github&utm_medium=zyvorai_org) |
| **Operate** | Private cloud day-2, storage intent, packets, GPUs, bare metal, reliability | [Axiom](https://zyvor.dev/axiom?utm_source=github&utm_medium=zyvorai_org) · [Ragnarok](https://zyvor.dev/ragnarok?utm_source=github&utm_medium=zyvorai_org) · [PacketWolf](https://zyvor.dev/packetwolf?utm_source=github&utm_medium=zyvorai_org) · [Forge](https://zyvor.dev/forge?utm_source=github&utm_medium=zyvorai_org) |
| **Scale** | Stand up clusters and sign regulated documents | [HyperCluster](https://zyvor.dev/hypercluster?utm_source=github&utm_medium=zyvorai_org) · [ZySign](https://zyvor.dev/zysign?utm_source=github&utm_medium=zyvorai_org) |
| **Community Edition** | Apache-2.0 tools maintained in the open — migration, compute, identity, edge, preflight | ↓ see below |

<p align="center"><a href="https://zyvor.dev/products?utm_source=github&utm_medium=zyvorai_org">Full product catalogue →</a> · <a href="https://zyvor.dev/compare?utm_source=github&utm_medium=zyvorai_org">Compare all products →</a></p>

---

## Open source vs Enterprise

Everything below is real, working, Apache-2.0 source — not a crippled trial. Enterprise is support, scale programs, and hardened deployments on top of it, not features withheld from the repo.

| | Open source (these repos) | Enterprise ([zyvor.dev](https://zyvor.dev?utm_source=github&utm_medium=zyvorai_org)) |
|:---|:---|:---|
| **Good for** | Labs, CI gates, single-VM / small-fleet migrations, contributing | Hypervisor exit programs, 100+ VM fleets, regulated / air-gapped rollouts |
| **Support** | GitHub Issues &amp; Discussions | SLA, [sales@zyvor.dev](mailto:sales@zyvor.dev), migration workshops, professional services |
| **What you get** | Full CLI/TUI tooling, self-hosted consoles, Helm charts — the same codebase Enterprise runs | Same codebase + priority fixes, guided playbooks, hardened reference architectures, fleet automation |

**Open source repos:**
[guestkit](https://github.com/zyvorai/guestkit) ·
[h2kvm](https://github.com/zyvorai/h2kvm) ·
[fluxvm](https://github.com/zyvorai/fluxvm) ·
[fabric](https://github.com/zyvorai/fabric) ·
[kryton](https://github.com/zyvorai/kryton) ·
[haven](https://github.com/zyvorai/haven) ·
[scout](https://github.com/zyvorai/scout) ·
[chimera](https://github.com/zyvorai/chimera) ·
[nodra](https://github.com/zyvorai/nodra) ·
[kairo](https://github.com/zyvorai/kairo) ·
[kubeflight](https://github.com/zyvorai/kubeflight) ·
[iris](https://github.com/zyvorai/iris) ·
[janus](https://github.com/zyvorai/janus) ·
[argus](https://github.com/zyvorai/argus) ·
[netevd](https://github.com/zyvorai/netevd) ·
[netctl](https://github.com/zyvorai/netctl) ·
[cloud-netconfig](https://github.com/zyvorai/cloud-netconfig) ·
[relay-pubsub](https://github.com/zyvorai/relay-pubsub) ·
[relay-edge](https://github.com/zyvorai/relay-edge)

**Get started:** [Demo](https://zyvor.dev/demo?utm_source=github&utm_medium=zyvorai_org) → [Axiom](https://zyvor.dev/axiom?utm_source=github&utm_medium=zyvorai_org) → [Pricing](https://zyvor.dev/pricing?utm_source=github&utm_medium=zyvorai_org) → [Talk to us](https://zyvor.dev/contact?utm_source=github&utm_medium=zyvorai_org)

**Learn more:** [zyvor.dev/docs](https://zyvor.dev/docs?utm_source=github&utm_medium=zyvorai_org) · [zyvor.dev/blog](https://zyvor.dev/blog?utm_source=github&utm_medium=zyvorai_org) · [Narrative repo](https://github.com/zyvorai/zyvorai)

Maintainers: [GitHub org settings](../GITHUB_ORG_SETTINGS.md) · [Lead tracking](../LEADS.md)

---

<p align="center">
  <b>Ready for production?</b><br/><br/>
  <a href="https://zyvor.dev/demo?utm_source=github&utm_medium=zyvorai_org"><img src="https://img.shields.io/badge/▶_Watch_demo-cc420a?style=for-the-badge" alt="Demo"/></a>
  <a href="https://zyvor.dev/contact?utm_source=github&utm_medium=zyvorai_org"><img src="https://img.shields.io/badge/Talk_to_sales-16a34a?style=for-the-badge" alt="Sales"/></a>
</p>
