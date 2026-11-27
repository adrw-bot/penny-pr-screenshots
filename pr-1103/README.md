# PR #1103 Taxprep Desktop mailing-address VM QA (CWM6639, Personal Taxprep 2025)

BEFORE = sidecar built from master 231cd4e09 ; AFTER = sidecar built from PR head a312396b9.
Fictional persona (firm Acme CPA LLC): Morgan Mailtestbefore/Mailtestafter + spouse Rowan Spousecheck. No SIN entered.
Full Windows desktop with taskbar; only the outer FreeRDP title frame is cropped.

| File | Shows |
|---|---|
| 01-before-done.png | BEFORE run tail: 39/41/222/420 rejected=True |
| 02-after-done.png | AFTER run tail: 39/41/222/420 rejected=False, taxpayer read-backs match |
| 03-before-taxpayer-mailing-and-same-as.png | BEFORE: Number/Apt empty, Province shows BC (unset default), same-as unanswered |
| 04-before-taxpayer-spouse-section.png | Spouse section; "spouse's address is different" unchecked |
| 05-before-spouse-return-id-address.png | Spouse return mailing = taxpayer copy (Toronto/BC) |
| 06-after-taxpayer-mailing-and-same-as.png | AFTER: 58 / 204 / ON / same-as Yes |
| 07-after-taxpayer-spouse-section.png | Spouse section; "spouse's address is different" unchecked |
| 08-after-spouse-return-id-address.png | Spouse return mailing = taxpayer copy (58/204/Toronto/ON) |
