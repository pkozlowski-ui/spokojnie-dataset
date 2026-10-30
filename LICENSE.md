# spokojnie open dataset – licence notice

This dataset holds the published answers of the non-commercial project "spokojnie – czy to normalne?" (child
development 0–5, Poland): short answers and claims written in our own words in Polish, each linked to its source.
It is not medical advice and does not assess any individual child. In a life-threatening emergency call 112.

## Licences are per claim

There is no single licence for the whole file. Every claim, myth and short answer has a `license` field: the licence
of its strictest source in our source registry.

| `license` | Why | Licence text |
|---|---|---|
| `CC-BY-4.0` | sources under OGL v3.0, CC BY, public domain or Polish legal acts | https://creativecommons.org/licenses/by/4.0/ |
| `CC-BY-SA-4.0` | source under CC BY-SA 4.0 (gov.pl) | https://creativecommons.org/licenses/by-sa/4.0/ |
| `CC-BY-NC-4.0` | source allows non-commercial use only (szczepienia.pzh.gov.pl, nfz.gov.pl) | https://creativecommons.org/licenses/by-nc/4.0/ |
| `CC-BY-NC-SA-4.0` | source under CC BY-NC-SA 3.0 IGO (WHO publications) | https://creativecommons.org/licenses/by-nc-sa/4.0/ |

Reuse each record as a whole under all the licences it lists. Do not drop claims: removing the 'SOR / 112' or 'Do lekarza' panels changes the medical meaning of the answer.

Verbatim quotes (`quote`) are not covered by this dataset's licences; they are short quotations of the linked source under its own terms.

## Attribution

- Credit "spokojnie – czy to normalne?" with a link to the question page (`url`, or `path` on the project site).
- Keep the source link of every claim and the source's attribution text (`sources.<id>.attribution`).
- Content from nhs.uk: "Contains public sector information licensed under the Open Government Licence v3.0." Do not
  attribute our summaries to the NHS.
- No source endorses this project or its reuse. Do not use publishers' names or logos to suggest endorsement.
- Say that you changed the text if you did.

Schema: `records.schema.json`. The same file is served at https://spokojnierodzice.pl/data/records.json.
