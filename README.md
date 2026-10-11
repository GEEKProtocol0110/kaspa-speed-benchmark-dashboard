# Kaspa Speed Benchmark Dashboard

**Status: planned benchmark concept.** The collector file `backend/block-watch.js` is empty; this repository does not yet provide a working dashboard or validated speed measurements. [GEEK HQ](https://www.geekprotocol.xyz/) has a separate live network-data companion; see [Kaspa Live Widget](https://github.com/GEEKProtocol0110/kaspa-live-widget).

The proposed tool would collect native transaction lifecycle timestamps from a Kaspa node, distinguish submission from acceptance, and show source, network, sample size and measurement limits. Those stages must be implemented and tested before reporting benchmark results. Block rate alone is not a transaction confirmation measurement.

Next engineering work: a reproducible collector, bounded storage, a display and failure/reorg handling using [Kaspa's accepted-transaction integration guide](https://docs.kaspa.org/integrate/accepted-transactions). No benchmark run or financial transaction is performed by this documentation change.

See [LICENCE](LICENCE).
