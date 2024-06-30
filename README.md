## Claude.ai ShareGPT Exporter

<img width="480" alt="image" src="https://github.com/EndlessReform/claude-sharegpt-exporter/assets/32968342/7454a926-11cd-4f56-a476-a29e07f555f8">

A fork of GeoAnima's and [TheAlanK's](https://github.com/TheAlanK/export-claude) Claude.ai chat exporter userscript. Exports your chat to [ShareGPT JSON format](https://github.com/domeccleston/sharegpt/blob/main/README.md), so you can view and process your chats in anything ShareGPT-compatible.

This extension has some minor quality-of-life improvements from upstream:

- Single click to download, since there's only one format
- Button hides properly on unrelated pages and blends into the Claude UI

## Installation

Install from the [GreasyFork](https://greasyfork.org/en/scripts/499310-claude-ai-sharegpt-exporter) page.

This script has been tested with [Violentmonkey](https://violentmonkey.github.io) for Chrome (recommended), but should work with Greasemonkey and Tampermonkey as well in compatible browsers.
It won't work with the Userscripts extension in Safari due to permission issues.

## Usage

On click, downloads are saved to your Downloads folder as `$CHAT_NAME_$TIMESTAMP.json`. That's it!

For a simple in-browser editor, consider using my [ShareGPT chat formatter](https://endlessreform.github.io/axolotl-sharegpt-converter/)!
