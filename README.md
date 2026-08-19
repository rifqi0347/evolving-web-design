# Evolving Web Design

Skill **design intelligence** untuk AI coding assistant (Claude Code, ZCode, dll.) — menghasilkan website yang contemporary, distinctive, usable, dan bebas dari "AI-slop".

Skill ini **bukan kumpulan template**. Skill ini adalah sistem berpikir: cara memilih, mengeksplorasi, menggabungkan, menolak, dan mengembangkan solusi desain — khusus untuk setiap project.

## Apa yang dilakukan skill ini

Saat di-trigger oleh permintaan membuat/mendesain/redesign website, skill ini memaksa proses:

1. **Creative divergence** — eksplorasi minimal 3 arah desain konseptual berbeda sebelum implementasi
2. **Trend intelligence** — riset & dekomposisi tren (prinsip, bukan penampakan), klasifikasi lifecycle: emerging → rising → contemporary → saturated → cliché
3. **Originality engine** — reference sebagai bahan penelitian (bukan template), mutation, recontextualization, novel synthesis
4. **Project-specific Design DNA** — tidak ada "AI style"; style lahir dari brand + audience + content + context
5. **Anti-AI-slop defense** — detector card/gradient/glow/glass overuse, AI-Slop Score 0–100, Originality Score, trend bundle detector
6. **Multi-role critique** — art director, UX, motion, engineering, accessibility review sebelum finalisasi
7. **Design memory & anti-convergence** — belajar dari kegagalan, rotasi style, style reset, tidak mengulang solusi antar project
8. **Continuous evolution** — annual revalidation, current-year awareness, versioning & changelog (lihat Layer 3 di SKILL.md)

## Siapa yang membutuhkannya

- Developer yang sering meminta AI membuat landing page/portfolio/marketing site dan bosan dengan hasil generik yang mirip semua
- Desainer yang ingin AI bekerja dengan proses design thinking, bukan "prompt → template → done"
- Siapa pun yang menginginkan website *award-quality thinking* tanpa harus mendikte setiap keputusan

## Apa yang TIDAK dijanjikan

- Tidak menjamin desain "belum pernah dibuat manusia" — targetnya *novel synthesis*, bukan kemutlakan
- Tidak menggantikan review manusia — skill memperkaya proses, keputusan akhir tetap di Anda
- Tidak otomatis menghasilkan animasi berat/WebGL — teknologi dipakai hanya jika memberi value nyata

## Struktur skill

```
evolving-web-design/
└── SKILL.md          # Semua aturan skill
```

SKILL.md terdiri dari 4 bagian (semua lapisan bersifat **additive**):

| Bagian | Isi |
|---|---|
| **Core** | 40 aturan fondasi: never freeze design language, design evolution engine, originality levels, cross-pollination, motion identity, self-critique |
| **Layer 1 — Creative Evolution Upgrade** | 23 aturan: divergence wajib, design mutation, anti-repetition system, AI-Slop Score, Emerging/Originality Mode |
| **Layer 2 — Evolving Web Design Intelligence v3** | 105 aturan: counter-design, direction scoring, visual grammar, trend lifecycle, multi-role review, master creative algorithm, ultimate directive |
| **Layer 3 — Continuous Evolution & Living Skill System** | 40 aturan: living skill, annual revalidation, source hierarchy, versioning, changelog, anti-convergence override |

## Cara install

### Claude Code

Symlink/clone folder skill ke direktori skill user:

```bash
# Windows (Git Bash) — symlink ke ~/.agents/skills
ln -s "$(pwd)/evolving-web-design" ~/.agents/skills/evolving-web-design

# atau clone langsung
git clone https://github.com/rifqi0347/evolving-web-design.git
# lalu pindahkan/symlink folder evolving-web-design ke ~/.agents/skills/
```

### ZCode

ZCode otomatis menemukan skill di `~/.agents/skills/` (scope user) atau `.zcode/skills/` di workspace (scope project):

```bash
git clone https://github.com/rifqi0347/evolving-web-design.git /tmp/ewd
cp -r /tmp/ewd/evolving-web-design ~/.agents/skills/
```

Restart session, lalu verifikasi skill muncul di daftar available skills.

### Agent lain (generic)

Skill ini pada dasarnya instruction file. Cara universal: paste/append isi `SKILL.md` ke system prompt, AGENTS.md, atau skill system agent Anda.

## Cara penggunaan

Skill ter-trigger **otomatis** saat user meminta hal seperti:

- "buatkan website/landing page untuk ..."
- "redesign homepage ini"
- "buat portfolio yang unik / tidak seperti template"
- "buat desain modern / cutting-edge / anti AI-slop"

Contoh prompt:

```
Buatkan landing page untuk studio arsitek "Atelier Utara".
Gaya: tenang, presisi, photographic. Anti AI-slop.
```

```
Redesign portfolio ini supaya distinctive, jangan pakai
bento grid atau glassmorphism.
```

```
Buat website product AI monitoring dengan desain
cutting-edge 2026, tapi tetap usable.
```

Anda juga bisa memanggil eksplisit: `/evolving-web-design` (jika CLI mendukung slash-command untuk skill).

## Mode

Skill memilih kedalaman eksplorasi otomatis berdasarkan konteks (Layer 3, aturan #32):

| Mode | Kapan | Perilaku |
|---|---|---|
| **Stable** | utility UI, internal tool, CRUD sederhana | Tanpa riset trend, langsung ke solusi solid |
| **Current** | marketing site, SaaS, branding, e-commerce, portfolio | Riset landscape terkini + divergence + audit |
| **Frontier** | experimental, award-oriented, interactive art | Deep research + emerging tech + eksplorasi maksimal |

Bisa juga diminta manual: "pakai frontier mode".

## Update strategy

Skill ini dirancang sebagai **living skill** (Layer 3):

- **Annual revalidation**: setiap tahun evaluasi ulang tren, teknologi, AI-slop pattern; pertahankan prinsip, ganti yang usang
- **Core vs Evolving layer**: prinsip fundamental (clarity, usability, accessibility) stabil; aesthetic & tren diperbarui
- **Consolidation**: aturan yang redundant/outdated di-merge atau dibuang, bukan terus ditumpuk

## Versioning & changelog

Semantic versioning `MAJOR.MINOR.PATCH`:

- **MAJOR** — perubahan filosofi/arsitektur skill
- **MINOR** — penambahan capability baru
- **PATCH** — perbaikan kecil, typo, klarifikasi

### Changelog

#### v1.0.0 — 2026-08-19

- Initial release
- Core: 40 aturan fondasi (evolving design intelligence)
- Added: Layer 1 Creative Evolution Upgrade (23 aturan)
- Added: Layer 2 Evolving Web Design Intelligence v3 (105 aturan)
- Added: Layer 3 Continuous Evolution & Living Skill System (40 aturan)
- Added: README, versioning system, changelog

## Maintenance

Repository dikelola dengan loop (Layer 3, aturan #35):

```
Issue → Research → Proposal → Implementation → Testing → Changelog → Release
```

Kontribusi: buka issue dulu untuk perubahan philosophy; PR kecil (typo/klarifikasi) bisa langsung.

## Examples hasil yang diharapkan

| Input generik | Tanpa skill | Dengan skill |
|---|---|---|
| "buat landing page SaaS" | Dark background + purple gradient + glass cards + bento grid + fade-up | Direction-specific: mis. editorial light layout, product demo sebagai hero, motion system mengikuti brand, lolos AI-Slop audit |
| "buat portfolio" | Hero besar + grid card project | Signature element unik, mis. navigasi sebagai storytelling atau scroll narrative, dengan motion identity sendiri |

## Limitations

- Kualitas output tetap bergantung pada model AI yang menjalankan
- Riset trend real-time membutuhkan akses web; tanpa itu skill fallback ke internal knowledge + konservatisme trend-lifecycle
- Skill ini instruksi, bukan kode — tidak ada runtime/test otomatis
- Originality tinggi tidak selalu tepat: untuk banking/government/utility, skill dengan sengaja memilih clarity > novelty

## Lisensi

MIT — bebas dipakai, dimodifikasi, dan dikembangkan.
