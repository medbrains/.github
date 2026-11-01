<p align="center">
  <img src="assets/logo.png" alt="MedBrains logo" width="88" height="88">
</p>

<h1 align="center">MedBrains</h1>

<p align="center"><strong>Software that runs a whole hospital. Free, forever.</strong><br>
One patient record across OPD, wards, lab, radiology, pharmacy and billing, built for ABDM, NHCX and UHI.</p>

<p align="center"><em>Every patient deserves safe care. Every hospital, big or small, deserves the tools to give it.<br>
Built with love for patients, for hospitals, and for well-made software.</em></p>

<p align="center">
  <a href="https://github.com/medbrains/medbrains/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Apache_2.0-0F62FE?style=for-the-badge" alt="License: Apache 2.0"></a>
  <img src="https://img.shields.io/badge/💚_Free-forever-24A148?style=for-the-badge" alt="Free forever">
  <img src="https://img.shields.io/badge/❤️_For-every_patient-DA1E28?style=for-the-badge" alt="For every patient">
  <img src="https://img.shields.io/badge/🏥_For-every_hospital-8A3FFC?style=for-the-badge" alt="For every hospital">
</p>

<p align="center">
  <a href="https://github.com/medbrains/medbrains">Source code</a> ·
  <a href="https://www.medbrains.in">Website</a> ·
  <a href="https://www.medbrains.in/pricing">Pricing</a> ·
  <a href="https://www.medbrains.in/partners">Partners</a> ·
  <a href="https://www.medbrains.in/sponsors">Sponsor</a> ·
  <a href="https://www.medbrains.in/blog">Blog</a> ·
  <a href="https://www.medbrains.in/#demo">Book a demo</a> ·
  <a href="mailto:hello@medbrains.in">hello@medbrains.in</a>
</p>

<p align="center">
  <img src="assets/banner.png" alt="MedBrains: OPD workstation, waiting-room token board and patient app" width="100%">
</p>

## Why it's free

- **The software and every update are free**, for every hospital and clinic, under the Apache 2.0 licence. No subscription, no charge per user.
- **Safety for everyone.** Every patient-safety check is free, never an upgrade.
- **Your data is yours.** A full export whenever you ask. We never sell clinical data.
- **How we earn:** only from optional implementation, training, hosting and support (AMC). See [pricing](https://www.medbrains.in/pricing).

## What MedBrains does

- **One patient, one record.** Registration with a duplicate check, so a patient never gets two UHIDs. The token, case sheet, orders, prescription, dispensing, bill and discharge summary all hang off that record.
- **Clinical safety in the software, not on paper.** Schedule H/H1/X and NDPS rules at the pharmacy counter, critical lab values alerted to the doctor, the WHO surgical safety checklist enforced in OT, and nursing risk scores (NEWS2, Braden, Morse).
- **The way hospitals get paid.** GST billing, insurance and TPA pre-authorisation with IRDAI's 1-hour and 3-hour clocks, and UPI, card, cash and payment links.
- **Every screen in the hospital.** Web workstations, native iOS and Android apps for staff and patients, waiting-room TV token boards and kiosks.
- **Your choice of hosting.** Our cloud or your own servers. Each hospital's data is kept separate in the database, with an audit trail of who saw what.

## Roadmap

| Area | Status |
|---|---|
| Registration, OPD, IPD, nursing, lab, radiology, pharmacy, billing | ✅ In use at a hospital in Tamil Nadu |
| Native staff and patient apps (SwiftUI, Jetpack Compose) | 🟡 Built; store release in progress |
| ABDM M1: ABHA create, verify, card, QR | 🟡 Built and tested against mocks; sandbox certification next |
| ABDM M2/M3: share and fetch health records with consent | 🟡 Built; conformance fixes to NRCeS FHIR profiles in progress |
| ABDM M4: facility (HFR) and professional (HPR) registries | 🔵 In progress |
| Scan & Share at the front desk | 🟡 Built; sandbox certification next |
| NHCX insurance claims (eligibility, pre-auth, claims, payments) | 🔵 In progress: protocol conformance fixes |
| UHI provider: in-person consultations, ambulance, blood bank | 🔵 In progress |
| SNOMED CT terminology and coded clinical records | 🔵 In progress; national extensions pending licence approval |
| DPDP Act 2023 tooling: consent register, rights requests, breach register | 🟡 Built; consent enforcement next |
| Public demo hospital | 🔵 In progress |
| Redesigned interface with specialty components (dental, eye, maternity, ICU, dialysis and more) | 🔵 Design in progress |
| IVF and assisted-reproduction module (ART Act) | ⚪ Planned |

✅ live · 🟡 built, not yet certified or released · 🔵 in progress · ⚪ planned

MedBrains is **not yet certified by NHA** for ABDM, NHCX or UHI production use. We say "built for" until certification is complete.

## Source code

The code is at **[medbrains/medbrains](https://github.com/medbrains/medbrains)**, licensed under **Apache 2.0**. Start with the [README](https://github.com/medbrains/medbrains#readme) and [CONTRIBUTING](https://github.com/medbrains/medbrains/blob/main/CONTRIBUTING.md). We are working towards recognition as a [Digital Public Good](https://digitalpublicgoods.net/).

## Get involved

We'd love to hear from **clinicians** (what slows you down?), **hospital administrators** (what does your HMS get wrong?) and **developers** (Rust, React, Swift, Kotlin). Open an [issue](https://github.com/medbrains/medbrains/issues) or write to hello@medbrains.in.

**Sponsor the work:** fund a feature every hospital gets, implementation at a charitable hospital, or a language. See [medbrains.in/sponsors](https://www.medbrains.in/sponsors).

**Install MedBrains for hospitals near you:** join the [partner programme](https://www.medbrains.in/partners).

<sub>"MedBrains" and its logo are trademarks of Domnic Amalan S and are not covered by the code licence. SNOMED CT is a registered trademark of SNOMED International.</sub>
