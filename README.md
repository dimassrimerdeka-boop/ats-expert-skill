# ATS Expert Skill for Claude Code

Skill ini mengubah Claude Code CLI menjadi konsultan karir & ATS expert — bisa **buat CV ATS-friendly**, **analisa kekuatan CV**, dan **rekomendasikan lowongan kerja** yang sesuai profil.

## Fitur

- **Buat CV** — Format Plain Text atau LaTeX (siap compile di Overleaf)
- **Analisa CV** — ATS Score, AI filler detection, bullet quality check
- **Rekomendasi Lowongan** — Tier 1/2/3 berdasarkan profil kandidat

---

## Cara Install di Claude Code CLI

```bash
claude skill install https://github.com/dimassrimerdeka-boop/ats-expert-skill
```

Atau manual: copy folder `skills/ats-expert/` ke `~/.claude/skills/`

### Cara Pakai

Ketik di Claude Code CLI:

```
/ats-expert
```

Atau cukup bilang: `"buat CV"`, `"analisa CV saya"`, `"cari lowongan"`

### Trigger Otomatis

Skill aktif secara otomatis ketika kamu menyebut:
- `buat CV` / `bikin CV` / `buatkan resume`
- `analisa CV` / `cek CV` / `review CV`
- `cari lowongan` / `rekomendasikan pekerjaan`
- `ATS score` / `LaTeX CV` / `CV Overleaf`

---

## Cara Pasang di Claude Desktop

Skill ini tidak bisa diinstall langsung di Claude Desktop, tapi bisa dipakai lewat **Project Instructions**.

### Langkah-langkah:

1. Buka **Claude Desktop**
2. Klik **"New Project"**
3. Klik **"Set project instructions"** (ikon pensil)
4. Copy semua isi file [`claude-desktop-prompt.md`](./claude-desktop-prompt.md) dari repo ini
5. Paste ke kolom Project Instructions → klik **Save**

Setelah itu, di project tersebut kamu bisa langsung bilang:
- `"buat CV"` → mode buat CV otomatis
- `"analisa CV saya"` + paste CV → dapat ATS Score lengkap
- `"cari lowongan"` → rekomendasi lowongan Tier 1/2/3
