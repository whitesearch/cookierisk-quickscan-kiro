# CookieRisk Quickscan for Kiro

Check one public homepage you own or are authorized to scan for cookies and tracking observed before consent interaction.

## Install and use

In Kiro, open **Powers**, choose **Add Custom Power**, then **Import power from GitHub**. Use this repository URL. The power connects to the hosted CookieRisk MCP endpoint without a CookieRisk account or API key.

Ask Kiro to run a CookieRisk Quickscan on an authorized public homepage. The `start_quickscan` tool returns a scan ID. The `get_quickscan_result` tool uses that ID to retrieve progress or the sanitized findings. When an eligible scan is reused, the response includes the evidence capture time when known and the end of the 24-hour domain cooldown.

Quickscan observes a single public homepage before interaction. Private pages, consent-button testing, bulk scans, monitoring and legal verdicts are outside its scope.

[Quickscan documentation](https://cookierisk.eu/developers/mcp) · [Privacy policy](https://cookierisk.eu/privacy) · [Support](mailto:info@cookierisk.eu)

## License

The manifest's `LicenseRef-Kiro-Powers-Publisher-Terms` refers to the permissions applicable to this Power under the [Kiro Powers Publisher Terms](https://kiro.dev/powers/terms/). The hosted CookieRisk service is governed by the [CookieRisk Terms of Service](https://cookierisk.eu/terms).
