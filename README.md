# Tuesday 24 November 2026 — 35 Dated Stories, 9 Regions, 14 Fields, 13 Vector Scenes, UTC Timeline & Date-Check Audit

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124/Dedypol22/news-image-20261124-entry/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Dedypol22/news-image-20261124-entry/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One page that sums up Tuesday 24 November 2026 in a single image: 35 dated
stories from 9 regions and 14 fields, every one dated. Three illustrated
lead stories — a Houthi drone hits Riyadh's tallest tower, Huang is back at
Nvidia, and hackers breach the CIA and ODNI's unclassified systems — plus
10 illustrated medium stories, a world map with numbered pins 1–13,
numbered briefs 14–35, a UTC timeline, and a DATE CHECK box that names the
big stories deliberately left out because they happened on another day.

## How to run

```sh
python3 main.py > entry.png        # writes the 1024x1024 PNG to stdout
python3 main.py /tmp/entry.png     # or: write to a path
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py   # or: write to <dir>/entry.png
```

`main.py` uses only the Python standard library. It decodes the embedded
base64 PNG, validates it strictly (PNG magic, IHDR exactly 1024x1024,
8-bit palette, CRC of every chunk, no trailing data after IEND, size
<= 1 MiB), then writes the bytes unchanged. It reads nothing from disk and
needs no network, so it runs identically from any working directory.

Verification: running `main.py` twice from a neutral `/tmp` working
directory produces byte-identical output (SHA-256
`6e9cefa92c984c4248b4297c1ad9c24291b727370f8c4e1aa302ca7a0b7db909`,
70,905 bytes, 1024x1024).

## The 35 stories

### Hero (1–3, illustrated large)

1. [MIDDLE EAST — TUE 24 NOV] **Houthi drone hits Riyadh's tallest tower** — Second Houthi strike in <1 week hits the 80-floor PIF Tower (Saudi wealth fund HQ, ~$1tn assets), 11 hurt; coalition vows firm response. First strike Thu 19 Nov broke windows, no casualties.
2. [NORTH AMERICA — MON 23 NOV] **Huang back at Nvidia** — Jensen Huang reinstated as CEO 11 days after resigning (12 Nov) after Trump intervention; shares +31.5% Mon, then −6% Tue; Congress to question Huang (3 Dec).
3. [NORTH AMERICA — TUE 24 NOV] **CIA & ODNI breached** — Hackers breach UNCLASSIFIED systems of CIA + Office of Director of National Intelligence, first reported by NYT; classified systems NOT affected, already fixed; culprit unknown; suspected tool "ARTEX".

### Medium (4–13, illustrated)

4. [NORTH AMERICA — TUE 24 NOV] **Huawei guilty 10 of 12** — Brooklyn jury convicts on 10 of 12 counts (fraud, sanctions, trade secrets); acquitted on RICO + obstruction; sentencing 14 Sep 2027.
5. [NORTH AMERICA — TUE 24 NOV] **Dow tops 50,000** — Dow +0.85% to 50,018.70, first close above 50k; S&P −0.50%; Nasdaq −1.48% as AI rally fades.
6. [NORTH AMERICA — TUE 24 NOV] **Trump readies new tariffs** — Section 301 probe into excess capacity at 16 partners incl. China + EU; findings + new tariffs expected Tue/Wed.
7. [MIDDLE EAST — TUE 24 NOV] **Israel kills Hamas security chief** — Airstrike kills Naeem Abu Nahel, Hamas internal security director, +6 others in western Gaza City, amid fragile ceasefire.
8. [AFRICA — TUE 24 NOV] **Senegal reinstated AFCON champions** — CAS unanimously restores Senegal as 2025 Africa Cup winners, overturning CAF; beat Morocco 1-0 in Jan 2026 final.
9. [ASIA — TUE 24 NOV] **China probes Politburo member** — Chen Jining, Shanghai party chief, under investigation; 4th member of top leadership probed since 2025.
10. [ASIA — TUE 24 NOV] **Sooryavanshi 204 off 53** — 15-year-old Vaibhav Sooryavanshi smashes fastest List A double hundred (204 off 53, 28 sixes); India A beat UAE by 7 wickets.
11. [MIDDLE EAST — TUE 24 NOV] **IRGC claims 3 tankers hit mines in Hormuz** — CLAIM: 6 tankers since Sun 22 Nov; no ship names/flags; CENTCOM silent.
12. [MIDDLE EAST — TUE 24 NOV] **US sanctions ~30 Iran-linked financial houses** — Treasury targets firms + executives in Iran's shadow banking system.
13. [EUROPE — TUE 24 NOV] **Gukesh holds Sindarov** — Defending champion draws Game 1 of the Classical World Chess Championship final vs Javokhir Sindarov, holding with black.

### Briefs (14–35, numbered)

14. [NORTH AMERICA — TUE 24 NOV] US consumer confidence 103.3 in Nov, up from Oct.
15. [EUROPE — TUE 24 NOV] Putin: Ukraine hits refineries despite Trump plea.
16. [EUROPE — TUE 24 NOV] Russia strikes Zaporizhzhia: 2 killed, 40+ wounded.
17. [EUROPE — MON 23 NOV] NATO vows space defence after REPORT of Russian "Sputnik-S" satellite.
18. [EUROPE — TUE 24 NOV] Sarkozy & Bruni to stand trial; witness-tampering case.
19. [EUROPE — MON 23 NOV] Brentford 4-0 Everton; Lewis-Potter scores twice.
20. [SOUTH AMERICA — MON 23 NOV] Car bomb wounds 23 in Colombia; blamed on FARC-EMC.
21. [CENTRAL AMERICA — TUE 24 NOV] Mexico tour bus overturns: 7 killed, 20+ hurt.
22. [CENTRAL AMERICA — TUE 24 NOV] Mexico inflation 3.96%, six-month high; core 3.68%.
23. [SOUTH AMERICA — TUE 24 NOV] US to launch new phase of Venezuela operations.
24. [CENTRAL AMERICA — MON 23 NOV] Women's World Cup 2031: USA, Mexico, Costa Rica, Jamaica.
25. [AFRICA — TUE 24 NOV reported] Congo plane missing; rebels CLAIM shoot-down (reported Tue).
26. [AFRICA — TUE 24 NOV] Nigeria king, 92, suspended after misconduct allegation.
27. [AFRICA — TUE 24 NOV] South Africa bowl Bangladesh out for 91; hosts 88/1.
28. [MIDDLE EAST — TUE 24 NOV] Rubio meets Qatar PM on Iran; Trump: no major operations.
29. [ASIA — TUE 24 NOV] Hanoi gas blast kills 6, 10 hurt, at restaurant.
30. [ASIA — TUE 24 NOV] Nepal quake 5.6 near Tibet border; felt to Dhaka.
31. [ASIA — TUE 24 NOV] Hasina PLANS return 16 Dec, ending 2+ years exile.
32. [ASIA — MON 23 NOV] 14 nations back ICJ Rohingya genocide ruling.
33. [ASIA — TUE 24 NOV] Malaysia to send back 6,803 Myanmar nationals in Dec.
34. [OCEANIA — TUE 24 NOV] Solomon Islands to replace China pact with Australia treaty.
35. [GLOBAL — TUE 24 NOV] UNAIDS: AIDS deaths lowest in 20 years (~570,000).

## Regions (9)

North America 6 · Central America 3 · South America 2 · Europe 5 ·
Africa 4 · Middle East 5 · Asia 6 · Oceania 1 · Global 3 (= 35)

## Fields (14)

Politics · War & Security · Diplomacy · Justice · Technology · Markets ·
Energy · Health · Sport · Science · Crime · Accidents · Migration · Media

## Date check — deliberately excluded (not 24 Nov)

- Shenzhou-24 launches — Wed 25 Nov
- Merkury sunk — Sun 22 Nov
- COP31 collapses with no deal — Sun 22 Nov
- Australia sweeps France 4-0, BJK Cup — Sun 22 Nov
- Alcaraz wins ATP Finals — Sun 22 Nov

## License

MIT — see [LICENSE](LICENSE).
