# The askFinz web index

askFinz runs its own index of the web rather than renting results from another search provider. Pages are read in full, filed into typed collections by what they are, and answered with the passage that carries the answer and its source.

**Website:** [https://askfinz.com](https://askfinz.com) &nbsp;·&nbsp; **Contact:** hello@askfinz.com

## Crawling and web safety

- [askFinz-Crawler · Web crawler documentation](docs/crawling/crawler.md): How askFinz-Crawler behaves, how to identify it in your logs, and how to allow or block it. Documentation for site owners and webmasters.
- [Submit a domain · the Web Index](docs/crawling/submit-domain.md): Suggest a site worth reading. Submitted domains go into the askFinz indexing queue, and you can watch them being read on the live status page.
- [Web safety · the Web Index](docs/crawling/web-safety.md): How askFinz keeps malware, scams and adult material out of its index without quietly deleting the good web — layered checks and a human override.

## The web index

- [Our own web index for AI, with sources](docs/web-index/web-index.md): askFinz runs its own real-time index of the web — fed by the browser extension, the desktop app, askFinz OS devices, indexer machines and partner sites.
- [How the index works](docs/web-index/how-the-index-works.md): askFinz reads the web itself and keeps its own index — three stages and a head start, a distributed fleet, and storage measured in kilobytes per page.
- [The best web index for AI and LLM workflows](docs/web-index/best-web-index-for-ai.md): Most AI products rent someone else's search results. askFinz reads the web itself and answers from a standing index, filed by what each document is.
- [What is web indexing?](docs/web-index/what-is-web-indexing.md): Web indexing in plain English: crawl, read, store, retrieve. Most indexes store links to pages — askFinz stores what the pages actually say.
- [Web scraping alternative: index, don't scrape](docs/web-index/vs-web-scraping.md): Scraping charges you per page, every time, and breaks the moment a site redesigns. Indexing is done once, ahead of time, and stays fresh on its own.
- [What makes a web indexer AI-powered](docs/web-index/ai-web-indexer.md): An AI web indexer reads pages for meaning instead of keywords, files them by what they are, and answers in milliseconds. Here's what that actually takes.
- [No rented proxies, no rotation](docs/web-index/no-proxies.md): askFinz doesn't rent a residential proxy pool. Its fleet reads from its own machines in several countries, and a refusal is retried, not laundered.
- [Web index for AI agents: answers with sources](docs/web-index/for-ai-agents.md): Chat, Research, Search and News all read from the same index. It's what powers every askFinz app, not a feed sold or licensed on its own.

## Collections

- [Search collections: every library in the web index](docs/collections/collections.md): The askFinz index is kept as separate collections — research, law, standards, patents, news and more — each filed by what it is, not as loose web pages.
- [Research paper search: papers, preprints and data](docs/collections/research-and-data.md): Open-access research read in full — with the datasets a finding rests on kept alongside the write-up.
- [News archive search across thousands of publishers](docs/collections/news-and-briefings.md): The day's coverage read as it is published, with outlets running the same wire copy recognised as one story.
- [Encyclopedia and reference search](docs/collections/encyclopedia.md): The settled account of a subject, read from the maintained entry rather than a copy of it.
- [Industry and sector research search](docs/collections/industry-and-sector.md): Trade bodies and companies explaining their own market — where segment names and category definitions actually originate.
- [Company filings and earnings call search](docs/collections/markets-and-filings.md): Regulatory filings kept beside the earnings calls that explained them, with the reporting period attached to both.
- [Clinical trials search: studies and literature](docs/collections/medicine-and-clinical-research.md): Registered studies kept as registry records — with phase, sponsor and recruiting status intact — beside the literature.
- [Product and review search](docs/collections/products-and-reviews.md): The same item recognised across shops, so you compare a product rather than ten pages selling it.
- [Property search: for sale, to let and being built](docs/collections/property-and-construction.md): Live property listings and construction records, kept with the practical detail a decision actually turns on.
- [Registered trademark search](docs/collections/trademarks.md): Trademark registrations read from the offices that grant them — searchable by what a mark covers, not just its spelling.
- [Code repository search](docs/collections/code-repositories.md): Libraries findable by what they do rather than what they are called, with the docs read alongside the code.
- [Book and product manual search](docs/collections/books-and-manuals.md): Product manuals and book-length texts read page by page — including the ones published only as documents.
- [Course material and syllabus search](docs/collections/course-material.md): What a programme actually teaches, read from the institution rather than a directory's summary of it.
- [Questions and answers search](docs/collections/questions-and-answers.md): Threads read for their resolution — the accepted answer rather than the longest argument.
- [Job search: openings as employers publish them](docs/collections/jobs.md): Roles read from the employer's own posting rather than an aggregator's copy, which is often stale or altered.
- [Travel listing search](docs/collections/travel.md): Routes, stays and activities read from operators, with dates and availability kept as structured detail.
- [Film, music and video search](docs/collections/film-music-and-video.md): Releases matched on their industry identifier, so a remaster, a reissue and a same-titled remake stay separate things.
- [Event and recipe search](docs/collections/events-and-recipes.md): Events and recipes held with their quantities, timings and places intact rather than summarised away.
- [Agriculture data search: food and farming](docs/collections/agriculture.md): Agricultural material held as records — crops, yields, practice and the regulation around them.
- [Patent search: patents and published applications](docs/collections/patents.md): Granted patents and published applications from more than a hundred patent offices — searchable by what an invention does, not just the words in its title.
- [Technical standards and specifications search](docs/collections/standards-and-specifications.md): Technical standards in full — the documents that define how systems actually interoperate.
- [Public tender search: procurement notices](docs/collections/public-tenders.md): Contract notices from public buyers — who is buying what, where, and by when.
- [Case law and legislation search](docs/collections/law-and-legislation.md): Judgments from national and supranational courts, and the acts, regulations and statutory instruments beside them — searchable by what a case decided or what
- [Web page search](docs/collections/web-pages.md): Ordinary web pages, read and kept as pages. The collection everything else is filed out of — where a page belongs to no speciality shelf, it belongs here.
- [Economic indicator search](docs/collections/statistical-indicators.md): Economic and development indicators held as records rather than as pages describing them — the measure itself, filed so it can be read alongside the others.
- [Earth observation data search](docs/collections/earth-observation.md): Observations of the planet — its land, its atmosphere and its oceans — held as records rather than as articles reporting them.
- [Software vulnerability (CVE) search](docs/collections/software-vulnerabilities.md): Disclosed weaknesses in software and the systems built on it, held as records — the disclosure itself, not the coverage of it.
- [Company and organisation search](docs/collections/named-entities.md): Organisations, places and other named things filed as records in their own right, rather than only as mentions inside something else.
- [AI model search: machine-learning model records](docs/collections/ai-models.md): Models published for others to use, held as records — so one can be found by what it is for rather than by what it is called.
- [Insider trading transaction search](docs/collections/insider-transactions.md): Share dealings disclosed by the people closest to a company, held as records. This shelf has only just started filling — it is listed because the records are
- [Research record search](docs/collections/general-research.md): Research material held as records in its own right, apart from the papers, reports and data sets filed under the research corpus — so work that belongs to non

## Research

- [Engineering and research notes](docs/research/research.md): Short writing on what we believe, what we change our minds about, and how we read the work. Updates land in the inbox of anyone in private access first.
- [A workshop, not a chatbot](docs/research/a-workshop-not-a-chatbot.md): We argued for a single blank box, and rejected it. Here is the argument that lost, why it lost, and what the decision costs us.
- [Owning your tools again](docs/research/owning-your-tools-again.md): Count the layers of your working day that someone else can change without asking. For most professionals it is five out of six — and the honest fix is not…
- [Software should earn its keep](docs/research/software-should-earn-its-keep.md): A demo shows you the first time. Real work is the hundredth. Almost every design decision that matters is invisible in the first and decisive in the…
- [Speed is a feature, trust is the product](docs/research/speed-is-a-feature-trust-is-the-product.md): Every latency benchmark measures the wrong half of the clock. The wait is visible and the checking is not — which is why the faster answer is routinely…
- [We tell you which model wrote your answer](docs/research/tell-you-who-wrote-the-answer.md): Hiding the model is the industry default and it is a design choice, not a neutral one. It asks you to extend more trust than the situation earns.
- [The case against one big model](docs/research/the-case-against-one-big-model.md): The argument is not that more models are better. It is that being structurally unable to use anything else is a liability disguised as simplicity.
- [The hidden cost of switching tabs](docs/research/the-cost-of-switching-tabs.md): The expensive part of a context switch is not the switch. It is the climb back — and the climb never returns you to where you stopped.
- [The web became the operating system](docs/research/the-web-became-the-operating-system.md): You noticed it when a new laptop took twenty minutes to become useful. The browser stopped being where you look things up and became where the work is…

## By industry

- [Finance web index: filings, earnings calls, sectors](docs/industries/finance.md): Regulatory filings with the quarter they belong to, the earnings calls that explain them, and sector coverage read from the bodies that write it.
- [Legal web index: case law, statutes and patents](docs/industries/legal.md): Judgments with their jurisdiction, statutes at the section, patent publications by filing office, and trademarks with their status on the register.
- [Healthcare web index: trials and medical literature](docs/industries/healthcare.md): Registered studies split by study type — trial, observational, evidence-synthesis, preclinical — held beside the literature and reference entries around them.
- [Education web index: courses, papers, reference](docs/industries/education.md): Course material next to the papers it teaches from, plus maintained reference entries and the books and manuals behind a reading list.
- [Real estate web index: listings and projects](docs/industries/real-estate.md): Property listings, the construction pipeline around them, building materials, and public tender notices by country — one shelf instead of four portals.
- [Retail web index: products, reviews and brands](docs/industries/retail.md): Product records and the reviews written about them, held beside company and sector pages and de-duplicated daily coverage of the category.
- [Media web index: film, TV, music and news](docs/industries/media.md): Film and television titles, music releases and video, held beside de-duplicated news so a title sits next to what has been written about it.
- [Travel web index: stays, things to do, events](docs/industries/travel.md): Things to do and places to stay read from where they are published, with events and recipes alongside — the material a destination page is built from.
- [Consulting web index: sector research and tenders](docs/industries/consulting.md): Company and sector pages, research with its method attached, tender notices by country, and de-duplicated coverage — what a deck has to be right about.
- [Technology web index: code, standards, specs](docs/industries/technology.md): Specifications from the bodies that issue them, repositories read with their documentation, patent publications by office, and developer questions and answers.
- [Government web index: legislation and tenders](docs/industries/government.md): Legislation and judgments by jurisdiction, procurement notices by country, issued standards, and the research an evidence base is built from.
- [Nonprofit web index: research, grants and jobs](docs/industries/nonprofit.md): The research a grant application cites with its method attached, sector reporting in its own words, tender notices, and hiring read from the posting itself.

## About these files

Every file here is a structured summary generated from the matching page on askfinz.com, and links back to it. The website is the source of truth; if the two ever differ, trust the site.

Generated 2026-10-07.
