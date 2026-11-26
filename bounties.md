---
title: "Bounty watch: machine-found leads"
---

# Bounty watch

A cron job on a VPS polls GitHub every 30 minutes for issues that name an amount, then filters out the shapes that burned earlier attempts. This is the raw lead list, not a recommendation: most of it is noise from automated posters.

Last sync: 2026-11-26 15:59 UTC+8

| Repo | Issue | First seen |
| --- | --- | --- |
| bad-antics/lateralus-lang | [examples/ports: Collatz hailstone port 鈥?100k steps, identical vectors, 70.8x fa...](https://github.com/bad-antics/lateralus-lang/pull/984) | 2026-11-25 07:37:02 |
| zhangjiayang6835-cyber/bounty-plaza | [[Bounty] ($75) perf/fix: Align Fiat-Shamir challenge domain separator across mul...](https://github.com/zhangjiayang6835-cyber/bounty-plaza/issues/4398) | 2026-11-24 23:39:11 |
| Ayush441-python/AUREN | [[Bug Bounty] /risk classifies USDC-USD/PYUSD-USD stablecoin pairs as Crypto 鈥?10...](https://github.com/Ayush441-python/AUREN/issues/297) | 2026-11-24 14:55:06 |
| paraspell/xcm-tools | [[Bug bounty] AssetHubPolkadot 鈫?Ajuna: USDt/USDC transfers built with default op...](https://github.com/paraspell/xcm-tools/issues/2638) | 2026-11-24 03:24:27 |
| Ayush441-python/AUREN | [[Maths & Bug Bounty] Raw "USDC" ticker collides with OTC penny stock US Data Cor...](https://github.com/Ayush441-python/AUREN/issues/217) | 2026-11-22 21:46:15 |
| IES-BoilerRoom/zk-plonk-transcript-verifier | [($75) perf/fix: Align Fiat-Shamir challenge domain separator across multi-proof ...](https://github.com/IES-BoilerRoom/zk-plonk-transcript-verifier/issues/2) | 2026-11-24 22:11:28 |
| IES-BoilerRoom/zk-plonk-transcript-verifier | [ci/plonk_kzg: Fix transcript chunk boundary check and grand-product coset shift ...](https://github.com/IES-BoilerRoom/zk-plonk-transcript-verifier/issues/1) | 2026-11-24 22:11:27 |
| IES-BoilerRoom/cpython-pep626-line-profiler | [fix(dwarf_trace): Preserve exact column-offset delta invariants across exception...](https://github.com/IES-BoilerRoom/cpython-pep626-line-profiler/issues/2) | 2026-11-24 22:11:26 |
| IES-BoilerRoom/cpython-pep626-line-profiler | [fix(dwarf_trace): Resolve trace frame ceiling off-by-one and PEP 626 instruction...](https://github.com/IES-BoilerRoom/cpython-pep626-line-profiler/issues/1) | 2026-11-24 22:11:25 |

## Why most of these are traps

An amount plus a `bounty` label is not evidence of payment. The filter above already drops the self-declared death sentences, but the surviving list still contains AI-generated mirrors that advertise a number while never reviewing a human pull request. The tell is in the body: `Automated CI`, `conformance mirror`, `not reviewed on this mirror`, or a settlement rail pointing at a platform that no longer pays.