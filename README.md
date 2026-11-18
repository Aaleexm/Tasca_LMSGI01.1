# Tasca LMSGI01.1 — Alex Morro Calafell

Llenguatges de Marques i Sistemes de Gestió d'Informació (DAM).

| Exercici | Fitxer |
|---|---|
| 1.1 Correcció agenda | `ex1_1_agenda.xml` |
| 1.2 Correcció horari | `ex1_2_horari.xml` |
| 2 Catàleg de pel·lícules | `ex2_cataleg.xml` |
| 3 JSON → XML (tornei) | `ex3_tornei.xml` |
| 4 Inventari ampliat | `ex4_inventari.xml` |
| 5 Enquestes en JSON | `ex5_enquestes.json` |

`fragment1_1_original.xml` i `fragment1_2_original.xml` són els fragments de l'enunciat tal com venien (amb errors), per comparar.

## Com validar-los
- **Navegador**: obre qualsevol `.xml` amb Edge/Chrome/Opera. Si està ben format, es mostra l'arbre; si no, surt l'error de la línia.
- **Terminal** (Linux/Git Bash): `xmllint --noout fitxer.xml`
- **JSON**: `python -m json.tool ex5_enquestes.json` o un validador com jsonlint.com.
