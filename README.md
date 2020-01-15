# ethspam

`ethspam` generates an infinite stream of realistic Ethereum JSONRPC queries,
anchored around the latest block with some amount of random jitter. The latest state is updated every 15 seconds, so it can run continuously without becoming stale.

Per second, ethspam generates around 500,000 lines, or 120 megabytes of data, on a modern portable laptop.

Also makes for an okay superniche screensaver.

## License

MIT
