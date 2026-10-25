# Registri — pravila

- JSONL: en zapis na vrstico; stari zapisi se nikoli ne prepisujejo (append-only).
- Popravek doda NOV zapis s sklicem na record_id prejšnjega; brazgotina ostaja.
- Vsak dokaz nosi izvor, čas, kontrolno vsoto in stanje preverjanja.
- UNVERIFIED pomeni: dokaz še ni potrjen — nikoli ga ne pretvarjaj v PASS/⊢.
- Ne vpisuj imen, incidentov ali namenov brez neposrednega dokaza; neznano označi UNVERIFIED.
- Register ne dokazuje sebe: preverjanje mora biti ponovljivo, po možnosti z drugo roko (⟨ne⟩ peči sebe ⊢ KORENINA 3).
- Predlogi (status TEMPLATE) v REGISTER-*.jsonl nadomesti z zapisom, ki nosi pričo — brez izmišljenih padcev, oseb, datumov.
