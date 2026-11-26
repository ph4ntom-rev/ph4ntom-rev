<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=620&lines=ph4ntom;linux+kernel+%26+native+reverse+engineering;android+malware+dissection+%26+threat+intel" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://github.com/pkshih/rtw/commits/rtw-next/?author=ph4ntom-rev"><img src="https://img.shields.io/badge/Linux_Kernel-wifi:_rtw89-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux Kernel"/></a>
  <a href="https://github.com/ph4ntom-rev/ph4ntom-ida-bridge"><img src="https://img.shields.io/badge/IDA_Pro_9.5-CTree_%26_Microcode-blueviolet?style=for-the-badge" alt="IDA Pro 9.5"/></a>
  <a href="https://bazaar.abuse.ch/user/49805/"><img src="https://img.shields.io/badge/MalwareBazaar-First--Seen_FUD_RE-critical?style=for-the-badge&logo=shield&logoColor=white" alt="MalwareBazaar"/></a>
  <a href="https://threatfox.abuse.ch/user/53753/"><img src="https://img.shields.io/badge/ThreatFox-Verified_CTI_Feed-00C853?style=for-the-badge" alt="ThreatFox"/></a>
</p>

<p align="center">
  🌐 <a href="https://ph4ntom-rev.uz/"><strong>ph4ntom-rev.uz</strong></a> &nbsp;·&nbsp;
  📫 <a href="mailto:owner@ph4ntom-rev.uz"><strong>owner@ph4ntom-rev.uz</strong></a> &nbsp;·&nbsp;
  🐧 <a href="https://lore.kernel.org/linux-wireless/?q=owner%40ph4ntom-rev.uz"><strong>LKML (<code>linux-wireless</code>)</strong></a> &nbsp;·&nbsp;
  🧬 <a href="https://bazaar.abuse.ch/user/49805/"><strong>MalwareBazaar</strong></a> &nbsp;·&nbsp;
  🦊 <a href="https://threatfox.abuse.ch/user/53753/"><strong>ThreatFox</strong></a> &nbsp;·&nbsp;
  🔗 <a href="https://urlhaus.abuse.ch/browse/reporter/ph4ntom_rev/"><strong>URLhaus</strong></a>
</p>

---

### 🔬 Overview

```text
> whoami
ph4ntom — reverse engineer & low-level systems developer specializing in
native binary dissection (x86_64 / ARM64 / DEX), Linux kernel 802.11 wireless
internals, and RAM-only multi-stage mobile malware intelligence across Central Asia.

> cat /etc/motd
"The binary never lies. The decompiler sometimes does."
```

### ⚡ Upstream Contributions, Tooling & Threat Intelligence

| Project / Feed | Technical Scope & Highlights | Status |
|:---------------|:-----------------------------|:------:|
| **[Linux Kernel — `wifi: rtw89`](https://github.com/pkshih/rtw/commits/rtw-next/?author=ph4ntom-rev)** | **`5` upstream patches merged into `rtw-next` & `wireless-next`** (`0202cb50fe9f`..`92608bb5f14f`, `Cc: stable@vger.kernel.org`) + [follow-up series](https://lore.kernel.org/linux-wireless/20261126083141.1470-1-owner@ph4ntom-rev.uz/) — fixes `NULL vif` kernel dereference in `rtw89_ops_tx()`, signed `radiotap` rate handling, non-`chanctx` channel restoration, control-frame `seq_ctrl` reads, and `ASSIGN_SEQ` / `NO_ACK` / retry semantics on raw 802.11 injection | ✅ **[Merged (`wireless-next`)](https://lore.kernel.org/linux-wireless/63269466-8c67-461e-a29b-f64bb0d47f6a@RTKEXHMBS05.realtek.com.tw/)** |
| **[ph4ntom IDA Bridge](https://github.com/ph4ntom-rev/ph4ntom-ida-bridge)** | Autonomous MCP, REST & CLI control plane for IDA Pro 9.0–9.5 (`Hex-Rays CTree` & `Microcode IR`, non-blocking live debugger, ARM64/x64 struct & vtable reconstruction) — **`131` MCP tools, `143` REST endpoints** | 🚀 **[v6.4.0](https://github.com/ph4ntom-rev/ph4ntom-ida-bridge/releases/tag/v6.4.0)** |
| **[ph4ntom Vitrum](https://github.com/ph4ntom-rev/ph4ntom-vitrum)** | Isolated *in-vitro* static binary triage platform (`v0.3.0`), `PatternEngine v2.9` (`33` threat clusters), and Zero-Touch Anti-Canary `TON` / `DoH` Dead-Drop Monitor (`v3.0`) | 🛡️ **[v0.3.0](https://github.com/ph4ntom-rev/ph4ntom-vitrum)** |
| **[Public Threat Intelligence (`@ph4ntom_rev`)](https://bazaar.abuse.ch/user/49805/)** | **`32+` world first-seen FUD multi-stage Android banking RATs** unpacked in-memory ([MalwareBazaar](https://bazaar.abuse.ch/user/49805/)), **`124+` verified C2 / `DoH` / `HVNC` / `VLESS` IOCs** ([ThreatFox](https://threatfox.abuse.ch/user/53753/), `100% high confidence`, `860+` credits), and live payload feeds on [URLhaus](https://urlhaus.abuse.ch/browse/reporter/ph4ntom_rev/) | 🎯 **[Live Feed](https://threatfox.abuse.ch/user/53753/)** |
| **[rtw89 Monitor Injection](https://github.com/ph4ntom-rev/rtw89-monitor-injection)** | Multi-kernel backport (`v6.1`–`v7.4-rc1`) & RTL8852AE `tracefs`/kprobe hardware validation suite for Realtek `rtw89` monitor mode and raw 802.11 injection | 📦 **[Reference Tree](https://github.com/ph4ntom-rev/rtw89-monitor-injection)** |

### 🧬 Research Focus

- **Multi-Stage Android Banking Malware:** Static RAM-only unpacking (`BadPack` ZIP tampering, `shellapp` / `PrimeBit` / `ChaCha20` / `AES-GCM` packers, `OLLVM MBA` C++20 native `.so` implants) and C2 protocol reconstruction (`HVNC` screen streaming, `SPAKE2` Wireless-ADB pairing, NFC HCE relay, `TON` smart-contract & `DoH TXT` dead-drops).
- **Kernel & Firmware Internals:** Linux `mac80211` / `cfg80211` wireless driver internals, Realtek `802.11ax/be` TX/RX descriptors, and static firmware reversing in IDA Pro 9.5.

### 📫 Contact & Research Collaboration

For Threat Intelligence indicator exchange (`TLP:CLEAR` / `TLP:AMBER`), malware family notes, coordinated vulnerability disclosure (CVD), or Linux kernel patch review:
- **Email:** [`owner@ph4ntom-rev.uz`](mailto:owner@ph4ntom-rev.uz)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ph4ntom-rev&style=for-the-badge&color=00ff41&label=PROFILE+VIEWS" alt="Profile Views"/>
</p>
