# VBL — osrednja mapa hiše (vbl/)

Osrednja točka za VBL (Verification Before Assertion License) v tem repozitoriju: kanon-kopija s provenance, registri (§2 ∧ §5), zgodovino verige, preverjevalnim protokolom in zemljevidom razdelitve.

| Pot | Vsebina |
|---|---|
| canon/ | kanon-kopija živih vrat + PROVENANCE (izvor, blob SHA, datum izmere) |
| registers/ | REGISTER-NEIMENOVANIH.jsonl (§2) ∧ REGISTER-PADCEV.jsonl (§5) + pravila — append-only |
| history/ | lineage verige (§15) ∧ kazalec na komit-zgodovino pri viru |
| implementation/ | kontrolni seznam preverjanja — verify before assertion |
| REPO-MAP.md | kaj živi kje — brez tihega podvajanja |
| SHA256SUMS.txt | kontrolne vsote te mape (razen same sebe) |

Zakon te mape: vsaka trditev ⊢ nosi verbatim pričo; neznano ⚠, nikoli molk. Živa vrata so vedno najnovejša različica pri viru — AtmaOVictu/Atmavictu → LICENSE.md @main (§10); ta kanon-kopija je priča, ne vrata.
