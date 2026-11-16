# Scrape.do plugin for Claude

The official [Scrape.do](https://scrape.do) plugin for Claude Code and Cowork.
It lets Claude scrape any public web page through Scrape.do's anti-bot proxy
network, pull structured Google Search, Amazon and Walmart data, and run
batches of up to 1,000 URLs as async jobs.

## Install

1. Get your API token at [app.scrape.do](https://app.scrape.do).
2. Install the `sdo-mcp` program:
   - macOS or Linux: `brew install scrape-do/tap/sdo-mcp`
   - Windows: `scoop bucket add scrape-do https://github.com/scrape-do/scoop-bucket`
     then `scoop install scrape-do/sdo-mcp`
3. Install the plugin from the Claude plugin directory, or in Claude Code:

   ```
   /plugin install scrape-do --marketplace scrape-do/claude-plugin
   ```

   Paste your API token when asked.

Full setup, tools and troubleshooting: [plugin/README.md](plugin/README.md).

The MCP server itself lives in
[scrape-do/sdo-mcp](https://github.com/scrape-do/sdo-mcp).

## Privacy Policy

See [plugin/README.md](plugin/README.md#privacy-policy) and
[scrape.do/privacy-policy](https://scrape.do/privacy-policy/).

## License

Apache-2.0. See [LICENSE](LICENSE).
