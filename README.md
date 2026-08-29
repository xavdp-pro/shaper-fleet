# shaper-fleet

The operator's fleet map: one `fleet.yml` naming the base, the catalogue and
every universe class repo at an **immutable tag**, plus the machine inventory.

PRA starts here and needs nothing else that is not derivable: clone this
repo, deploy base and catalogue at their tags, deploy each class per its
`governedBy` order, and every instance's data returns from its derivable R2
bucket (Rule 16). Instances never appear in this file — they are ledger rows.

Schema and laws (the `-dev` bypass, the promotion guard, federation for
sovereign forks): `SHAPER-OS-V1.13/docs/architecture/FLEET.md` — Rule 37.
