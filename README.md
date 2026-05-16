# Running Ledger

Public verification index for the running ledger signed by the OpenPGP key below.

```text
Holder:      Joseph R. Goydish II
Fingerprint: 4A04 1F50 6D89 4F5E E391 7438 6487 8B56 A2EB 2D11
Updated:     2026-05-15 UTC
Scope:       Public anchor trail and ongoing work index
```

## Canonical Files

| File | Purpose |
| --- | --- |
| [`running-ledger.txt`](running-ledger.txt) | Canonical plain-text ledger |
| [`running-ledger.txt.asc`](running-ledger.txt.asc) | Detached OpenPGP signature |
| [`index.html`](index.html) | Human-readable browser view of the ledger |

Direct raw ledger URL:

```text
https://raw.githubusercontent.com/JGoyd/Running-Ledger/main/running-ledger.txt
```

## Verify

```powershell
gpg --keyserver hkps://keys.openpgp.org --recv-keys 4A041F506D894F5EE391743864878B56A2EB2D11
gpg --verify running-ledger.txt.asc running-ledger.txt
```

A valid OpenPGP signature verifies that `running-ledger.txt` was signed by the private key corresponding to the published fingerprint.

## Public Anchors

| Item | Component | Publication | CVSS | Reference |
| --- | --- | ---: | ---: | --- |
| CVE-2025-24085 | CoreMedia use-after-free | 2025-01-27 | 10.0 | [Public CVE record](https://nvd.nist.gov/vuln/detail/CVE-2025-24085) |
| CVE-2025-24201 | WebKit out-of-bounds write | 2025-03-11 | 10.0 | [Public CVE record](https://nvd.nist.gov/vuln/detail/CVE-2025-24201) |
| CVE-2025-31200 | CoreAudio memory corruption via audio decode | 2025-04-16 | 9.8 | [Public CVE record](https://nvd.nist.gov/vuln/detail/cve-2025-31200) |
| CVE-2025-31201 | Pointer Authentication bypass | 2025-04-16 | 9.8 | [Public CVE record](https://nvd.nist.gov/vuln/detail/CVE-2025-31201) |
| CVE-2025-43300 | ImageIO out-of-bounds write | 2025-08-20 | 10.0 | [Public CVE record](https://nvd.nist.gov/vuln/detail/CVE-2025-43300) |

## Work Log

<details open>
<summary><strong>2026 submissions and disclosures</strong></summary>

| Date | Venue | Entry |
| --- | --- | --- |
| 2026-03-24 | Taiwan / NCC | Taiwan Mobile infrastructure used as terminal node in relay mesh, NCC decision reference `11500091980`. SHA-256 `4530081B986C0C084863FFA3102823DDCC81CDE0D9C1DC0E1B28BE2BA70F2AD7` |
| 2026-04-08 | Microsoft MSRC | MSRC Case 112639, MIME type-confusion / Defender / Exchange Online attachment inspection bypass. SHA-256 `274B18C9D3851F41DF33EB32691F4E8E0B46C5B68D7AC2A13D2CDCDD6C7C7722` |
| 2026-04-28 | Slovakia / genpro.gov.sk | Complete-verification receipt, Tracking ID `260428070422263`. SHA-256 `84C410150FA89CF48433C19399449CADF7C75F32AACD377ECD14554991C36489` |
| 2026-04-30 | Lithuania / Panevezio OTNK skyrius | Submitted information added to criminal case file `01-1-03450-26`. SHA-256 `603409F4B01BFED46D22D7129EC22A1969F1A32921654B3559FEBBD4E62BC17D` |
| 2026-05-04 | EC / OLAF | Mandelson / Carbyne concealment disclosure, Ref `00Db00K8yP.!500Sk019RuGn`. SHA-256 `42F922168AFC25FD0AB6813F3782F16C8F1DA82365615B3FE8272964016371F7` |
| 2026-05-04 | Singapore / CPIB | Corruption Reporting Form submission, Tracking ID `69f824dfe5ef7daf3b78ccee`. SHA-256 `B0F4D9EED94BDC6D5C351296CC1949CA7D7106E0E8CFFA5B97DB54727608B137` |
| 2026-05-05 | DOJ / FARA Public | Karim Wade / Macky Sall / Epstein-funded lobby disclosure. SHA-256 `83EF754869D953DC808130334E07719EC1210FE28EED8E6479482A0CEBBDD925` |
| 2026-05-05 | Massachusetts AGO | MIT Media Lab / institutional governance complaint. SHA-256 `A797257A9FBD19EFEC4BDA2FB023597EAFABEA143A4D9E9EBE8996F1B302CF62` |
| 2026-05-06 | IRS | Form 211 under IRC 7623(b), Southern Trust / Financial Trust / Epstein Estate. SHA-256 `653F9D1F3497C51C955A82EF1E1B2C36782468A9EB813104FADD8D72D0C6764F` |
| 2026-05-06 | SEC | TCR submission `17780-976-067-126` |
| 2026-05-11 | FCA | Bank of China (UK) Limited advisory and acknowledgement, Case Ref `212278528`. SHA-256 `5B77C1CE4B348B065D736D2E8B15F6015CBB2E434514511E18F35DC306127C4E` |
| 2026-05-13 | Japan / ISA | ICRRA Article 70-1 visa-fraud referral. SHA-256 `1D4CA44C8DF651E89119E621ECE12BA48E41FB928BFD82D12474F8DF4916ECBC` |

</details>

<details>
<summary><strong>2025 disclosures and certifications</strong></summary>

| Date | Venue | Entry |
| --- | --- | --- |
| 2025-04-22 | NASA | TLS certificate-chain misconfiguration disclosure for `webhosting-external.jpl.nasa.gov`. SHA-256 `C3EDEDB6E86187484BC0F86E0A046AF65DC316983F6EAA23E679DC888E4A25BC` |
| 2025-12-25 | Department of Energy / NNSA | DOE-417 electric emergency incident and disturbance report. SHA-256 `D203750DDB657BD350B69343F36BF0C9364378004D508E5572347760C38743C2` |
| 2025-03-18 | CNVD | CNVD-2025-06744, Apple iOS / iPadOS buffer overflow, `CNVD-YCGO-202503023656`. SHA-256 `352A56FF1319E1B8138B1F4C6F55B652CF09CCD8C6784610E3A3EF6A9A80723C` |
| 2025-04-22 | CNVD | CNVD-2025-07885, Apple memory reuse, `CNVD-YCGO-202504012519`. SHA-256 `D5BB17D5A27EABD32D272173116C90F89F12CDD912A26969115007383A7F21C8` |

</details>

## Notes

- The plain-text ledger is canonical.
- Sensitive packet bodies are not published in this repository.
- This repository is a public verification pointer, not a key store, wallet, or credential store.
- Prior signed versions should be retained as historical artifacts when materially updated.
