# PLUSVein

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FPLUSVein-181717?logo=github)](https://github.com/biometric-community/PLUSVein)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.wavelab.at/sources/PLUSVein-FV3/)

**PLUSVein** — tbiom catalog packaging for `plusvein` (vein; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/PLUSVein
- **Upstream source**: https://www.wavelab.at/sources/PLUSVein-FV3/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `plusvein` |
| Category | `vein` |
| Access | `register` |
| Upstream homepage | https://www.wavelab.at/sources/PLUSVein-FV3/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: PLUSVein-FV3 and related PLUS vein sets.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/PLUSVein.git
cd PLUSVein
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_plusvein.sh
```

Place licensed archives under `projects/datasets/plusvein/` (gitignored).

## Dataset structure

```text
PLUSVein/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.wavelab.at/sources/PLUSVein-FV3/
- Packaging: https://github.com/biometric-community/PLUSVein/issues
