<img src="https://i.ibb.co/rG4f2wFs/Screen.png" width="100%">

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║    𓃠  B A S T E T C I P H E R  𓃠                                   ║
║                                                                      ║
║         Guarded by Bastet, forged in entropy.                        ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

<img src="https://img.shields.io/badge/Cryptography-PBKDF2--HMAC--SHA512-gold?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAxTDMgNXY2YzAgNS41NSAzLjg0IDEwLjc0IDkgMTIgNS4xNi0xLjI2IDktNi40NSA5LTEyVjVsLTktNHoiLz48L3N2Zz4=" alt="Crypto Badge"/>
<img src="https://img.shields.io/badge/Zero_Dependencies-Pure_Vanilla-c9a84c?style=for-the-badge" alt="Zero Dependencies"/>
<img src="https://img.shields.io/badge/Single_File-HTML_+_CSS_+_JS-ff8c00?style=for-the-badge" alt="Single File"/>
<img src="https://img.shields.io/badge/XSS_Protected-CSP_+_DOM_API-00c896?style=for-the-badge" alt="XSS Protected"/>
<img src="https://img.shields.io/badge/Web_Crypto_API-SHA--256%2F384%2F512-royalblue?style=for-the-badge" alt="Web Crypto"/>
<img src="https://img.shields.io/badge/Sacred_Vault-AES--256--GCM_%2B_CBC-00c896?style=for-the-badge" alt="Sacred Vault"/>
<img src="https://img.shields.io/badge/Entropic_Amplifier-0--9999_chars-gold?style=for-the-badge" alt="Entropic Amplifier"/>
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/>

</div>

---

<div align="center">

# 𓃠 BastetCipher

### *An ancient Egyptian cryptographic chamber hidden inside a single HTML file.*

> A mystical, fully deterministic, multi-layer cryptographic engine wrapped in an immersive pyramid-temple experience — built entirely with zero dependencies, zero external resources, and zero compromise on security. Now featuring an **Entropic Amplifier** for unbounded cipher extension, and a full **Sacred Vault** for double-layer AES-256 encrypted file archiving — all 100% local, all in one file.

</div>

---

## 📜 Table of Contents

- [What Is BastetCipher?](#-what-is-bastetcipher)
- [Live Demo](#-live-demo)
- [What's New](#-whats-new)
- [The Visual Experience](#-the-visual-experience)
- [Features at a Glance](#-features-at-a-glance)
- [The Cryptographic Pipeline](#-the-cryptographic-pipeline)
  - [Step 1 — Deterministic Salt](#step-1--deterministic-salt)
  - [Step 2 — Base Hash Trinity](#step-2--base-hash-trinity)
  - [Step 3 — The Seed](#step-3--the-seed)
  - [Step 4 — Proprietary Transformation Layer](#step-4--proprietary-transformation-layer)
  - [Step 5 — Combination](#step-5--combination)
  - [Step 6 — PBKDF2-HMAC-SHA512 Key Derivation](#step-6--pbkdf2-hmac-sha512-key-derivation)
  - [Step 7 — Deterministic Special Character Insertion](#step-7--deterministic-special-character-insertion)
  - [Step 7b — Deterministic Mixed-Case Transformation](#step-7b--deterministic-mixed-case-transformation)
  - [Step 8 — Entropic Amplifier](#step-8--entropic-amplifier)
  - [Step 9 — Final Cipher Assembly](#step-9--final-cipher-assembly)
- [The PIM — Personal Iterations Multiplier](#-the-pim--personal-iterations-multiplier)
- [The Entropic Amplifier — Deep Dive](#-the-entropic-amplifier--deep-dive)
- [The Sacred Vault — Complete Technical Reference](#-the-sacred-vault--complete-technical-reference)
  - [.bca File Format Specification](#bca-file-format-specification)
  - [Tab 1 — Create Archive](#tab-1--create-archive)
  - [Tab 2 — Extract Archive](#tab-2--extract-archive)
  - [Tab 3 — Open Virtual Vault (In-Memory Browser)](#tab-3--open-virtual-vault-in-memory-browser)
  - [Vault Cryptographic Architecture](#vault-cryptographic-architecture)
  - [In-Memory File Viewer](#in-memory-file-viewer)
  - [Operational Security Notice](#operational-security-notice)
- [Security Architecture](#-security-architecture)
  - [XSS Protection](#xss-protection)
  - [Content Security Policy](#content-security-policy)
  - [Determinism Guarantee](#determinism-guarantee)
- [Animations & Visual Detail](#-animations--visual-detail)
- [Code Quality & Architecture](#-code-quality--architecture)
- [Browser Compatibility](#-browser-compatibility)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [Why One File?](#-why-one-file)
- [FAQ](#-faq)
- [License](#-license)

---

## 🏛️ What Is BastetCipher?

**BastetCipher** is a deterministic cryptographic cipher generator disguised as an ancient Egyptian temple.

You give it a **secret phrase** and a **PIM (Personal Iterations Multiplier)**. It runs that input through a 9-step cryptographic pipeline — involving SHA-256, SHA-384, SHA-512, a custom multi-stage proprietary transformation, PBKDF2 with HMAC-SHA512, a seeded PRNG for special character injection, a deterministic mixed-case transformer, and optionally the **Entropic Amplifier** — and produces a **powerful, unique, reproducible cipher string** of any desired length.

Same phrase + same PIM + same amplifier → **always** the same output.  
Wrong PIM → completely different cipher. Every. Single. Time.

It also ships with the **Sacred Vault**: a full AES-256-GCM + AES-256-CBC double-layer file encryption system that can archive up to 1,024 files into a single `.bca` container, decrypt and extract them back to a `.zip`, or browse and open them entirely in RAM — never touching disk.

It is:
- 🔐 **Cryptographically serious** — not a toy, not a gimmick
- 🎨 **Visually spectacular** — an animated Egyptian temple experience
- 📦 **A single HTML file** — open it anywhere, no server, no install, no internet
- 🛡️ **Hardened against XSS** — CSP meta tag + pure DOM API output construction
- ⚡ **Fast** — PBKDF2 completes in 1–3 seconds regardless of PIM value
- 🔮 **Fully deterministic** — no randomness, no timestamps, no entropy leakage
- 🗄️ **A complete encrypted file vault** — AES-256-GCM + AES-256-CBC, 200,000 PBKDF2 iterations, deflate-raw compression, CRC32 integrity verification

---

## 🌐 Live Demo

Simply download [`BastetCipher.html`](./BastetCipher.html) and open it in any modern browser.

```bash
# Clone and open
git clone https://github.com/yourusername/BastetCipher.git
cd BastetCipher
open BastetCipher.html   # macOS
start BastetCipher.html  # Windows
xdg-open BastetCipher.html # Linux
```

No npm. No build step. No server. No internet required. Just open and use.

---

## 🆕 What's New

The following major features have been added since the initial release. The original cryptographic pipeline is **100% unchanged** — all additions are new, independent modules.

### Entropic Amplifier
A new optional input field (`0`–`9999`) that **deterministically extends the cipher** by exactly N extra characters, derived from a SHA-512 seeded PRNG that is cryptographically bound to the phrase, PIM, amplifier value, derived key, and the embedded PEPPER. Same four inputs → always the same extension. The amplifier output uses a 78-character alphabet (`0-9a-zA-Z!@#$%^&*_-+=~?`) for maximum entropy density. Setting it to `0` leaves the pipeline output identical to the original behaviour. Full technical details in [The Entropic Amplifier — Deep Dive](#-the-entropic-amplifier--deep-dive).

### Sacred Vault — Encrypted File Archive System
A complete file encryption module embedded inside the same HTML file, visually separated in an emerald-themed chamber below the main altar. The Sacred Vault operates entirely locally, supports up to 1,024 files per archive, and produces `.bca` (BastetCipher Archive) files using:
- **AES-256-GCM** (Layer 1) — authenticated encryption with a 96-bit random IV
- **AES-256-CBC** (Layer 2) — second encryption layer with a 128-bit random IV
- **PBKDF2-HMAC-SHA512** at **200,000 fixed iterations** for key derivation
- **deflate-raw compression** on every file before encryption
- **CRC32 integrity checksum** on every file's original data
- Three tabs: **Create**, **Extract**, **Open Virtual Vault**

### In-Memory Virtual Vault Browser
The "Open Virtual Vault" tab decrypts the archive entirely in RAM and lets you browse and open files **without writing anything to disk**. The built-in file viewer renders images, audio, video, PDFs, text, JSON, CSV, Markdown, and HTML inside a sandboxed iframe — all from in-memory data URIs or BlobURLs. RAM is explicitly zeroed on vault close. BlobURLs are revoked immediately after use.

### Operational Security Notice Panel
A red-bordered warning section inside the Sacred Vault, with four detailed technical cards covering: disabling hibernation (to prevent RAM dump to disk), disabling virtual memory/swap, full-disk encryption recommendations (including an explicit warning about BitLocker's closed-source nature and Microsoft's FISA/NSL obligations), and multi-pass secure file deletion tools for all major OS platforms.

### Welcome Overlay
A full-screen animated modal that greets users on first open, presenting the cryptographic architecture in a readable format with animated particle effects, a gold rotating border, and the "Enter the Temple" button. Includes the technical grid (6 cards) and a plain-language explanation of what BastetCipher does and why it is safe.

---

## 🏺 The Visual Experience

BastetCipher is not just a crypto tool. It is an **experience**.

The interface is designed to feel like you have discovered an ancient Egyptian cryptographic chamber inside a pyramid dedicated to the goddess **Bastet** — deity of protection, secrets, and the home.

| Element | Description |
|---|---|
| 🐱 **Bastet Statue** | A fully hand-crafted inline SVG cat goddess — golden body, glowing emerald eyes, animated halo rings with radial glow, golden collar with turquoise/lapis/ruby gemstones and hanging pendants, scarab crown, kohl eyeliner, whiskers, blinking eyelid animation (double blink pattern on an 8-second loop), independent left/right pupil rendering, animated tail with slow swaying motion, and a full paw-pad detail with individual toe pads and nail marks |
| 🔥 **Animated Torches** | Two wall torches with four-layer CSS flame animation — outer core, mid-flame, tip flicker, inner glow — plus floating ember sparks rising upward. Each torch uses **independent animation durations** so they never synchronise. The top-left torch has slightly different timing from the top-right torch, creating organic, non-mechanical fire. Four ember particles per torch with different colours (gold, orange, white, dark orange) and different `--dur`/`--del` CSS custom properties |
| ⚙️ **Cipher Wheel** | A rotating golden disk engraved with 6 hieroglyphs on its outer ring at 60° intervals (`𓃠 𓂀 𓆣 𓇯 𓋹 𓊹`); spins at `20s linear infinite` at rest, switches to `1s` during generation via `.spinning` class |
| 🔑 **Ancient Key** | Hand-drawn SVG key with an ankh ring, the `𓋹` hieroglyph inside the bow, a gold gradient shaft, and three teeth protruding from the blade |
| 🌟 **Sand Particles** | 80 canvas-rendered floating particles in gold (`#c9a84c`) and sand (`#d4b483`) tones, drifting upward with randomised lifetimes (100–300 frames), x-drift, and fade-out curves via `requestAnimationFrame` |
| 🔺 **Background Pyramid** | A three-ring nested outline pyramid with the Eye of Ra at its centre (outer ellipse, inner circle, filled pupil); pulses gently at `6s ease-in-out infinite`, intensifies dramatically during cipher generation via `.active` class |
| 📜 **Stone Wall Columns** | Left and right SVG panels of 13 stacked hieroglyphs per side with two gold border lines each; mirrored horizontally on the right via `transform:scaleX(-1)` |
| 🕯️ **Torch Halos** | Radial glow circles behind each torch with `@keyframes torchFlicker` — opacity and scale oscillation |
| 👁️ **Bastet Eyes** | Two eye-orb indicators that cycle through 5 green hues continuously via a `requestAnimationFrame` HSL loop; pulse and intensify when cipher generation is active with the `.active` CSS class |
| 🔒 **Lock Icon** | Snaps from 🔒 to 🔓 with `@keyframes lockBounce` (scale 1 → 1.4 → 0.9 → 1 with rotation) when cipher completes |
| ✨ **Rune Bursts** | 14 hieroglyph glyphs drawn from a 12-symbol pool explode outward from the generate button in a full starburst (360° / 14 positions), each at a randomised distance (80–200px), random delay (0–0.3s), and CSS `--tx`/`--ty` custom properties |
| 📟 **Rune Display** | Cycles through 6 random hieroglyphs from a 12-symbol pool every 80ms via `setInterval` during generation; stops and resets to `𓃠 𓂀 𓊹 𓆣 𓇯 𓋹` on completion |
| 🖥️ **Typewriter Output** | The cipher string types itself onto the stone tablet in 8-character chunks every 18ms |
| 🏺 **Engraved Border Bands** | Scrolling hatched gold pattern at top and bottom of both the altar and vault panels via `@keyframes bandScroll` |
| 🌠 **Title Shimmer** | The golden gradient title pulses and brightens on a 4-second loop |
| 🌙 **Tagline Fade** | The subtitle fades between stone-pale and gold on a 5-second cycle |
| 🟢 **Vault Emerald Theme** | The Sacred Vault panel uses a completely separate emerald (`#00c896`) colour palette — dark green background gradients, emerald borders, animated emerald shimmer on the title, and an emerald animated action button with `@keyframes vaultBtnFlow` |
| 📋 **Welcome Overlay** | A full-screen modal with a rotating gold conic-gradient border, 5 floating gold particles, an Eye of Ra SVG, animated tech cards appearing sequentially with `@keyframes cardAppear`, and a plain-language explanation panel |

The favicon is a hand-crafted embedded SVG: a golden Bastet bust with glowing eyes set against a dark background, with pyramid silhouette — visible in the browser tab.

---

## ✨ Features at a Glance

- ✅ **Zero external dependencies** — no libraries, no CDN, no fonts from Google
- ✅ **Zero network requests** — all resources embedded; works fully offline
- ✅ **One file** — the entire application is `BastetCipher.html`
- ✅ **Fully deterministic** — identical input + PIM + amplifier → identical output, always
- ✅ **PIM-sensitive** — each PIM value produces a structurally different cipher
- ✅ **PBKDF2-HMAC-SHA512** — industry-standard key derivation function
- ✅ **Web Crypto API** — uses the browser's native, hardware-accelerated crypto
- ✅ **Proprietary 4-stage hash transformation** — rotation, swap, remap, reverse
- ✅ **Mixed case output** — exactly 50% uppercase / 50% lowercase alphabetic chars
- ✅ **Special character injection** — 8–15 special chars at deterministic positions
- ✅ **Entropic Amplifier** — extends cipher by 0–9999 additional deterministic characters
- ✅ **Sacred Vault** — AES-256-GCM + AES-256-CBC double-layer file encryption
- ✅ **`.bca` archive format** — custom binary format with magic bytes, versioning, salt, IVs
- ✅ **deflate-raw compression** — CompressionStream API, every file compressed before encryption
- ✅ **CRC32 integrity** — per-file checksum verified during extraction and browsing
- ✅ **200,000 PBKDF2 iterations** for vault key derivation (OWASP-compliant)
- ✅ **In-memory vault browser** — browse, open, and view files without writing to disk
- ✅ **Sandboxed file viewer** — iframe with strict CSP for safe rendering of untrusted content
- ✅ **Multi-format viewer** — images, audio, video, PDF, text, JSON, CSV, Markdown, HTML
- ✅ **RAM zeroing** — all decrypted data explicitly `fill(0)` on vault close
- ✅ **BlobURL revocation** — `URL.revokeObjectURL()` called immediately after use
- ✅ **XSS-hardened** — CSP meta tag, `escapeHTML()` utility, zero `innerHTML` from user data
- ✅ **SVG favicon** — embedded data-URI, no external image file
- ✅ **Mobile responsive** — adapts gracefully to small screens
- ✅ **Clipboard copy** — one-click copy with animated confirmation
- ✅ **Progress bar** — live status updates during both the cipher pipeline and vault operations
- ✅ **Cipher stats panel** — length, iterations, algorithm, amplifier status, salt preview
- ✅ **Enter key support** — press Enter to generate
- ✅ **PIM validation** — enforces 1–32 digit numeric input, strips leading zeros
- ✅ **Amplifier validation** — clamps 0–9999, strips non-numeric characters on input
- ✅ **Up to 1,024 files** per `.bca` archive
- ✅ **ZIP output on extraction** — standard `.zip` file, compatible with all tools
- ✅ **Operational security guide** — in-app hibernation, swap, disk encryption, and secure deletion instructions

---

## 🔐 The Cryptographic Pipeline

Every time you click **Generate Cipher**, the following 9-step pipeline executes deterministically. The same inputs will always produce byte-for-byte identical output.

```
INPUT ──────────────────────────────────────────────────────────────►
           │
           ▼
  ┌─────────────────────────────────────────────────────────────┐
  │  PEPPER  (embedded secret, constant per installation)        │
  └─────────────────────────────────────────────────────────────┘
           │
    ┌──────▼──────┐
    │   STEP 1    │  SHA-256("BastetCipher" + input + pim + pepper + "SacredSalt")
    │   SALT      │  → 64-char hex deterministic salt
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 2    │  h1 = SHA-256(input + salt + pim + pepper)
    │   HASHES    │  h2 = SHA-384(salt + input + pim + pepper)
    │             │  h3 = SHA-512(input:salt:pim:pepper)
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 3    │  seed = SHA-256(input + pim + pepper)
    │   SEED      │  (drives all downstream transformations)
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 4    │  t1 = transformHash(h1, seed)
    │ TRANSFORM   │  t2 = transformHash(h2, seed)
    │             │  t3 = transformHash(h3, seed)
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 5    │  combined = ".," + t1 + t2 + t3 + ",."
    │  COMBINE    │
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 6    │  PBKDF2-HMAC-SHA512
    │  PBKDF2     │  password = combined + pepper
    │             │  salt     = SHA-256("BastetCipher" + input + pim + pepper)
    │             │  iters    = f(SHA-256(pim + pepper + "IterSeed")) → 50k–600k
    │             │  keyLen   = 64 bytes → 128-char hex
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 7    │  insertSpecialChars(derivedKey, seed)
    │  SPECIALS   │  8–15 chars from !@#$%^&*_-+=~?
    │             │  at deterministic PRNG positions
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │  STEP 7b    │  applyMixedCase(str, seed)
    │ MIXED CASE  │  50% uppercase / 50% lowercase
    │             │  via seeded Fisher-Yates shuffle
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 8    │  generateAmplification(input, pim, derivedKey, amplifier)
    │  AMPLIFIER  │  SHA-512 seeded PRNG → N extra chars (0–9999)
    │             │  alphabet: 0-9 a-z A-Z !@#$%^&*_-+=~? (78 chars)
    └──────┬──────┘
           │
    ┌──────▼──────┐
    │   STEP 9    │  finalCipher = ".," + withCase + ampExtension + ",."
    │   OUTPUT    │
    └─────────────┘
           │
           ▼
OUTPUT ─────────────────────────────────────────────────────────────►
```

---

### Step 1 — Deterministic Salt

```js
salt = SHA256("BastetCipher" + input + pim + pepper + "SacredSalt")
```

A unique 256-bit salt is derived from the full input context. This ensures that even two phrases that share the same PIM will have completely unrelated salt values, preventing any cross-input correlation.

---

### Step 2 — Base Hash Trinity

```js
h1 = SHA256(input + salt + pim + pepper)                          // 64  hex chars
h2 = SHA384(salt  + input + pim + pepper)                         // 96  hex chars
h3 = SHA512(input + ":" + salt + ":" + pim + ":" + pepper)        // 128 hex chars
```

Three different SHA variants are used deliberately:
- **SHA-256** provides the compact, fast anchor
- **SHA-384** adds entropy width at a different internal state
- **SHA-512** provides the longest raw material and a different Merkle-Damgård length

The argument ordering differs between h1, h2, and h3, ensuring the three hashes are maximally independent from one another.

---

### Step 3 — The Seed

```js
seed = SHA256(input + pim + pepper)
```

This 256-bit seed drives every deterministic operation downstream — the transformation, special character positions, and mixed-case selection. It is derived independently of the salt to avoid feedback loops.

---

### Step 4 — Proprietary Transformation Layer

`transformHash(hash, seed)` applies four sequential deterministic stages to each of the three hashes:

#### Stage 1 — Left Rotation
```
rotAmt = seedNum % hash.length
result = hash[rotAmt:] + hash[:rotAmt]
```
Rotates the character string left by a seed-derived offset, destroying any positional patterns.

#### Stage 2 — Position Swapping
```
swapStep = (seedNum % 7) + 2   → range: 2..8
For every pair of positions i, i+swapStep: swap characters
```
Disrupts sequential runs and interleaves distant parts of the string.

#### Stage 3 — Hex Digit Remapping
A 16-element permutation table `hexMap[0..15]` is constructed via a seeded Fisher-Yates shuffle of `[0..15]` using an LCG (Linear Congruential Generator) seeded from the first 8 bytes of the seed hex. Every hex digit `0–9, a–f` is remapped through this table, making all frequency analysis against standard hex character distributions useless.

#### Stage 4 — Section Reversal
```
secLen = (seedNum % 12) + 4   → range: 4..15
Every odd-indexed chunk of secLen characters is reversed
```
Introduces long-range dependencies across the string, ensuring small input changes cascade across the entire output.

---

### Step 5 — Combination

```js
combined = ".," + t1 + t2 + t3 + ",."
```

The three transformed hashes are concatenated with a structural delimiter, producing a string of `4 + 64 + 96 + 128 = 292` characters before PBKDF2. The delimiters are part of the input to PBKDF2, contributing to the entropy of the derived key.

---

### Step 6 — PBKDF2-HMAC-SHA512 Key Derivation

This is the security core of BastetCipher.

```js
// Iteration count: hash-derived, not linear — fast AND PIM-sensitive
pimHash  = SHA256(pim + pepper + "IterSeed")
hashInt  = parseInt(pimHash[0:6], 16)              // 24-bit integer
baseIter = 50000 + floor((hashInt / 16777215) * 550000)   // 50k–600k
twist    = (pimNum % 65537) * 7                    // per-PIM offset
iters    = baseIter + twist

// Key derivation
PBKDF2(
  password = combined + pepper,
  salt     = SHA256("BastetCipher" + input + pim + pepper),
  hash     = HMAC-SHA512,
  iters    = iters,
  keyLen   = 64 bytes   →   128-char hex string
)
```

**Why this iteration formula?**

The naive approach `100000 + pim * 500` is catastrophic with large PIMs — PIM `563519` would produce 281 million iterations, taking minutes. BastetCipher solves this elegantly:

- The iteration count is **hash-derived** from the PIM, not linear — so it always falls in the 50,000–600,000 range
- Every PIM still produces a **unique iteration count** via the `twist` term
- A wrong PIM changes the iteration count AND all upstream material — producing a completely different derived key
- 50k–600k PBKDF2-HMAC-SHA512 iterations is the OWASP/NIST recommended range for modern systems

All crypto is performed through the **Web Crypto API** (`window.crypto.subtle`) — the browser's native, hardware-accelerated cryptographic engine.

---

### Step 7 — Deterministic Special Character Insertion

```js
SPECIAL = '!@#$%^&*_-+=~?'
rng     = LCG seeded from seed
count   = 8 + floor(rng() * 8)   →   8–15 insertions

For each insertion:
  pos  = floor(rng() * (arr.length + 1))
  char = SPECIAL[floor(rng() * 14)]
  arr.splice(pos, char)
```

A seeded LCG with parameters `(1664525, 1013904223, 2^32)` — the classic Numerical Recipes constants — drives all position and character selection.

---

### Step 7b — Deterministic Mixed-Case Transformation

```js
// Independent PRNG stream: reversed seed hex prevents collision with Step 7
rng = LCG seeded from reversed(seed)

alphaIndices = all positions of [a-zA-Z] characters
half         = ceil(alphaIndices.length / 2)

// Fisher-Yates shuffle of alpha positions
shuffled = [...alphaIndices]
for i from len-1 downto 1:
  j = floor(rng() * (i+1))
  swap(shuffled[i], shuffled[j])

// First half → uppercase, second half → lowercase
upperSet = Set(shuffled[0:half])
```

This guarantees exactly **50% uppercase and 50% lowercase** alphabetic characters — never more, never less — while all digits, special characters, and punctuation remain completely unchanged. The reversed-seed trick ensures the PRNG stream for case selection is **fully independent** from the stream used for special character insertion.

---

### Step 8 — Entropic Amplifier

This step is new. It is only active when the amplifier input is `> 0`.

```js
async function generateAmplification(input, pim, derivedKey, amplifier) {
  if (amplifier === 0) return '';

  // The amplifier seed is cryptographically bound to ALL four inputs
  const ampSeedHex = await sha512(
    input + '§' + pim + '§' + String(amplifier) +
    '§' + derivedKey + '§' + PEPPER + '.,§SacrumMAmplificator,.'
  );

  // XOR the first two 32-bit words of the seed for extra mixing
  let state = (parseInt(ampSeedHex.slice(0, 8), 16) ^
               parseInt(ampSeedHex.slice(8, 16), 16)) >>> 0;

  const AMP_ALPHABET = '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*_-+=~?';
  let result = '';

  for (let i = 0; i < amplifier; i++) {
    state = (state * 1664525 + 1013904223) >>> 0;   // LCG step
    result += AMP_ALPHABET[state % 78];
  }
  return result;
}
```

Key properties:
- The seed is SHA-512 of the concatenation of **phrase, PIM, amplifier value, the full PBKDF2-derived key, and PEPPER** — meaning the amplifier output is cryptographically bound to all cipher inputs simultaneously
- The `§` separator (Unicode `U+00A7`) is used to prevent trivial concatenation collisions
- The initial LCG state is an XOR of the first two 32-bit big-endian words of the SHA-512 hex, ensuring the state is seeded from 64 bits of hash material rather than just 32
- The alphabet has 78 characters — 10 digits + 26 lowercase + 26 uppercase + 16 special — providing `log2(78) ≈ 6.29` bits of entropy per character
- A 9999-character amplifier output therefore contributes approximately **62,900 bits of deterministic entropy extension**
- The same four inputs always produce the exact same extension; changing any single input by one character completely changes all 9999 characters

---

### Step 9 — Final Cipher Assembly

```js
finalCipher = ".," + withCase + ampExtension + ",."
```

The mixed-case cipher (from Step 7b) and the amplifier extension (from Step 8) are concatenated before the closing sentinel. The `.,` / `,.` delimiters serve as recognisable structural boundaries.

---

## 🔢 The PIM — Personal Iterations Multiplier

The PIM is your **second secret**. It is not a password — it is a multiplier of cryptographic complexity.

| PIM Property | Detail |
|---|---|
| **Format** | 1 to 32 digits, numeric only |
| **Default example** | `563519` |
| **Effect on salt** | Changes the deterministic salt (Step 1) |
| **Effect on hashes** | Incorporated into h1, h2, h3 inputs |
| **Effect on seed** | Changes the transformation seed |
| **Effect on iterations** | Non-linearly remaps the PBKDF2 iteration count |
| **Effect on amplifier** | Changes the amplifier seed (Step 8) |
| **Wrong PIM result** | Completely unrelated cipher — no partial match |
| **Security model** | Functions as a second factor; attacker needs both phrase AND PIM |

The PIM is embedded into **seven separate points** in the pipeline, meaning a brute-force attack must correctly guess both the phrase and the PIM simultaneously to have any chance of reproducing the output.

---

## 🔭 The Entropic Amplifier — Deep Dive

The Entropic Amplifier is an optional fourth input, accepting any integer from `0` to `9999`. It deterministically extends the final cipher output by exactly that many characters.

### Why it exists

The base PBKDF2 pipeline produces a cipher of fixed length (~140 characters after special char insertion and delimiters). While this is cryptographically strong, some use cases — such as generating a master key for a full-disk encryption container, a long token, or a key derivation basis — benefit from more output material. The Amplifier solves this without compromising the determinism guarantee.

### What it is NOT

The Amplifier is **not** a second cipher, **not** independently secure from the base cipher, and **not** a replacement for the PBKDF2 pipeline. It extends the output using an LCG seeded from a SHA-512 hash that incorporates the already-derived PBKDF2 key — so the extension is only as strong as the base cipher it extends. It adds length and entropy density, not independent cryptographic hardness.

### Determinism guarantee

The amplifier extension is bound to **all four inputs simultaneously**:

```
ampSeed = SHA-512(phrase § PIM § amplifierValue § PBKDF2derivedKey § PEPPER)
```

This means:
- Changing the phrase → completely different extension
- Changing the PIM → completely different extension  
- Changing the amplifier value → completely different extension (and different length)
- Changing none → byte-identical extension, always

### Amplifier value `0`

When the amplifier is set to `0`, `generateAmplification()` returns an empty string immediately without any computation. The output is identical to a run with no amplifier at all. The `0` case is explicitly a no-op.

### Entropy contribution

| Amplifier Value | Extra Characters | Approximate Extra Entropy |
|---|---|---|
| 0 | 0 | 0 bits |
| 100 | 100 | ~629 bits |
| 500 | 500 | ~3,145 bits |
| 1000 | 1,000 | ~6,290 bits |
| 9999 | 9,999 | ~62,894 bits |

These are theoretical maximums assuming uniform distribution from the 78-character alphabet. The actual entropy is bounded by the SHA-512 seed (512 bits of internal state), but the output is pseudorandomly uniform across that space.

---

## 🗄️ The Sacred Vault — Complete Technical Reference

The Sacred Vault is a complete file encryption system embedded in the same HTML file. It is visually and functionally independent from the cipher generator, using its own colour scheme (emerald), its own key derivation parameters, and its own binary container format.

### .bca File Format Specification

`.bca` stands for **BastetCipher Archive**. The binary format is:

```
Offset  Size    Field
──────  ──────  ─────────────────────────────────────────────────────
0       4       Magic bytes: 0x42 0x43 0x41 0x01  ("BCA\x01")
4       1       Version: 0x01
5       32      PBKDF2 Salt (random, 256-bit)
37      4       PBKDF2 Iteration count (little-endian uint32) = 200000
41      12      AES-GCM IV (random, 96-bit)
53      16      AES-CBC IV (random, 128-bit)
69      N       Ciphertext (AES-CBC output wrapping AES-GCM output)
```

The **plaintext** that is double-encrypted has the following internal structure:

```
Offset  Size    Field
──────  ──────  ─────────────────────────────────────────────────────
0       2       File count (little-endian uint16)

For each file:
  +0    2       Filename length in bytes (little-endian uint16)
  +2    L       Filename (UTF-8 encoded bytes)
  +L+2  4       CRC32 of original (uncompressed) data (little-endian uint32)
  +L+6  4       Original file size in bytes (little-endian uint32)
  +L+10 4       Compressed size in bytes (little-endian uint32)
  +L+14 C       deflate-raw compressed file data
```

### Vault Cryptographic Architecture

#### Key Derivation

```js
async function deriveVaultKeys(password, salt, iterations) {
  const km = await crypto.subtle.importKey(
    'raw',
    new TextEncoder().encode(password),
    { name: 'PBKDF2' },
    false,
    ['deriveBits']
  );
  const bits = await crypto.subtle.deriveBits(
    { name: 'PBKDF2', salt, iterations, hash: 'SHA-512' },
    km,
    512   // 512 bits = 64 bytes
  );
  // First 32 bytes → AES-256-GCM key (k1)
  const k1 = await crypto.subtle.importKey('raw', bits.slice(0, 32),  { name: 'AES-GCM' }, false, ['encrypt', 'decrypt']);
  // Next 32 bytes  → AES-256-CBC key (k2)
  const k2 = await crypto.subtle.importKey('raw', bits.slice(32, 64), { name: 'AES-CBC' }, false, ['encrypt', 'decrypt']);
  new Uint8Array(bits).fill(0);   // Zero the raw key material immediately
  return { k1, k2 };
}
```

The password is hashed through PBKDF2-HMAC-SHA512 at **200,000 fixed iterations**, producing 512 bits. These are split into two independent 256-bit keys — one for GCM, one for CBC — so the two encryption layers never share key material.

#### Encryption (Create Archive)

```
1. Generate 32-byte random PBKDF2 salt   (crypto.getRandomValues)
2. Generate 12-byte random GCM IV        (crypto.getRandomValues)
3. Generate 16-byte random CBC IV        (crypto.getRandomValues)
4. Derive k1 (GCM) and k2 (CBC) from password + salt at 200k iterations
5. For each file:
   a. Compress with deflate-raw (CompressionStream API)
   b. Compute CRC32 of original data
   c. Append to plaintext blob with header (filename, CRC, sizes, compressed data)
6. Encrypt plaintext blob with AES-256-GCM using k1 and iv1   → ct1 (includes 128-bit auth tag)
7. Encrypt ct1 with AES-256-CBC using k2 and iv2              → ct2
8. Assemble: magic + version + salt + iter_count + iv1 + iv2 + ct2
9. Zero all intermediate plaintext and key material from memory
```

#### Decryption (Extract / Browse)

```
1. Read and verify magic bytes (0x42 0x43 0x41 0x01)
2. Read salt (bytes 5–36), iteration count (bytes 37–40), iv1 (41–52), iv2 (53–68), ct2 (69+)
3. Derive k1 and k2 from password + salt at stored iteration count
4. Decrypt ct2 with AES-256-CBC using k2 and iv2              → ct1
   On failure: throw "Layer 2 Error"
5. Decrypt ct1 with AES-256-GCM using k1 and iv1              → plaintext
   On failure: throw "Layer 1 Error" (GCM auth tag mismatch = wrong password or corruption)
6. Parse plaintext: read file count, then for each file read header and decompress data
7. Verify CRC32 of each decompressed file against stored checksum
```

The AES-GCM authentication tag provides **tamper detection**: if any byte of the ciphertext is modified (including the CBC layer), the GCM decryption will fail with an authentication error. A wrong password → wrong k1/k2 → GCM tag mismatch → immediate rejection before any output is produced.

#### Why two encryption layers?

AES-GCM provides authenticated encryption (confidentiality + integrity) but has a known attack surface if IVs are reused — if the same IV were used twice with the same key, the keystream cancels out and plaintext is recoverable. AES-CBC does not have this property, providing defense-in-depth: even a catastrophic IV reuse in the GCM layer (which cannot happen here because IVs are `crypto.getRandomValues`) would still leave the data protected by the outer CBC layer. The two layers also use different keys derived from the same PBKDF2 pass, meaning attacking one layer provides no information about the key for the other.

#### Compression

Every file is compressed with `deflate-raw` via the browser's native `CompressionStream` API before encryption. This serves two purposes:
1. Smaller archives (especially for text, JSON, code, and other compressible formats)
2. Compression before encryption removes exploitable patterns from the plaintext — an attacker who knows part of the plaintext cannot use that knowledge to search for known-plaintext blocks

#### CRC32 Integrity

A CRC32 checksum is computed over each file's **original, uncompressed** data before compression and encryption. During extraction and browsing, after decompression, the CRC32 is recomputed and compared. A mismatch indicates either archive corruption or a decompression error. The CRC32 is stored in the plaintext container (inside the encryption boundary), so it cannot be tampered with without breaking the GCM authentication tag.

---

### Tab 1 — Create Archive

1. **Drop zone** — drag and drop any files, or click to open a file picker. Accepts any format. Up to **1,024 files** per archive. File names are sanitised (removes control characters, `<>"'\`&/\`) before storage.
2. **File list** — scrollable list showing each file's name and size with a remove button.
3. **Password field** — the encryption password. `autocomplete="new-password"` to prevent browser autofill pollution.
4. **Create and Encrypt button** — triggers the full pipeline:
   - Reads all files as `ArrayBuffer` via `FileReader`
   - Runs `buildBCA()` with progress callbacks updating the status bar
   - Progress stages: key derivation (5%) → per-file processing (22–70%) → GCM encryption (74%) → CBC encryption (85%) → finalisation (92%) → done
   - Downloads the resulting `.bca` file automatically
   - Zeroes all intermediate `Uint8Array` buffers after use
5. **Algorithm pills** — visible reminder: AES-256-GCM · AES-256-CBC · PBKDF2-HMAC-SHA512 · 200k+ iterations · deflate-raw · 96-bit IV · 256-bit salt

The default archive filename is the name of the single uploaded file (minus extension) if only one file was uploaded, otherwise `sacred_archive.bca`.

---

### Tab 2 — Extract Archive

1. **Drop zone** — accepts a single `.bca` file. Displays the filename and size once loaded.
2. **Password field** — `autocomplete="current-password"`.
3. **Decrypt and Extract button** — triggers:
   - `parseBCA()` — full decryption pipeline with progress callbacks
   - `buildZipFromEntries()` — assembles a valid ZIP file from the decrypted entries
   - Downloads `<originalname>_extracted.zip`
4. **ZIP construction** — the ZIP is built entirely in JavaScript using the PKZIP specification (local file headers, central directory, end-of-central-directory record). The compression method field is set to `8` (deflate), and the already-compressed data is stored as-is with the original file sizes and CRC32 values — the output ZIP is fully compatible with all ZIP tools (7-Zip, WinRAR, macOS Archive Utility, etc.)
5. **Algorithm pills** — visible reminder: GCM/CBC auth tamper verification · wrong password = immediate rejection · standard .zip output · this time written to disk

---

### Tab 3 — Open Virtual Vault (In-Memory Browser)

This is the most advanced tab. It decrypts the `.bca` archive into RAM and lets you browse and open files without writing anything to disk.

1. **Drop zone** — accepts a single `.bca` file. Displays size and "Archive ready, enter the password".
2. **Password field** — cleared immediately after use (`.value = ''`).
3. **Open Virtual Vault button** — triggers `vaultOpenVault()`:
   - Calls `parseBCA()` (full decryption, same as extract)
   - Stores the decrypted `entries` array (with compressed data still in memory) in `vaultBrowseState.entries`
   - Renders the file list
   - Shows success message with file count
4. **File list** — each entry shows:
   - A hieroglyphic icon based on file extension (pdf=`𓇲`, mp4/video=`𓊹`, mp3/audio=`𓏢`, images=`𓁹`, html=`𓃠`, text/json/csv=`𓇯`, zip=`𓆣`, unknown=`𓄿`)
   - Filename
   - Original file size
   - "Open" button
5. **File opening** — `vaultOpenFile(index)`:
   - Decompresses the entry's `compressed` data via `DecompressionStream('deflate-raw')`
   - Verifies decompressed size matches `origSize`
   - Determines MIME type from file extension
   - Builds a sandboxed `srcdoc` or BlobURL for the iframe viewer
   - Zeroes the decompressed data buffer immediately after use

---

### In-Memory File Viewer

The viewer is a full-screen overlay with a dark-themed header, a sandboxed iframe body, and a security status bar.

| File Type | Rendering Method |
|---|---|
| Images (jpg, png, gif, webp, svg, bmp) | `<img>` with `data:` URI inside srcdoc |
| Audio (mp3, ogg, wav, flac, aac) | `<audio controls>` with `data:` URI inside srcdoc |
| Video (mp4, webm, mov, avi, mkv) | `<video controls>` with `data:` URI inside srcdoc |
| PDF | BlobURL (`URL.createObjectURL`) → `frame.src` |
| Text / Markdown / JSON / XML / CSV / code | HTML-escaped `<pre>` inside srcdoc with monospace font |
| HTML / HTM | srcdoc with `sandbox="allow-scripts"` (no same-origin, no forms, no top navigation) |
| Unknown formats | Info panel showing MIME type and file size |

**Security model of the viewer:**
- All `srcdoc` content has its own strict CSP: `default-src 'none'; style-src 'unsafe-inline'; script-src 'none'; img-src data:; media-src data:; object-src data:`
- This prevents any content inside the viewer from making network requests, accessing cookies, accessing `localStorage`, or communicating with the parent page
- HTML files get `sandbox="allow-scripts"` which permits JavaScript execution inside the frame but denies same-origin access, form submission, and top-level navigation
- PDF files use a BlobURL which is revoked via `URL.revokeObjectURL()` as soon as the viewer is closed (`vaultCloseViewer()`)
- The iframe `referrerpolicy="no-referrer"` prevents the parent page URL from leaking

**RAM management:**
- All decompressed file data is stored in `Uint8Array` buffers
- After building the `srcdoc` or handing data to the BlobURL, the buffer is immediately `fill(0)` zeroed
- On vault close (`vaultCloseVault()`), the entire `entries` array is iterated and every `compressed` buffer is `fill(0)` zeroed before nulling the reference
- The `bcaFile.buffer` is also zeroed and nulled on close
- The drop zone text and sub-text are reset to their default state

---

### Operational Security Notice

The Sacred Vault includes a red-bordered in-app security guide with four actionable cards:

#### 🔴 Disable Hibernation
When a PC hibernates, the **entire RAM contents are written to disk** as a hibernation file (`hiberfil.sys` on Windows, `/var/vm/sleepimage` on macOS). Any files currently open in the Virtual Vault would end up on disk — entirely defeating the in-memory security model.
- **Windows:** `powercfg /h off` (disables hiberfil.sys)
- **macOS:** `sudo pmset -a hibernatemode 0`
- **Linux:** Remove the `resume=` line from GRUB and disable the swap partition from hibernation

#### 🔴 Disable Swap / Virtual Memory
If physical RAM is exhausted, the OS may page memory to disk (swap file / pagefile). This can include decrypted data even without hibernation.
- **Windows:** System → Advanced system settings → Performance → Virtual Memory → No paging file
- **macOS:** Swap is automatic; use FileVault to ensure the swap is encrypted at rest
- **Linux:** `sudo swapoff -a` (temporary) or remove swap lines from `/etc/fstab`

#### 🟡 Encrypt the Disk (if swap cannot be disabled)
If swap cannot be disabled, full-disk encryption ensures that even data paged to swap remains inaccessible without the boot key.
- **Windows:** **VeraCrypt** (recommended) — open source, publicly audited, no cloud key escrow
- **macOS:** FileVault 2
- **Linux:** LUKS with dm-crypt

> ⚠️ **Why not BitLocker?** BitLocker is closed source and cannot be independently audited. By default, Windows uploads the recovery key to the user's Microsoft account — on third-party servers outside the user's control. Microsoft is subject to US legislation (FISA, NSL) which can compel the handover of encryption keys with legally-imposed secrecy obligations toward the end user. VeraCrypt has undergone multiple independent public audits, requires no account, uses no cloud, and stores no key material on external servers. The choice is the user's — but these are the facts.

#### 🟡 Securely Delete Original Files
After creating a `.bca` archive, the original unencrypted files should be deleted with **multi-pass secure overwrite**, not just moved to the Recycle Bin.
- **Windows:** Eraser (Gutmann 35-pass or DoD 5220.22-M algorithm)
- **macOS:** `rm -P filename` or Permanent Eraser
- **Linux:** `shred -vuz -n 35 filename` (Gutmann) or `wipe`, or via `peazip`

> ⚠️ On SSD/NVMe drives, overwrite-based secure deletion is less reliable due to wear leveling and internal remapping. The drive firmware may retain copies of "overwritten" blocks in remapped sectors. Full-disk encryption is the primary protection for SSDs. If encryption is not available, free-space wiping covers the entire disk at the cost of significant write amplification and accelerated drive wear.

---

## 🛡️ Security Architecture

### XSS Protection

BastetCipher implements **three independent layers** of XSS defence:

#### Layer 1 — Content Security Policy
```html
<meta http-equiv="Content-Security-Policy" content="
  default-src  'none';
  script-src   'self' 'unsafe-inline';
  style-src    'self' 'unsafe-inline' data:;
  img-src      'self' data:;
  font-src     'self' data:;
  media-src    data:;
  object-src   data:;
  connect-src  'none';
  frame-src    blob:;
  worker-src   'none';
  base-uri     'none';
  form-action  'none';
">
```

- `default-src 'none'` blocks everything not explicitly permitted
- `connect-src 'none'` prevents data exfiltration via `fetch` or `XMLHttpRequest` even if code were somehow injected
- `frame-src blob:` permits the vault viewer's BlobURL iframe while blocking all external frames
- `base-uri 'none'` prevents `<base>` tag hijacking
- `form-action 'none'` prevents form submission redirects

#### Layer 2 — `escapeHTML()` Utility
```js
function escapeHTML(str) {
  return String(str)
    .replace(/&/g,  '&amp;')
    .replace(/</g,  '&lt;')
    .replace(/>/g,  '&gt;')
    .replace(/"/g,  '&quot;')
    .replace(/'/g,  '&#x27;');
}
```

All five dangerous HTML characters are escaped. Applied as a defensive backstop on any value that could theoretically reach a DOM injection point.

#### Layer 3 — Zero `innerHTML` from User Data
All user-derived values that appear in the DOM are set via `textContent`, `createTextNode`, or `createElement` + `appendChild`. `textContent` is incapable of HTML parsing. A phrase of `<script>alert(1)</script>` displays as literal text — never executes.

---

### Content Security Policy

The only reason `'unsafe-inline'` is present in `script-src` and `style-src` is that the entire application is a single inline HTML file. In a server deployment context, these could be replaced with hash-based allowlisting for even stricter enforcement.

---

### Determinism Guarantee

BastetCipher makes a hard contract: **same inputs always produce the same output**.

1. All hash functions (SHA-256/384/512, PBKDF2) are deterministic by definition
2. All pseudo-random operations use seeded LCGs — no `Math.random()`, no `Date`, no `performance.now()`
3. The Web Crypto API is deterministic for all operations used (digest, deriveBits)
4. No mutable global state affects the pipeline
5. String concatenation order is fixed and documented
6. The Amplifier uses a seeded LCG; same seed → same N-character sequence, always

---

## 🎬 Animations & Visual Detail

| Animation | Implementation | Trigger |
|---|---|---|
| Sand particles | Canvas `requestAnimationFrame` loop, 80 particles | Continuous |
| Torch flames (4 layers) | CSS `@keyframes` on each SVG ellipse | Continuous |
| Ember sparks | CSS `@keyframes` on positioned `div` elements (4 per torch) | Continuous |
| Torch glow halos | CSS `@keyframes torchFlicker` | Continuous |
| Bastet eyes | JS `requestAnimationFrame` HSL cycle (5 colours) | Continuous |
| Bastet blink | SVG `<animate>` on eyelid path, double-blink pattern, 8s loop | Continuous |
| Bastet tail | SVG `<animateTransform>` slow rotation around base point, 7s | Continuous |
| Bastet halo rings | SVG `<animate>` on halo radius and opacity, 4s | Continuous |
| Cipher wheel | CSS `animation: wheelSpin 20s linear infinite` | Continuous |
| Cipher wheel fast | CSS `.spinning` class swap → `1s` | On generate |
| Background pyramid pulse | CSS `@keyframes pyramidPulse` | Continuous |
| Pyramid intensity | CSS `.active` class swap | On generate |
| Title shimmer | CSS `@keyframes titleShimmer` | Continuous |
| Tagline fade | CSS `@keyframes taglineFade` | Continuous |
| Wall glyph flicker | CSS `@keyframes runeFlicker` | Continuous |
| Rune display scramble | JS `setInterval` 80ms | On generate |
| Rune burst explosion | 14 DOM elements, CSS `@keyframes runeBurstAnim` | On click + complete |
| Altar border bands | CSS `@keyframes bandScroll` | Continuous |
| Altar glow pulse | CSS `@keyframes altarGlow` | Continuous |
| Eye orbs activate | CSS `.active` class + `@keyframes eyePulse` | On generate |
| Lock bounce | CSS `@keyframes lockBounce` | On complete |
| Progress bar shimmer | CSS `@keyframes progressShimmer` | On generate |
| Button shimmer stripe | CSS `@keyframes shimmerSlide` | Continuous |
| Output typewriter | JS `setInterval` 18ms chunk reveal | On complete |
| Output fade-in | CSS `@keyframes fadeInUp` | On complete |
| Corner ornament pulse | CSS `@keyframes cornerGlow` | Continuous |
| Copy button flash | CSS `.copied` class transition | On copy |
| Vault section glow | CSS `@keyframes vaultGlow` — emerald pulse | Continuous |
| Vault corner ornaments | CSS `@keyframes vaultCorner` — emerald flash | Continuous |
| Vault emerald band | CSS `@keyframes bandScroll` (10s, emerald colours) | Continuous |
| Vault action button flow | CSS `@keyframes vaultBtnFlow` — gradient slide | Continuous |
| Vault drop zone glyph | CSS `@keyframes glyphDrift` — float up/down | Continuous |
| Vault tech card appear | CSS `@keyframes cardAppear` — fade up on load | On overlay open |
| Welcome overlay fade | CSS `@keyframes overlayFadeIn`, `scrollReveal` | On first open |
| Welcome overlay border | CSS `@keyframes borderRotate` — conic gradient spin | On overlay open |
| Welcome particles | CSS `@keyframes scrollParticleFloat` — 5 gold particles | On overlay open |
| Welcome guarantee pills | CSS `@keyframes pillPulse` — glow cycle | On overlay open |
| Welcome enter button | CSS `@keyframes btnGoldFlow` — gold gradient slide | On overlay open |
| Security notice pulse | CSS `@keyframes noticePulse` — red glow | Continuous |

---

## 🏗️ Code Quality & Architecture

### Structure

```
BastetCipher.html
├── <head>
│   ├── CSP meta tag (strict)
│   ├── Viewport meta
│   ├── Favicon (data-URI SVG — Bastet bust)
│   └── <style> (~900 lines)
│       ├── CSS variables (:root)
│       ├── Background / chamber
│       ├── Particle canvas
│       ├── Wall glyphs
│       ├── Torch & flame animations (4 layers + embers)
│       ├── App layout / altar
│       ├── Form elements
│       ├── Button states + shimmer
│       ├── Output panel + typewriter
│       ├── Stats badges
│       ├── Welcome overlay + scroll + tech cards + guarantee pills
│       ├── Sacred Vault section (emerald theme)
│       │   ├── Vault tabs
│       │   ├── Drop zones
│       │   ├── File lists
│       │   ├── Vault action buttons
│       │   ├── Progress bars
│       │   ├── Algorithm pills
│       │   ├── File viewer overlay + iframe
│       │   └── Operational security notice + cards
│       └── Responsive breakpoints
├── <body>
│   ├── #chamber (radial gradient background)
│   ├── #particles-canvas (80-particle sand system)
│   ├── #bg-pyramid (SVG — 3 nested outlines + Eye of Ra)
│   ├── .wall-glyphs left/right (SVG — 13 glyphs per side + border lines)
│   ├── .torch.tl / .torch.tr (SVG flame layers + 4 ember divs each)
│   ├── #bastet-welcome-overlay (full-screen modal)
│   │   ├── 5 scroll particles
│   │   ├── Scroll top/bottom bands
│   │   ├── Scroll inner (header + tech grid + common text + enter button)
│   │   │   ├── Eye of Ra SVG
│   │   │   ├── 6 animated tech cards
│   │   │   ├── 5 guarantee pills
│   │   │   └── "Enter the Temple" button
│   └── #app
│       ├── <header> (Bastet SVG, title, tagline, divider runes)
│       └── <main id="altar">
│           ├── Cipher wheel SVG
│           ├── Bastet eye indicators + lock icon + rune display
│           ├── Ancient key SVG
│           ├── Input: secret phrase
│           ├── Input: PIM (+ note)
│           ├── Input: Entropic Amplifier (+ note)
│           ├── Error message
│           ├── Generate button
│           ├── Progress bar
│           └── Output section (tablet + stats badges + copy button)
│       ├── <section id="archive-vault">
│       │   ├── Vault band (top)
│       │   ├── Vault title row (icon + title + tagline)
│       │   ├── Tab buttons (Create / Extract / Open Virtual Vault)
│       │   ├── Panel: Create
│       │   │   ├── File drop zone
│       │   │   ├── File list
│       │   │   ├── Password input
│       │   │   ├── Create & Encrypt button
│       │   │   ├── Error / success messages
│       │   │   ├── Progress bar
│       │   │   └── Algorithm pills (7)
│       │   ├── Panel: Extract
│       │   │   ├── .bca drop zone
│       │   │   ├── Password input
│       │   │   ├── Decrypt & Extract button
│       │   │   ├── Error / success messages
│       │   │   ├── Progress bar
│       │   │   └── Algorithm pills (4)
│       │   ├── Panel: Open Virtual Vault
│       │   │   ├── .bca drop zone
│       │   │   ├── Password input
│       │   │   ├── Open Virtual Vault button
│       │   │   ├── Error / success messages
│       │   │   ├── Progress bar
│       │   │   ├── File list (scrollable, up to 320px)
│       │   │   ├── Close Vault & Destroy RAM button
│       │   │   └── Algorithm pills (5)
│       │   ├── Operational Security Notice
│       │   │   ├── Card: Disable Hibernation
│       │   │   ├── Card: Disable Swap
│       │   │   ├── Card: Encrypt Disk (+ BitLocker warning)
│       │   │   └── Card: Secure File Deletion
│       │   └── Vault band (bottom)
│       ├── #vault-viewer-overlay (fixed, full-screen file viewer)
│       │   ├── Header (icon + filename + info + close button)
│       │   ├── Sandboxed iframe
│       │   └── Security status bar
│       └── <footer>
└── <script> (~950 lines)
    ├── escapeHTML()                  — XSS utility
    ├── initParticles()               — Canvas animation loop (IIFE)
    ├── spawnRuneBursts()             — 14-glyph DOM burst effect
    ├── startRuneAnimation()          — 80ms hieroglyph scramble
    ├── stopRuneAnimation()
    ├── encode() / bufToHex()         — Crypto encoding utilities
    ├── sha256() / sha384() / sha512()— Web Crypto wrappers
    ├── pbkdf2()                      — PBKDF2-HMAC-SHA512 wrapper
    ├── transformHash()               — 4-stage proprietary transform
    ├── createPRNG()                  — Seeded LCG factory
    ├── insertSpecialChars()          — Deterministic special char injection
    ├── applyMixedCase()              — 50/50 case via seeded Fisher-Yates
    ├── generateAmplification()       — Entropic Amplifier (NEW)
    ├── runCipherPipeline()           — 9-step orchestrator
    ├── generateCipher()              — UI handler + animation trigger
    ├── copyCipher()                  — Clipboard API + textarea fallback
    ├── animateBastetEyes()           — rAF eye glow loop (IIFE)
    ├── keydown listener              — Enter key support
    ├── PIM validation listener       — 32-digit cap + leading zero strip
    ├── Amplifier validation listener — 0–9999 clamp + non-numeric strip
    ├── ── VAULT MODULE ──
    ├── BCA_MAGIC / BCA_VERSION / BCA_ITERS — constants
    ├── vConcat()                     — Uint8Array concatenation
    ├── vU16() / vU32()               — Little-endian integer encoders
    ├── initCRC() / crc32V()          — CRC32 lookup table + computation
    ├── vCompress()                   — deflate-raw via CompressionStream
    ├── vDecompress()                 — deflate-raw via DecompressionStream
    ├── deriveVaultKeys()             — PBKDF2 → k1 (GCM) + k2 (CBC)
    ├── vFmtSize()                    — Human-readable file size
    ├── buildBCA()                    — Full archive creation pipeline
    ├── parseBCA()                    — Full archive decryption pipeline
    ├── buildZipFromEntries()         — ZIP assembly from decrypted entries
    ├── vaultDownload()               — BlobURL download trigger
    ├── vaultState                    — Create/extract UI state object
    ├── vaultBrowseState              — Browse UI state object
    ├── vaultSwitchTab()              — Tab panel toggle
    ├── vaultAddFiles()               — File queue management
    ├── vaultRenderFileList()         — Create-tab file list rendering
    ├── vaultShowMsg()                — Error / success message display
    ├── vaultSetProg() / vaultEndProg()— Progress bar control
    ├── vaultCreateArchive()          — Create tab: full pipeline trigger
    ├── vaultExtractArchive()         — Extract tab: full pipeline trigger
    ├── initVaultUI()                 — Drop zone event bindings (IIFE)
    ├── vaultLoadBCA()                — Extract tab: BCA file loader
    ├── vaultLoadBrowseBCA()          — Browse tab: BCA file loader
    ├── vaultBrowseSetProg()          — Browse tab: progress bar control
    ├── vaultBrowseShowMsg()          — Browse tab: message display
    ├── vaultOpenVault()              — Browse tab: decrypt & render list
    ├── vaultBrowseRenderList()       — Browse tab: file list rendering
    ├── vaultFileIcon()               — Extension → hieroglyph icon map
    ├── vaultMime()                   — Extension → MIME type map
    ├── uint8ToBase64()               — Chunked base64 encoder
    ├── buildSrcdoc()                 — In-memory viewer HTML generator
    ├── vaultOpenFile()               — Decompress + open file in viewer
    ├── vaultCloseViewer()            — Close viewer + revoke BlobURL
    └── vaultCloseVault()             — Close vault + zero all RAM
```

---

## 🌐 Browser Compatibility

BastetCipher requires a browser that supports:
- `window.crypto.subtle` (Web Crypto API — `digest`, `deriveBits`, `encrypt`, `decrypt`, `importKey`)
- `CompressionStream` / `DecompressionStream` (deflate-raw — for the vault)
- `ReadableStream` / `WritableStream` (Streams API — for the vault)

| Browser | Minimum Version | Notes |
|---|---|---|
| Chrome / Edge | 80+ | Full support (CompressionStream requires 80+) |
| Firefox | 113+ | CompressionStream added in 113 |
| Safari | 16.4+ | CompressionStream added in 16.4 |
| Opera | 67+ | Full support |
| iOS Safari | 16.4+ | Full support |
| Android Chrome | 80+ | Full support |

> **Note:** The Web Crypto API requires a **secure context** (HTTPS or `localhost`). Opening the file directly via `file://` works in most browsers but may be blocked in some strict configurations. If you encounter issues, serve the file via a local web server.

```bash
python3 -m http.server 8080
npx serve .
php -S localhost:8080
```

---

## 📖 How to Use

### Cipher Generator — Basic Usage

1. Open `BastetCipher.html` in your browser
2. Read (or dismiss) the welcome overlay — it explains the system architecture
3. Type your **secret phrase** into the first field
4. Enter your **PIM** (or keep the default `563519`)
5. Optionally set the **Entropic Amplifier** (0–9999) to extend the cipher
6. Click **Generate Cipher** or press **Enter**
7. Watch the temple come alive
8. Your cipher appears on the stone tablet — click **Copy to Clipboard**

### Sacred Vault — Creating an Archive

1. Click the **Sacred Vault** section below the main altar
2. Select the **Create Archive** tab
3. Drag files onto the drop zone (or click to browse) — up to 1,024 files
4. Enter a strong password
5. Click **Create and Encrypt .bca Archive**
6. The `.bca` file is automatically downloaded

### Sacred Vault — Extracting an Archive

1. Select the **Extract Archive** tab
2. Drop your `.bca` file onto the drop zone
3. Enter the archive password
4. Click **Decrypt and Extract → .zip**
5. A standard ZIP file is downloaded containing all original files

### Sacred Vault — Browsing In-Memory (No Disk Write)

1. Select the **Open Virtual Vault** tab
2. Drop your `.bca` file onto the drop zone
3. Enter the archive password
4. Click **Open Virtual Vault — In Memory Only**
5. Browse the file list; click **Open** to view any file in the built-in viewer
6. When done, click **Close Vault and Destroy Data from RAM** — all decrypted data is zeroed

### Important Security Rules

> ⚠️ **The same phrase + same PIM + same amplifier always produces the same cipher.**  
> ⚠️ **A different PIM produces a completely different cipher — there is no recovery path.**  
> ⚠️ **Store your PIM separately from your phrase.**  
> ⚠️ **There is no server, no database, no recovery mechanism. The cipher is purely computational.**  
> ⚠️ **The vault password is separate from the cipher PIM — they are independent secrets.**  
> ⚠️ **If you forget your vault password, the archive cannot be recovered. There is no backdoor.**

---

## 📁 Project Structure

```
BastetCipher/
├── BastetCipher.html    ← The entire application (single file, ~1,700 lines)
└── README.md            ← This document
```

That's it. Two files. Everything — cipher engine, file vault, in-memory browser, animated temple, operational security guide — is inside one self-contained HTML file.

---

## 🤔 Why One File?

Because a cryptographic tool that requires an `npm install` is a cryptographic tool with a supply-chain attack surface.

BastetCipher has:
- **Zero npm dependencies** — no `node_modules`, no lockfile, no CVEs hiding in transitive deps
- **Zero CDN requests** — no third-party scripts that could be compromised or unavailable
- **Zero build step** — no webpack, no Babel, no transpilation, nothing to go wrong
- **Zero network surface** — the CSP explicitly blocks all outbound connections at the browser level

You can audit every single byte of this application by reading one file. You can clone it, copy it, put it on a USB stick, email it, and it will work identically in every context.

---

## ❓ FAQ

**Q: Can two different phrases with the same PIM produce the same cipher?**  
A: Cryptographically negligible. The salt alone is `SHA256(phrase + pim + ...)` — a collision would require a SHA-256 preimage attack.

**Q: Does the Entropic Amplifier make the cipher stronger?**  
A: It makes the cipher *longer*, which increases the effective keyspace for any system that uses the cipher as a key or password. The amplifier extension is as strong as the base cipher it is seeded from — it does not add independent hardness, but it does add more material derived from the same cryptographic foundation.

**Q: If I change the amplifier value, does the base cipher change?**  
A: No. The base cipher (Steps 1–7b) is computed identically regardless of the amplifier value. The amplifier only appends characters; it does not modify what came before. Changing the amplifier value changes the appended extension while the base remains identical.

**Q: Can I use the Sacred Vault offline?**  
A: Yes. Like everything in BastetCipher, the vault operates entirely locally. The `CompressionStream` and `crypto.subtle` APIs are native browser APIs — no external libraries are used.

**Q: What happens if I enter the wrong vault password?**  
A: The AES-GCM authentication tag will fail to verify, and decryption will throw an error immediately. No partial output is produced. The error message says "Wrong password or corrupted file" — no information is leaked about how close the password was.

**Q: Is the `.bca` format future-proof?**  
A: The format includes a version byte (currently `0x01`) and stores the PBKDF2 iteration count explicitly inside the file. Future versions can increment the version byte and change parameters without breaking compatibility with existing archives.

**Q: Is this suitable for password hashing (storing passwords)?**  
A: BastetCipher generates deterministic cipher strings, not one-way hashes for storage comparison. For password *storage*, use Argon2id or bcrypt — algorithms designed to be non-reversible and resistant to precomputation.

**Q: Why not Argon2 for the vault?**  
A: Argon2 is not available in the Web Crypto API. PBKDF2-HMAC-SHA512 at 200,000 iterations is the strongest available primitive in the browser's native crypto engine — and it is what VeraCrypt, 1Password, and iOS Keychain use for their master key derivation.

**Q: Can I change the PEPPER?**  
A: Yes, but doing so will change all cipher outputs for all phrase+PIM combinations. The PEPPER is an application-level secret embedded in the source. If you fork this project, generate your own pepper.

**Q: Is the output URL-safe?**  
A: The cipher contains characters from `[0-9a-zA-Z!@#$%^&*_\-+=~?.,]`. The `@`, `#`, `%`, `&`, `+`, `=`, `?`, and `#` characters may need URL encoding if used in a query string.

**Q: Can I verify the output independently?**  
A: Yes. The pipeline is fully documented above. You can reproduce the same output in any language that supports SHA-256, SHA-384, SHA-512, and PBKDF2-HMAC-SHA512 — as long as you replicate the exact string concatenation order, the `transformHash` logic, and the seeded LCG parameters (`a=1664525, c=1013904223, m=2^32`).

**Q: Why does the viewer have its own CSP inside the iframe?**  
A: Defence in depth. Even if an attacker crafted a `.bca` file containing a malicious HTML file designed to exfiltrate data, the viewer's srcdoc CSP (`connect-src 'none'`, `script-src 'none'` for non-HTML files) prevents any network requests or cookie access from inside the viewer frame.

**Q: What does the CRC32 actually protect against?**  
A: Archive corruption during storage or transmission. If a single bit of the `.bca` file is flipped, the AES-GCM authentication tag will almost certainly fail first (since GCM covers the entire ciphertext). The CRC32 provides a secondary check at the per-file level after decryption and decompression, catching edge cases where decompression silently produces wrong-length output. It is not a cryptographic integrity guarantee — the GCM tag is.

---

## 📄 License

```
MIT License

Copyright (c) 2026 - zdarkblow

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

<div align="center">

```
𓃠 𓂀 𓆣 𓇯 𓋹 𓊹 𓁹 𓃠 𓂀 𓆣 𓇯 𓋹 𓊹 𓁹 𓃠 𓂀 𓆣
```

**BastetCipher** — *Where ancient wisdom meets modern cryptography.*

</div>
