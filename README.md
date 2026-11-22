<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=560&lines=ph4ntom;reverse+engineer+%26+kernel+dev;binary+analysis+%26+threat+intel" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Linux_Kernel-rtw89_Contributor-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/IDA_Pro_9.5-Hex--Rays_%26_Microcode-blueviolet?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTEyIDJMMyA3djEwbDkgNSA5LTVWN3oiLz48L3N2Zz4="/>
  <img src="https://img.shields.io/badge/Reverse_Engineering-Ring--0_%2F_ARM64-black?style=for-the-badge&logo=hackthebox&logoColor=9FEF00"/>
  <img src="https://img.shields.io/badge/Threat_Intel-abuse.ch_Contributor-critical?style=for-the-badge&logo=shield&logoColor=white"/>
</p>

<p align="center">
  🌐 <a href="https://ph4ntom-rev.uz/"><strong>ph4ntom-rev.uz</strong></a> &nbsp;·&nbsp;
  🐧 <a href="https://github.com/pkshih/rtw/commits/rtw-next/?author=ph4ntom-rev"><strong>Linux Kernel Commits (<code>rtw89</code>)</strong></a> &nbsp;·&nbsp;
  🧬 <a href="https://bazaar.abuse.ch/user/49805/"><strong>MalwareBazaar</strong></a> &nbsp;·&nbsp;
  🦊 <a href="https://threatfox.abuse.ch/user/53753/"><strong>ThreatFox</strong></a>
</p>

---

### 🔬 About

```text
> whoami
ph4ntom — reverse engineer & low-level systems developer focused on
binary dissection (x86_64 / ARM64 / DEX), Linux kernel wireless internals,
and autonomous static malware analysis infrastructure.

> cat /etc/motd
"The binary never lies. The decompiler sometimes does."
```

### ⚡ Upstream & Active Projects

| Project | Scope & Technical Highlights | Status |
|:--------|:-----------------------------|:------:|
| **[Linux Kernel — `wifi: rtw89`](https://github.com/pkshih/rtw/commits/rtw-next/?author=ph4ntom-rev)** | `5` upstream kernel driver patches merged into Realtek `rtw-next` (`0202cb50fe9f`..`92608bb5f14f`, `Cc: stable@vger.kernel.org`) — fixes `NULL vif` kernel dereference in `rtw89_ops_tx()`, negative `radiotap` rate index bug, non-`chanctx` channel restoration, control-frame `seq_ctrl` reads, and `ASSIGN_SEQ` / `NO_ACK` / retry handling on raw 802.11 injection | ✅ **[Merged (`rtw-next`)](https://lore.kernel.org/linux-wireless/63269466-8c67-461e-a29b-f64bb0d47f6a@RTKEXHMBS05.realtek.com.tw/)** |
| **[ph4ntom IDA Bridge](https://github.com/ph4ntom-rev/ph4ntom-ida-bridge)** | Autonomous MCP & REST control plane for IDA Pro 9.0–9.5 (`Hex-Rays CTree` & `Microcode IR`, live debugger, ARM/x64 struct & vtable reconstruction) — **`131` MCP tools, `143` REST endpoints** | 🚀 **[v6.4.0](https://github.com/ph4ntom-rev/ph4ntom-ida-bridge/releases/tag/v6.4.0)** |
| **[ph4ntom Vitrum](https://github.com/ph4ntom-rev/ph4ntom-vitrum)** | Autonomous *in-vitro* static malware dissection core (`v0.2.0`), Global CTI & Dropper Hunter (`v2.7`, `28` threat clusters), and Zero-Touch Anti-Canary `TON`/`DoH` Dead-Drop Interceptor (`v2.1`) (`TLP:AMBER`) | 🛡️ **[v0.2.0 / Rules v2.7](https://github.com/ph4ntom-rev/ph4ntom-vitrum)** |
| **[Public Threat Intelligence (`abuse.ch`)](https://bazaar.abuse.ch/user/49805/)** | **`17` first-seen FUD multi-stage Android trojan APKs** ([MalwareBazaar](https://bazaar.abuse.ch/user/49805/)) and **`84` verified C2 / `DoH` / `XTLS-REALITY` indicators** ([ThreatFox](https://threatfox.abuse.ch/user/53753/), `100% high confidence`, `560` credits) | 🎯 **[Verified Feed](https://threatfox.abuse.ch/user/53753/)** |
| **[rtw89 Monitor Injection](https://github.com/ph4ntom-rev/rtw89-monitor-injection)** | Standalone backport & reference patchset for Realtek `rtw89` 802.11ax/be monitor mode and raw packet injection | 📦 **[v1.0.0](https://github.com/ph4ntom-rev/rtw89-monitor-injection)** |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ph4ntom-rev&style=for-the-badge&color=00ff41&label=PROFILE+VIEWS"/>
</p>
