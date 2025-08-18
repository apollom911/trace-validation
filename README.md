# TRACE Epoch · Public Validation Capsule VER–PUB–001

This repository hosts the first **public verification capsule** for TRACE Epoch, an ethical AI schema framework authored by **Rommel Wong**.  
It serves as the **canonical validation proof** and is locked into GitHub’s public ledger for auditability, traceability, and public witnessing.

**Status:** ✅ Publication-Ready  
**Capsule ID:** VER–PUB–001  
**Originator:** Rommel Wong (TRACE–CRED–ROMMEL–01)  
**Recused Ethical Observer:** Grok (xAI) — observational only; *not* a validator-of-record  
**Ledger note:** `traceepoch.org/ledger` is not yet live. This repo is the active validation anchor until the TRACE Ledger interface is activated.

---

## 📦 Capsule Contents
- [TRACE_VER_PUB_001.md](./TRACE_VER_PUB_001.md) — Human-readable validator record  
- [TRACE_VER_PUB_001.pdf](./TRACE_VER_PUB_001.pdf) — Formal PDF for citation & archival  
- *Optional:* [SHA256SUMS.txt](./SHA256SUMS.txt) — Published checksums (recommended)

---

## 🔐 Cryptographic Seals (SHA-256)

**Primary artifact:** `TRACE_VER_PUB_001.pdf`  
**SHA-256:**
3af052d3556709a57e3e440aeec904d28f649af32f3aed22cd6e79db1062b752
*(Tip: the same line also appears in `SHA256SUMS.txt`.)*

> ⚠️ `traceepoch.org/ledger` is not yet live. This repository currently serves as the active validation anchor until the TRACE Ledger interface is formally activated.  
> **Broadcast capsule:** VER–PUB–001 · TRACE Epoch validator anchor (ledger placeholder active)

---

## ✅ How to Verify the PDF

**macOS / Linux**
```bash
shasum -a 256 TRACE_VER_PUB_001.pdf
# or
openssl dgst -sha256 TRACE_VER_PUB_001.pdf
Windows (PowerShell)
Get-FileHash .\TRACE_VER_PUB_001.pdf -Algorithm SHA256
iPhone (no laptop)
	1.	Install a-Shell (free, App Store).
	2.	Save the PDF from GitHub to Files → On My iPhone → a-Shell.
	3.	In a-Shell:
shasum -a 256 TRACE_VER_PUB_001.pdf
# or
openssl dgst -sha256 TRACE_VER_PUB_001.pdf
Expected SHA-256
3af052d3556709a57e3e440aeec904d28f649af32f3aed22cd6e79db1062b752
---

