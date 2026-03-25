# Threat Intelligence Indicator Dumps

This repository is a public collection of threat intelligence indicators shared to help the wider security community detect, investigate, and block malicious activity.

The datasets in this project currently focus on phishing and business email compromise (BEC) infrastructure and are published in simple, reusable formats so they can be consumed by defenders, researchers, and security teams.

## What You Will Find

This repository may contain:

- Domains
- IP addresses
- File hashes
- Campaign or cluster indicator sets
- Raw research exports
- Normalised CSV files for easier ingestion

Indicators are typically defanged where appropriate, for example `example[.]com`, to reduce the risk of accidental clicks or enrichment.

## Intended Use

This project is meant to support defensive security operations, including:

- SIEM and detection engineering enrichment
- Blocklist and denylist generation
- Threat hunting
- Malware, phishing, and infrastructure investigations
- Research and community sharing

Always validate indicators in your own environment before applying automated blocking at scale. Threat intelligence can age quickly, and some infrastructure may later be repurposed or sinkholed.

## Data Format Notes

- `.raw` files are simple line-separated indicator dumps.
- `.csv` files are intended for easier parsing and pipeline ingestion.
- Some files are curated and structured, while others are direct research exports.
- Duplicate indicators may exist in raw datasets.

## Safe Handling

- Treat all indicators as untrusted.
- Keep indicators defanged when sharing externally.
- Do not browse to listed domains or interact with infrastructure from unmanaged systems.
- Use isolated analysis environments for validation and enrichment.

## Contributing

If you have corrections, additions, or better context for an indicator set, open an issue or submit a pull request. Useful contributions include:

- New defensive indicators
- Improved normalisation or deduplication
- Additional campaign context
- Date, source, or tagging improvements

## Contact

For questions, corrections, or responsible sharing, contact `hello[@]itsjack[.]cc`.

## License

This project is released under the [MIT License](LICENSE).
