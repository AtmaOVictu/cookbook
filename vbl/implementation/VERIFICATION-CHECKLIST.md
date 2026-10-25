# VBL — kontrolni seznam preverjanja (verify before assertion)

- [ ] Identiteta artefakta: pot, različica, datum, velikost, SHA-256.
- [ ] UTF-8: strogo dekodiranje brez nadomestnih znakov (U+FFFD = padec stroja, §12).
- [ ] Round-trip: dekodiranje/ponovno kodiranje da identične bajte.
- [ ] Strojni zapis: različica, datum, predhodnik ∧ vezi skladni.
- [ ] Register: samo append-only, veljaven JSONL, dokazna polja popolna.
- [ ] HTML: loči `type=text/plain` vdelane podatke od izvedljive kode.
- [ ] JavaScript: sintaktična preverba ločeno od browser E2E.
- [ ] Browser E2E: označi NOT_VERIFIED, dokler predvajanje ni preverjeno v pravem brskalniku.
- [ ] Neodvisna ponovitev: drugi preverjevalec ponovi izmere (⟨ne⟩ peči sebe ⊢ KORENINA 3).
- [ ] Objavna veriga: preveri komit, tag, release, PR ∧ datume (§10).
- [ ] Pravna presoja: ločeno od tehničnih testov; izvršljivosti ne sklepaj iz besedila.
- [ ] Razlika med različicami: 2.x ∧ 10.x ne združuj brez dokazljivega mostu (§15).
