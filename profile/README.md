<!-- utm: github / hypersdk_org (in href only) -->

<p align="center">
  <a href="https://zyvor.dev?utm_source=github&utm_medium=hypersdk_org">
    <img src="https://zyvor.dev/img/zavor-logo.webp" alt="Zyvor AI Labs — HyperSDK Platform" width="260">
  </a>
</p>

<h3 align="center">HyperSDK Platform · Zeus suite</h3>
<p align="center"><sub>Post-VMware infrastructure · Enterprise VM migration · by Zyvor AI Labs</sub></p>

<p align="center">
  <a href="https://zyvor.dev/demo?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/▶_Watch_demo-F97316?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch demo"/></a>
  <a href="https://dashboard.zyvor.dev?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/Live_dashboard-8B5CF6?style=for-the-badge&logo=grafana&logoColor=white" alt="Dashboard"/></a>
  <a href="https://zyvor.dev/contact?intent=demo&utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/Book_engineering_call-22C55E?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book call"/></a>
  <a href="mailto:sales@zyvor.dev"><img src="https://img.shields.io/badge/sales@zyvor.dev-2563EB?style=for-the-badge&logo=gmail&logoColor=white" alt="Sales"/></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2800&pause=800&color=F97316&center=true&vCenter=true&width=940&lines=VMware+%E2%86%92+KVM+%E2%86%92+KubeVirt+%C2%B7+one+pipeline;96.8%25+first-boot+%C2%B7+10+cloud+providers;12+products+%C2%B7+2%2C000%2B+APIs+%C2%B7+400%2B+dashboard+views" alt="Animated tagline"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hypersdk&show_icons=true&theme=dark&hide_border=true&bg_color=00000000&title_color=F97316&icon_color=F97316&text_color=E4E4E7&ring_color=F97316&custom_title=Open%20source%20activity" alt="GitHub stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hypersdk&theme=dark&hide_border=true&background=00000000&ring=F97316&fire=F97316&currStreakLabel=F97316&sideLabels=E4E4E7&dates=71717A" alt="Streak"/>
</p>

---

## Migrate a VM in 60 seconds

```bash
# Production-style cutover — Community Edition preview
$ hyperctl export --provider vmware --vm prod-db-01 --target kvm
→ Discovered (4 vCPU · 32 GiB · 420 GB)     ✓
→ Streamed export with integrity checks       ✓
→ hyper2kvm: QCOW2 + VirtIO + bootloader      ✓
→ GuestKit: guest validated offline           ✓
→ First boot on KVM                           ✓  6.8s

# Fleet migrations, SLAs, air-gap, VMware exit programs → talk to Zyvor
```

<p align="center">
  <img src="https://zyvor.dev/screenshots/hypersdk-dashboard-hd.webp" alt="HyperSDK live dashboard" width="92%"/>
</p>

<p align="center">
  <b>See the real platform first</b> — migration video, live dashboard, optional 30‑min engineering session<br/>
  <a href="https://zyvor.dev/demo?utm_source=github&utm_medium=hypersdk_org"><b>Demo</b></a>
  ·
  <a href="https://dashboard.zyvor.dev?utm_source=github&utm_medium=hypersdk_org"><b>Dashboard</b></a>
  ·
  <a href="https://zyvor.dev/contact?utm_source=github&utm_medium=hypersdk_org"><b>Contact</b></a>
</p>

---

## What makes this different

<table>
<tr>
<td width="33%" align="center" valign="top">

### 🎯 One pipeline
Not 6 vendors. **Export → convert → fix → deploy → operate** in a single Zeus suite.

</td>
<td width="33%" align="center" valign="top">

### ⚡ 96.8% first boot
Automated **VirtIO**, bootloader repair, Windows & Linux — migrations that actually finish.

</td>
<td width="33%" align="center" valign="top">

### 🔒 Enterprise-ready
**SOC2-ready** · RBAC/SSO · audit logs · **air-gapped** · regulated industries.

</td>
</tr>
</table>

---

## Zeus suite · 12 products

```
   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
   │  HyperSDK   │───▶│  hyper2kvm  │───▶│  GuestKit   │───▶│   Aether    │
   │   Export    │    │   Convert   │    │   Inspect   │    │   Deploy    │
   └─────────────┘    └─────────────┘    └─────────────┘    └──────┬──────┘
                                                                     │
                    ┌─────────────┐    ┌─────────────┐    ┌─────────▼──────┐
                    │ PacketWolf  │◀───│     v9s     │◀───│  VMRogue · …   │
                    │   Observe   │    │   Manage    │    │  Machina · Forge│
                    └─────────────┘    └─────────────┘    └────────────────┘
```

<p align="center">
  <a href="https://zyvor.dev/hypersdk?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/HyperSDK-export-18181B?style=flat-square&logo=kubernetes&logoColor=F97316"/></a>
  <a href="https://zyvor.dev/hyper2kvm?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/hyper2kvm-convert-18181B?style=flat-square&logo=python&logoColor=F97316"/></a>
  <a href="https://zyvor.dev/guestkit?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/GuestKit-inspect-18181B?style=flat-square&logo=rust&logoColor=F97316"/></a>
  <a href="https://zyvor.dev/v9s?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/v9s-KubeVirt-18181B?style=flat-square&logo=kubernetes&logoColor=8B5CF6"/></a>
  <a href="https://zyvor.dev/packetwolf?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/PacketWolf-eBPF-18181B?style=flat-square&logo=linux&logoColor=8B5CF6"/></a>
  <a href="https://zyvor.dev/docs/products?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/+_7_more-products-F97316?style=flat-square"/></a>
</p>

---

## Built for every source · every target

<p align="center">
  <img src="https://img.shields.io/badge/VMware-vSphere-607078?style=for-the-badge&logo=vmware&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hyper--V-0078D4?style=for-the-badge&logo=windows&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenStack-ED1944?style=for-the-badge&logo=openstack&logoColor=white"/>
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white"/>
  <img src="https://img.shields.io/badge/KubeVirt-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
</p>

---

## Outcomes teams report

| Metric | Result |
|:-------|:-------|
| Fleet migration | **350 VMs** in **6 weeks** |
| Cost | **$1.2M** / yr saved · **$720K** cloud spend cut |
| Economics | **$100/VM/yr** vs **$1,200–5,000** VMware typical |
| Reliability | **96.8%** first-boot · near-zero cutover downtime |

> *"Every VM booted on the first try — zero downtime across 500 VMs."*  
> — Director of IT Operations, federal agency  
> [More case studies →](https://zyvor.dev/case-studies?utm_source=github&utm_medium=hypersdk_org)

<p align="center">
  <a href="https://zyvor.dev/vmware-exit?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/VMware_exit_program-F97316?style=for-the-badge"/></a>
  <a href="https://zyvor.dev/roi?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/ROI_calculator-22C55E?style=for-the-badge"/></a>
  <a href="https://zyvor.dev/pricing?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/Enterprise_pricing-2563EB?style=for-the-badge"/></a>
</p>

---

## ⚠️ You're on GitHub — that's Community Edition

| ✅ Fine for CE | 🏢 Contact Zyvor for |
|:---|:---|
| Labs, CI, single-VM experiments | VMware exit · **100+ VMs** · SLAs |
| Trying export / convert / guest tools | Air-gapped · compliance packs |
| Open-source contributors | Architecture review · cutover planning |

**CE repos:** [hypersdk](https://github.com/hypersdk/hypersdk) · [hyper2kvm](https://github.com/hypersdk/hyper2kvm) · [guestkit](https://github.com/hypersdk/guestkit)  
**Docs:** [Developer guide](https://github.com/hypersdk/hypersdk/blob/main/docs/DEVELOPER_GUIDE.md) · [CE vs Enterprise](https://github.com/hypersdk/hypersdk/blob/main/docs/ce-vs-enterprise.md)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,100:EA580C&height=120&section=footer&fontSize=28&fontColor=fff&animation=twinkling&text=Ready%20for%20production%3F" alt="Footer wave"/>
</p>

<p align="center">
  <a href="https://zyvor.dev/demo?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/▶_Watch_demo-F97316?style=for-the-badge" alt="Demo"/></a>
  <a href="https://zyvor.dev/contact?utm_source=github&utm_medium=hypersdk_org"><img src="https://img.shields.io/badge/Talk_to_sales-22C55E?style=for-the-badge" alt="Sales"/></a>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=hypersdk&label=Profile%20views&color=F97316&style=flat" alt="views"/>
</p>
