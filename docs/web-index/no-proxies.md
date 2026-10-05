# No rented proxies, no rotation

askFinz doesn't rent a residential proxy pool. Its fleet reads from its own machines in several countries, and a refusal is retried, not laundered.

**Canonical page:** [https://askfinz.com/web-index/no-proxies](https://askfinz.com/web-index/no-proxies)

## Key points

### Our own exits. Our own name. Our own problem when it goes wrong

Our own fleet, its own exits Reading runs on infrastructure askFinz operates — the same accountable fleet described on how the index works — and it reaches the web from its own machines in several countries rather than from one fixed address.

### A 403 says one exit was refused. It doesn't say the site is unreachable

A rented residential proxy pool is built to make traffic look like it's coming from ordinary people's home connections, at scale, from an address you don't control and usually can't see.

### You decide how it gets read

Allow it, slow it down, feed it in directly as a partner, or ask us not to read the site at all — the crawler documentation covers all four, and none of them requires an account.

## Frequently asked

### Does askFinz use proxies at all?

It reads from its own fleet's machines in several countries — not through a rented, rotating residential proxy pool bought from a third party. That's a meaningful difference: the machines are ours, accountable and identifiable, not an anonymous pool sold by the connection.

### What actually happens when a site returns a 403?

It's treated as "this particular exit was refused," not "this site can't be read." The request is re-queued along with the list of exits already turned away, and only counted as a real failure once every exit available has been refused.

### Do blocked pages get retried forever?

No — a page that stays unreachable moves into a pool-wide dead-URL registry so it isn't hammered on repeat, and that registry self-heals: a page is reconsidered after 14 days rather than being blocked in the record permanently.

### How can a site owner identify or block this traffic specifically?

Every request carries the User-Agent askFinz-Crawler/2.0 with a link to the crawler documentation, which covers exactly how to allow or block it — match on that token, not on an IP address, since the exit address is expected to vary.

## Related

- [Our own web index for AI, with sources](https://askfinz.com/web-index)
- [How the index works](https://askfinz.com/how-the-index-works)
- [The best web index for AI and LLM workflows](https://askfinz.com/web-index/best-web-index-for-ai)
- [What is web indexing?](https://askfinz.com/web-index/what-is-web-indexing)
- [Web scraping alternative: index, don't scrape](https://askfinz.com/web-index/vs-web-scraping)
- [What makes a web indexer AI-powered](https://askfinz.com/web-index/ai-web-indexer)

---

Summary of [https://askfinz.com/web-index/no-proxies](https://askfinz.com/web-index/no-proxies), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
