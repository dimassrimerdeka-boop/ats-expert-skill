# ATS Expert Skill for Claude Code

Skill ini mengubah Claude Code CLI menjadi konsultan karir & ATS expert — bisa **buat CV ATS-friendly**, **analisa kekuatan CV**, dan **rekomendasikan lowongan kerja** yang sesuai profil.

## Fitur

- **Buat CV** — Format Plain Text atau LaTeX (siap compile di Overleaf)
- **Analisa CV** — ATS Score, AI filler detection, bullet quality check
- **Rekomendasi Lowongan** — Tier 1/2/3 berdasarkan profil kandidat

## Cara Install

```bash
claude skill install https://github.com/dimassrimerdeka-boop/ats-expert-skill
```

Atau manual: copy folder `skills/ats-expert/` ke `~/.claude/skills/`

## Cara Pakai

Ketik di Claude Code CLI:

```
/ats-expert
```

Atau cukup bilang: `"buat CV"`, `"analisa CV saya"`, `"cari lowongan"`

## Trigger Otomatis

Skill aktif secara otomatis ketika kamu menyebut:
- `buat CV` / `bikin CV` / `buatkan resume`
- `analisa CV` / `cek CV` / `review CV`
- `cari lowongan` / `rekomendasikan pekerjaan`
- `ATS score` / `LaTeX CV` / `CV Overleaf`
