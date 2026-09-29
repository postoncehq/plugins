# PostOnce plugins for Claude Code

The Claude Code plugin marketplace for [PostOnce](https://postonce.to)'s social media MCP servers. Each plugin connects your agent to one platform through its official API and adds the writing skills for that platform.

```bash
claude plugin marketplace add postoncehq/plugins
claude plugin install instagram-mcp@postoncehq
```

Then give Claude Code your PostOnce API key as the `POSTONCE_API_KEY` environment variable. Create the key in [PostOnce preferences](https://postonce.to/dashboard/preferences) and never paste it into chat.

| Plugin | What it adds |
| --- | --- |
| [`linkedin-mcp`](https://github.com/postoncehq/linkedin-mcp) | LinkedIn posts, carousels, formatting, headlines and profile copy |
| [`instagram-mcp`](https://github.com/postoncehq/instagram-mcp) | Instagram captions, carousels, Reel scripts, bios and hashtags |
| [`tiktok-mcp`](https://github.com/postoncehq/tiktok-mcp) | TikTok scripts, hooks, captions and photo slideshows |
| [`youtube-mcp`](https://github.com/postoncehq/youtube-mcp) | YouTube titles, descriptions, tags, scripts, Shorts and thumbnails |
| [`facebook-mcp`](https://github.com/postoncehq/facebook-mcp) | Facebook Page posts, Reels and page copy |
| [`x-mcp`](https://github.com/postoncehq/x-mcp) | X (Twitter) posts, threads, formatting and bios |
| [`threads-mcp`](https://github.com/postoncehq/threads-mcp) | Threads posts, crossposts and bios |
| [`bluesky-mcp`](https://github.com/postoncehq/bluesky-mcp) | Bluesky posts, bios and custom domain handles |
| [`pinterest-mcp`](https://github.com/postoncehq/pinterest-mcp) | Pinterest pins, descriptions, keywords, boards and blog-to-pins |

Every plugin also includes a content calendar skill and the shared `postonce` publishing skill. Claude (claude.ai and desktop) and ChatGPT users don't need a plugin: add `https://postonce.to/mcp` as a custom connector instead. See [PostOnce integrations](https://postonce.to/integrations).

## License

MIT. See [LICENSE](LICENSE).
