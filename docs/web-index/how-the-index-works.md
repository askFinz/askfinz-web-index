# How the index works

askFinz reads the web itself and keeps its own index — three stages, a distributed fleet, and about 21.7 KB of storage per page.

**Canonical page:** [https://askfinz.com/how-the-index-works](https://askfinz.com/how-the-index-works)

## Key points

### Three stages. Almost nothing reaches the third

Pages differ enormously in how hard they are to read. Rather than treat them all the same, each one starts cheap and only escalates if it has to.

### Most sites never notice us, because there is very little to notice

Starting cheap is usually described as our saving. It is just as much the site's.

### Owning the index changes what we can offer

Most AI products buy their web results from someone else's index. askFinz runs its own — the reading, the ranking and the storage are all ours.

### Spread out, on purpose

The work is shared across many machines rather than concentrated in one place. That keeps it cheap, keeps it close to the pages being read, and means no single failure stops it.

### Reading ahead of time means answering now

Because pages are read and understood before anyone asks, a question does not wait on the web. These are the live numbers from the running system.

### How a page becomes an answer

A traditional index rebuilds on a schedule, so what it knows is always a little out of date. Here the last step happens the moment the first one does — a page seen now is answerable now.

## Frequently asked

### Why does storage per page matter so much?

It is the difference between an index that can afford to grow and one that cannot. Costs scale with every page held, so a few kilobytes either way decides whether reading the whole web is a business or a bonfire.

### Does more machinery mean slower answers?

No — the opposite. Reading is spread out and done ahead of time, so by the time you ask a question the work is already finished.

## Related

- [Our own web index for AI, with sources](https://askfinz.com/web-index)
- [The best web index for AI and LLM workflows](https://askfinz.com/web-index/best-web-index-for-ai)
- [What is web indexing?](https://askfinz.com/web-index/what-is-web-indexing)
- [Web scraping alternative: index, don't scrape](https://askfinz.com/web-index/vs-web-scraping)
- [What makes a web indexer AI-powered](https://askfinz.com/web-index/ai-web-indexer)
- [No rented proxies, no rotation](https://askfinz.com/web-index/no-proxies)

---

Summary of [https://askfinz.com/how-the-index-works](https://askfinz.com/how-the-index-works), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
