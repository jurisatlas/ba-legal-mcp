---
name: ba-legal-mcp-skill
description: Official Bosnia and Herzegovina (BA) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Bosnia and Herzegovina Legal Research & Multi-Tier Case Law Skill (`ba-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Bosnia and Herzegovina (BA)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `AP-123/23, 65 0 P 123456 23 Pž or Službeni glasnik BiH br. 10/24`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Općinski sudovi u FBiH (28 Municipal Courts), Osnovni sudovi u RS (19 Basic Courts), Okružni privredni sudovi u RS & Osnovni sud Brčko distrikta BiH
   - **Second Instance (Cantonal / Regional / Appellate):** 10 Kantonalnih sudova u FBiH (1. Unsko-sanski kanton — Kantonalni sud u Bihaću, 2. Posavski kanton — Kantonalni sud u Odžaku, 3. Tuzlanski kanton — Kantonalni sud u Tuzli, 4. Zeničko-dobojski kanton — Kantonalni sud u Zenici, 5. Bosansko-podrinjski kanton — Kantonalni sud u Goraždu, 6. Srednjobosanski kanton — Kantonalni sud u Novom Travniku, 7. Hercegovačko-neretvanski kanton — Kantonalni sud u Mostaru, 8. Zapadnohercegovački kanton — Kantonalni sud u Širokom Brijegu, 9. Kanton Sarajevo — Kantonalni sud u Sarajevu, 10. Kanton 10 — Kantonalni sud u Livnu), 6 Okružnih sudova u RS (Banja Luka, Bijeljina, Doboj, Istočno Sarajevo, Prijedor, Trebinje), Viši privredni sud u Banjoj Luci & Apelacioni sud Brčko distrikta BiH
   - **Supreme & Constitutional Instance:** Ustavni sud BiH, Sud Bosne i Hercegovine (State Court Appellate & Trial Divisions), Vrhovni sud Federacije BiH & Vrhovni sud Republike Srpske
   - **Primary Tiered Database:** VSTV BiH Centralna Baza Sudskih Odluka (sudskapraksa.pravosudje.ba / pravosudje.ba/csd) & Kantonalni/Okružni Sudski Portali (`https://sudskapraksa.pravosudje.ba`)
