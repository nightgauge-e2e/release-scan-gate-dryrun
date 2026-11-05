# release-scan-gate dry run

Throwaway repository for [nightgauge/nightgauge#2946](https://github.com/nightgauge/nightgauge/issues/2946).
Its one workflow runs the core's merged `scripts/release-scan-gate.sh` against this
repository's own draft releases. A draft with a clean file must be published, and a
draft carrying the EICAR antivirus test string must stay a draft.

It holds no product code and publishes nothing but a text file. It is archived
once the issue closes.
