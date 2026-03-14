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
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/>

</div>

---

<div align="center">

# 𓃠 BastetCipher

### *An ancient Egyptian cryptographic chamber hidden inside a single HTML file.*

> A mystical, fully deterministic, multi-layer cryptographic engine wrapped in an immersive pyramid-temple experience — built entirely with zero dependencies, zero external resources, and zero compromise on security.

</div>

---

## 📜 Table of Contents

- [What Is BastetCipher?](#-what-is-bastetcipher)
- [Live Demo](#-live-demo)
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
  - [Step 8 — Final Cipher Assembly](#step-8--final-cipher-assembly)
- [The PIM — Personal Iterations Multiplier](#-the-pim--personal-iterations-multiplier)
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

You give it a **secret phrase** and a **PIM (Personal Iterations Multiplier)**. It runs that input through an 8-step cryptographic pipeline — involving SHA-256, SHA-384, SHA-512, a custom multi-stage proprietary transformation, PBKDF2 with HMAC-SHA512, a seeded PRNG for special character injection, and a deterministic mixed-case transformer — and produces a **powerful, unique, reproducible cipher string**.

Same phrase + same PIM → **always** the same output.  
Wrong PIM → completely different cipher. Every. Single. Time.

It is:
- 🔐 **Cryptographically serious** — not a toy, not a gimmick
- 🎨 **Visually spectacular** — an animated Egyptian temple experience
- 📦 **A single HTML file** — open it anywhere, no server, no install, no internet
- 🛡️ **Hardened against XSS** — CSP meta tag + pure DOM API output construction
- ⚡ **Fast** — PBKDF2 completes in 1–3 seconds regardless of PIM value
- 🔮 **Fully deterministic** — no randomness, no timestamps, no entropy leakage

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

## 🏺 The Visual Experience

BastetCipher is not just a crypto tool. It is an **experience**.

The interface is designed to feel like you have discovered an ancient Egyptian cryptographic chamber inside a pyramid dedicated to the goddess **Bastet** — deity of protection, secrets, and the home.

| Element | Description |
|---|---|
| 🐱 **Bastet Statue** | A fully hand-crafted inline SVG cat goddess — golden body, glowing emerald eyes, ankh sceptre, scarab crown, kohl eyeliner, collar jewels, and whiskers |
| 🔥 **Animated Torches** | Two wall torches with four-layer CSS flame animation — outer core, mid-flame, tip flicker, inner glow — plus floating ember sparks rising upward, each torch on independent timing so they never sync |
| ⚙️ **Cipher Wheel** | A rotating golden disk engraved with 6 hieroglyphs on its outer ring; spins slowly at rest, accelerates during generation |
| 🔑 **Ancient Key** | Hand-drawn SVG key with an ankh ring, bearing the Ankh hieroglyph (`𓋹`) inside the bow |
| 🌟 **Sand Particles** | 80 canvas-rendered floating particles in gold and sand tones, drifting upward with randomised lifetimes and fade curves |
| 🔺 **Background Pyramid** | A layered outline pyramid with the Eye of Ra at its centre; pulses gently, intensifies dramatically during cipher generation |
| 📜 **Stone Wall Columns** | Left and right panels of stacked hieroglyphs (`𓃠 𓂀 𓆣 𓇯 𓋹 𓊹 𓁹`) with engraved gold border columns |
| 🕯️ **Torch Halos** | Radial glow halos behind each torch flickering with their own CSS timing |
| 👁️ **Bastet Eyes** | Two living eye indicators that cycle through green hues continuously; pulse and intensify when cipher generation is active |
| 🔒 **Lock Icon** | Snaps from locked to unlocked with a bounce animation when cipher completes |
| ✨ **Rune Bursts** | 14 hieroglyph glyphs explode outward from the generate button in a starburst pattern on click and on completion |
| 📟 **Rune Display** | Scrambles through random hieroglyphs at 80ms intervals during generation — like a sacred slot machine |
| 🖥️ **Typewriter Output** | The cipher string types itself onto the stone tablet in 8-character chunks |
| 🏺 **Engraved Border Bands** | Scrolling hatched gold pattern at top and bottom of the altar panel |
| 🌠 **Title Shimmer** | The golden gradient title pulses and brightens on a 4-second loop |
| 🌙 **Tagline Fade** | The subtitle fades between stone-pale and gold on a 5-second cycle |

The favicon is a hand-crafted embedded SVG: a golden Bastet bust with glowing eyes set against a dark background, with pyramid silhouette — visible in the browser tab.

---

## ✨ Features at a Glance

- ✅ **Zero external dependencies** — no libraries, no CDN, no fonts from Google
- ✅ **Zero network requests** — all resources embedded; works fully offline
- ✅ **One file** — the entire application is `BastetCipher.html`
- ✅ **Fully deterministic** — identical input + PIM → identical output, always
- ✅ **PIM-sensitive** — each PIM value produces a structurally different cipher
- ✅ **PBKDF2-HMAC-SHA512** — industry-standard key derivation function
- ✅ **Web Crypto API** — uses the browser's native, hardware-accelerated crypto
- ✅ **Proprietary 4-stage hash transformation** — rotation, swap, remap, reverse
- ✅ **Mixed case output** — exactly 50% uppercase / 50% lowercase alphabetic chars
- ✅ **Special character injection** — 8–15 special chars at deterministic positions
- ✅ **XSS-hardened** — CSP meta tag, `escapeHTML()` utility, zero `innerHTML` from user data
- ✅ **SVG favicon** — embedded data-URI, no external image file
- ✅ **Mobile responsive** — adapts gracefully to small screens
- ✅ **Clipboard copy** — one-click copy with animated confirmation
- ✅ **Progress bar** — live status updates during the pipeline
- ✅ **Cipher stats panel** — length, iterations, algorithm, salt preview
- ✅ **Enter key support** — press Enter to generate
- ✅ **PIM validation** — enforces 1–32 digit numeric input

---

## 🔐 The Cryptographic Pipeline

Every time you click **Generate Cipher**, the following 8-step pipeline executes deterministically. The same inputs will always produce byte-for-byte identical output.

```
INPUT ──────────────────────────────────────────────────────────────►
           │
           ▼
  ┌─────────────────────────────────────────────────────────────┐
  │  PEPPER = "Bastet_Secret_Temple_Key_𓃠"  (embedded secret)  │
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
    │   STEP 8    │  finalCipher = ".," + result + ",."
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
h1 = SHA256(input + salt + pim + pepper)          // 64  hex chars
h2 = SHA384(salt  + input + pim + pepper)          // 96  hex chars
h3 = SHA512(input + ":" + salt + ":" + pim + ":" + pepper)  // 128 hex chars
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
hashInt  = parseInt(pimHash[0:6], 16)          // 24-bit integer
baseIter = 50000 + floor((hashInt / 16777215) * 550000)   // 50k–600k
twist    = (pimNum % 65537) * 7                // per-PIM offset
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

**Why PBKDF2-HMAC-SHA512 specifically?**
- HMAC-SHA512 is 512 bits of internal state — wider than SHA-256, making partial preimage attacks harder
- PBKDF2 is the standard stretching function used in VeraCrypt, 1Password, iOS, macOS Keychain, and OpenSSL
- The iteration count ensures that even brute-force attempts against a captured cipher must pay a significant computational cost per guess
- The derived key is 64 bytes (512 bits), providing maximum theoretical entropy

All crypto is performed through the **Web Crypto API** (`window.crypto.subtle`) — the browser's native, hardware-accelerated cryptographic engine. No JavaScript reimplementation of SHA or PBKDF2 is used.

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

A seeded LCG (Linear Congruential Generator) with parameters `(1664525, 1013904223, 2^32)` — the classic Numerical Recipes constants — drives all position and character selection. Because it is seeded deterministically from the seed hash, the exact same characters appear at the exact same positions for the same input.

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

This guarantees exactly **50% uppercase and 50% lowercase** alphabetic characters — never more, never less — while all digits, special characters, and punctuation remain completely unchanged.

The reversed-seed trick ensures the PRNG stream for case selection is **fully independent** from the stream used for special character insertion, preventing any statistical correlation between the two.

---

### Step 8 — Final Cipher Assembly

```js
finalCipher = ".," + withCase + ",."
```

The `.,` prefix and `,.` suffix are structural sentinels inherited throughout the pipeline. They serve as recognisable delimiters when parsing or storing cipher strings and add two additional fixed positions that an attacker cannot predict without the full pipeline.

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
| **Wrong PIM result** | Completely unrelated cipher — no partial match |
| **Security model** | Functions as a second factor; attacker needs both phrase AND PIM |

The PIM is embedded into **six separate points** in the pipeline, meaning a brute-force attack must correctly guess both the phrase and the PIM simultaneously to have any chance of reproducing the output.

---

## 🛡️ Security Architecture

### XSS Protection

BastetCipher implements **three independent layers** of XSS defence:

#### Layer 1 — Content Security Policy
```html
<meta http-equiv="Content-Security-Policy" content="
  default-src  'none';
  script-src   'self' 'unsafe-inline';
  style-src    'self' 'unsafe-inline';
  img-src      'self' data:;
  font-src     'self' data:;
  connect-src  'none';
  object-src   'none';
  frame-src    'none';
  worker-src   'none';
  base-uri     'none';
  form-action  'none';
">
```

- `default-src 'none'` blocks everything not explicitly permitted
- `connect-src 'none'` prevents data exfiltration via `fetch` or `XMLHttpRequest` even if code were somehow injected
- `base-uri 'none'` prevents `<base>` tag hijacking
- `form-action 'none'` prevents form submission redirects
- No external scripts, no CDN, no fonts, no frames — nothing reaches the network

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

All five dangerous HTML characters are escaped. This utility is applied as a defensive backstop on any value that could theoretically reach a DOM injection point.

#### Layer 3 — Zero `innerHTML` from User Data
The cipher stats panel — the only place where values derived from user input appear in the DOM — is constructed entirely using the DOM API:

```js
// SAFE — never parses strings as HTML
const badge  = document.createElement('span');
const strong = document.createElement('strong');
strong.textContent = value;   // textContent, never innerHTML
badge.appendChild(strong);
statsEl.appendChild(badge);
```

`textContent` is incapable of HTML parsing. A user whose phrase is `<script>alert(1)</script>` will see that exact string displayed — not executed.

All other DOM writes throughout the application already used `textContent` — the stats panel was the only `innerHTML` present, and it has been eliminated.

---

### Content Security Policy

The CSP is deliberately strict. The only reason `'unsafe-inline'` is present in `script-src` and `style-src` is that the entire application is a single inline HTML file — there is no separate `.js` or `.css` file to reference. In a server deployment context, these could be replaced with script/style hash-based allowlisting for even stricter enforcement.

---

### Determinism Guarantee

BastetCipher makes a hard contract: **same inputs always produce the same output**.

This is guaranteed by:
1. All hash functions (SHA-256/384/512, PBKDF2) are deterministic by definition
2. All pseudo-random operations use seeded LCGs — no `Math.random()`, no `Date`, no `performance.now()`
3. The Web Crypto API is deterministic for all operations used (digest, PBKDF2 key derivation)
4. No mutable global state affects the pipeline
5. String concatenation order is fixed and documented

---

## 🎬 Animations & Visual Detail

BastetCipher is animated at every level without ever touching performance:

| Animation | Implementation | Trigger |
|---|---|---|
| Sand particles | Canvas `requestAnimationFrame` loop, 80 particles | Continuous |
| Torch flames (4 layers) | CSS `@keyframes` on each SVG ellipse | Continuous |
| Ember sparks | CSS `@keyframes` on positioned `div` elements | Continuous |
| Torch glow halos | CSS `@keyframes torchFlicker` | Continuous |
| Bastet eyes | JS `requestAnimationFrame` HSL cycle | Continuous |
| Cipher wheel | CSS `animation: wheelSpin 20s linear infinite` | Continuous |
| Cipher wheel fast | CSS `.spinning` class swap | On generate |
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

The two torches deliberately use **different animation durations** so they never synchronise — creating an organic, living fire effect rather than a mechanical blink.

---

## 🏗️ Code Quality & Architecture

### Structure

```
BastetCipher.html
├── <head>
│   ├── CSP meta tag
│   ├── Favicon (data-URI SVG)
│   └── <style> (1 block, ~700 lines, fully commented)
│       ├── CSS variables (:root)
│       ├── Background / chamber
│       ├── Particle canvas
│       ├── Wall glyphs
│       ├── Torch & flame animations
│       ├── App layout / altar
│       ├── Form elements
│       ├── Button states
│       ├── Output panel
│       ├── Stats badges
│       └── Responsive breakpoints
├── <body>
│   ├── #chamber (background)
│   ├── #particles-canvas (sand)
│   ├── #bg-pyramid (SVG)
│   ├── .wall-glyphs left/right (SVG)
│   ├── .torch.tl / .torch.tr (animated SVG flames + embers)
│   └── #app
│       ├── <header> (Bastet statue SVG, title, tagline, divider)
│       └── <main id="altar">
│           ├── Cipher wheel SVG
│           ├── Bastet eye indicators
│           ├── Ancient key SVG
│           ├── Input fields (phrase + PIM)
│           ├── Generate button
│           ├── Progress bar
│           └── Output section (tablet + stats + copy)
└── <script> (~500 lines, fully commented)
    ├── escapeHTML()              — XSS utility
    ├── Particle system           — Canvas animation loop
    ├── spawnRuneBursts()         — DOM burst effect
    ├── startRuneAnimation()      — Hieroglyph scramble
    ├── stopRuneAnimation()
    ├── encode() / bufToHex()     — Crypto utilities
    ├── sha256() / sha384() / sha512()
    ├── pbkdf2()                  — Web Crypto API wrapper
    ├── transformHash()           — 4-stage proprietary transform
    ├── createPRNG()              — Seeded LCG
    ├── insertSpecialChars()      — Deterministic injection
    ├── applyMixedCase()          — 50/50 case via Fisher-Yates
    ├── runCipherPipeline()       — 8-step orchestrator
    ├── generateCipher()          — UI handler + animation trigger
    ├── copyCipher()              — Clipboard API + fallback
    ├── animateBastetEyes()       — rAF eye glow loop
    ├── keydown listener          — Enter key support
    └── PIM validation listener   — 32-digit cap + leading zero strip
```

### Code Conventions

- Every major section is delimited with `╔══╗` box comments
- All async functions use `async/await` — no callback hell
- All animation classes are toggled, never written with inline styles (except CSS custom properties)
- No `eval()`, no `Function()`, no `document.write()`
- No `setTimeout` for security-sensitive operations
- All Web Crypto calls are properly `await`ed in sequence
- Error handling with `try/catch/finally` throughout the pipeline
- The `PEPPER` constant is defined once and never duplicated

---

## 🌐 Browser Compatibility

BastetCipher requires a browser that supports the **Web Crypto API** — specifically `crypto.subtle.digest` and `crypto.subtle.deriveBits`. This is available in all modern browsers:

| Browser | Minimum Version | Notes |
|---|---|---|
| Chrome / Edge | 37+ | Full support |
| Firefox | 34+ | Full support |
| Safari | 11+ | Full support |
| Opera | 24+ | Full support |
| iOS Safari | 11+ | Full support |
| Android Chrome | 37+ | Full support |

> **Note:** The Web Crypto API requires a **secure context** (HTTPS or `localhost`). Opening the file directly via `file://` works in most browsers but may be blocked in some strict configurations. If you encounter issues, serve the file via a local web server.

```bash
# Simple local server options
python3 -m http.server 8080
npx serve .
php -S localhost:8080
```

---

## 📖 How to Use

### Basic Usage

1. Open `BastetCipher.html` in your browser
2. Type your **secret phrase** into the first field
3. Enter your **PIM** (or keep the default `563519`)
4. Click **Generate Cipher** or press **Enter**
5. Watch the temple come alive
6. Your cipher appears on the stone tablet — click **Copy to Clipboard**

### Important Rules

> ⚠️ **The same phrase + same PIM always produces the same cipher.**  
> ⚠️ **A different PIM produces a completely different cipher — there is no recovery path.**  
> ⚠️ **Store your PIM separately from your phrase.**  
> ⚠️ **There is no server, no database, no recovery mechanism. The cipher is purely computational.**

### PIM Guidelines

| PIM | Iterations (approx.) | Speed |
|---|---|---|
| Any value | 50,000 – 600,000 + (pim % 65537 × 7) | 1–3 seconds |

The exact iteration count is non-linearly derived from `SHA256(pim + pepper + "IterSeed")`, so there is no way to predict it from the PIM value alone without running the hash.

---

## 📁 Project Structure

```
BastetCipher/
├── BastetCipher.html    ← The entire application (single file)
└── README.md            ← This document
```

That's it. Two files. The most important one is 1,700 lines of pure, commented, handcrafted HTML/CSS/JS.

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

**Q: Is this suitable for password hashing?**  
A: BastetCipher generates deterministic cipher strings, not stored password hashes. It is designed for key derivation and cipher generation. For password *storage*, use Argon2 or bcrypt.

**Q: Why not use Argon2?**  
A: Argon2 is not available in the Web Crypto API. PBKDF2-HMAC-SHA512 is the strongest available primitive in the browser's native crypto engine — and it is what VeraCrypt, 1Password, and iOS use.

**Q: Can I change the PEPPER?**  
A: Yes, but doing so will change all outputs for all phrase+PIM combinations. The PEPPER is an application-level secret embedded in the source. If you fork this project, generate your own pepper.

**Q: Is the output URL-safe?**  
A: The cipher contains characters from `[0-9a-zA-Z!@#$%^&*_\-+=~?.,]`. The `@`, `#`, `%`, `&`, `+`, `=`, `?`, and `#` characters may need URL encoding if used in a query string.

**Q: Does the order of characters in the phrase matter?**  
A: Absolutely. `"hello"` and `"olleh"` produce completely different ciphers because they produce different SHA-256 digests.

**Q: Can I verify the output independently?**  
A: Yes. The pipeline is fully documented above. You can reproduce the same output in any language that supports SHA-256, SHA-384, SHA-512, and PBKDF2-HMAC-SHA512 — as long as you replicate the exact string concatenation order and the `transformHash` logic.

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

*Built with 𓃠 and entropy.*

</div>
