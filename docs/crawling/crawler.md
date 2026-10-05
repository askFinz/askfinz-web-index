# askFinz-Crawler · Web crawler documentation

How askFinz-Crawler behaves, how to identify it in your logs, and how to allow or block it. Documentation for site owners and webmasters.

**Canonical page:** [https://askfinz.com/crawler](https://askfinz.com/crawler)

## Key points

### What it looks like from your side

A crawl opens with robots.txt, picks up your sitemap if you publish one, and then works through pages at a steady, spaced pace. Requests carry this User-Agent:

### Allowing askFinz-Crawler

You don't need to do anything for us to read a public page. These are for the case where something in front of your site is turning us away.

### One name, a few purposes

Different parts of askFinz read the web for different reasons, and each says which it is. That way you can allow one and refuse another instead of making a single all-or-nothing decision.

### How it behaves on your site

Follows robots.txt When it crawls your site it reads your robots.txt first and follows your rules — including Crawl-delay, which it will only ever wait longer than, never shorter.

### Checking it's really us

Our requests reach sites through a privacy layer with rotating exits, so askFinz-Crawler does not come from one fixed IP address. Verify by the User-Agent token above rather than by address.

### Would you rather we read you properly?

Verified domain partners are read directly and kept fresh with priority, instead of waiting to be reached in the ordinary course of crawling. If your content is worth finding, this is the way to make sure it is.

### Where crawled pages go

The crawler is one way content reaches askFinz. What it reads flows into a real-time index that answers questions with citations back to the sites the answers came from.

### Get in touch

For anything about how we read your site — slowing down, stopping, removal, or a dedicated address — email bots@askfinz.ai. For partnerships and everything else, use contact.

### You decide how it gets read

Being read well should never be something that happens to you. Set the pace, feed your pages in directly with priority and real-time freshness, or ask us not to read the site at all — all three are your call, and none of them requires an account.

## Frequently asked

### Why does the crawler come from different IP addresses?

Its connection routes through a privacy layer with rotating exits, so there is no single fixed address to allow-list. Match on the User-Agent instead. If your setup genuinely requires IP allow-listing, contact us and we can arrange a dedicated address.

### Does being crawled cost me anything?

It shouldn't be noticeable. Requests are spaced out and rate-limited, and your Crawl-delay is always respected. If you're seeing load you can attribute to us, tell us and we'll slow down for your domain.

### Can I get my site indexed faster?

Yes — verified domain partners are read directly and refreshed with priority rather than waiting to be reached in the normal course of crawling.

### What happens to a page once you've read it?

It becomes part of the index that askFinz searches when someone asks a question. Answers drawn from your page cite it and link back to you, so the attribution stays with the source rather than being absorbed anonymously.

## Related

- [Submit a domain · the Web Index](https://askfinz.com/submit-domain)
- [Web safety · the Web Index](https://askfinz.com/web-safety)

---

Summary of [https://askfinz.com/crawler](https://askfinz.com/crawler), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
