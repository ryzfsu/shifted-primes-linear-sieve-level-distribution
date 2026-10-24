# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v1`.
Each proof commits to the SHA-256 of the file below.

| file | SHA-256 |
|---|---|
| `shifted-primes-linear-sieve-level-distribution-v1.pdf` | `76c198c69a660ea9cd9e399cb0bb965056a20813a08644ebb4218c14c040b6f8` |
| `shifted-primes-linear-sieve-level-distribution-v1.tar.gz` | `553cf2b4f1979baddccdc206823a09ee0882435d21a41c387c110deb9f5fe76e` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots
