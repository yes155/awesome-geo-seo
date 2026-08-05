# Awesome GEO & Semantic SEO
> ⭐ **If you find this repository useful, please give it a Star!**
>
> It helps more SEO professionals, marketers, and developers discover the project.

&gt; A curated, opinionated list of resources for **Generative Engine Optimization (GEO)**, **Semantic SEO**, **Entity SEO**, and **Knowledge Graph Construction**.
&gt;
&gt; Maintained by [Farrukh Abdullah](https://farrukh.top) — Semantic SEO & GEO Consultant. IBM, Moz, BrightLocal, Anthropic certified.

---

## Table of Contents

- [What is GEO?](#what-is-geo)
- [GEO Monitoring & Intelligence Platforms](#geo-monitoring--intelligence-platforms)
- [Hybrid SEO + GEO Suites](#hybrid-seo--geo-suites)
- [Schema, Structured Data & Entity Tools](#schema-structured-data--entity-tools)
- [Knowledge Graph Construction](#knowledge-graph-construction)
- [Open-Source GEO Tools](#open-source-geo-tools)
- [AI Search Citation Research](#ai-search-citation-research)
- [Content Formats That AI Engines Cite](#content-formats-that-ai-engines-cite)
- [Technical Foundations for GEO](#technical-foundations-for-geo)
- [Communities & Discussion](#communities--discussion)
- [People to Follow](#people-to-follow)
- [Research Papers & Deep Reads](#research-papers--deep-reads)
- [Contributing](#contributing)

---

## What is GEO?

**Generative Engine Optimization (GEO)** is the practice of optimizing content, entities, and technical infrastructure so AI-powered answer engines — ChatGPT, Perplexity, Gemini, Claude Search — cite and trust your brand as a source.

Unlike traditional SEO, which optimizes for **ranking position**, GEO optimizes for **citation probability** inside synthesized answers.

Key differences:

| | Traditional SEO | GEO |
|---|---|---|
| **Goal** | Rank #1 on Google | Get cited inside AI answers |
| **Success metric** | Organic CTR, rankings | Citation frequency, brand mentions |
| **Content format** | Keyword-optimized articles | Structured, quotable, data-rich content |
| **Technical focus** | Page speed, mobile, Core Web Vitals | SSR, schema markup, `llms.txt`, entity consistency |
| **Authority signal** | Backlinks | Entity authority, knowledge graph presence, reviews |

---

## GEO Monitoring & Intelligence Platforms

Tools that track how AI engines mention, cite, or ignore your brand.

### Enterprise Tier

- **[Profound](https://www.profound.ai)** — The most advanced AI visibility tracker. Analyzes 400M+ prompts across ChatGPT, Claude, and Perplexity. Shows conversation-level insights, sentiment, and competitor encroachment. Integrates with GA4 to connect citations to actual traffic and conversions. Starting at ~$499/mo.
- **[AthenaHQ](https://www.athenahq.ai)** — Prescriptive GEO recommendations with an "Action Center" that turns visibility gaps into publishing tasks. Strong cross-market AI exposure analytics. $295–$595/mo.
- **[BrightEdge Generative Parser](https://www.brightedge.com)** — The gold standard for **Google AI Overviews** tracking. Decodes intent logic behind why queries trigger product carousels vs. text summaries vs. medical disclaimers. Essential for Google-centric GEO.

### Mid-Market / SMB Tier

- **[Peec AI](https://www.peec.ai)** — Clean, affordable GEO analytics. Distinguishes between direct "Source" citations and general brand "Visibility" mentions. Strong European footprint. ~€89–€499/mo.
- **[Otterly AI](https://www.otterly.ai)** — Beginner-friendly AI visibility watchdog. Converts keywords into conversational prompts and tracks brand mentions with sentiment. $29–$489/mo.
- **[Rankscale AI](https://www.rankscale.ai)** — Assigns exposure scores across prompts and models. Useful for benchmarking AI presence as a performance KPI. From €20/mo.
- **[Scrunch AI](https://www.scrunch.ai)** — Maps brand presence across multi-turn AI conversations. Features hallucination detection and bot monitoring. $300+/mo.

### Free / Freemium

- **[HubSpot AI Search Grader](https://www.hubspot.com/ai-search-grader)** — Free snapshot audit. Categorizes your brand as Leader, Challenger, or Niche Player based on AI engine positioning. Zero commitment.
- **[Geoptie GEO Audit](https://www.geoptie.com)** — Free GEO audit tool. Assess your AI search readiness.

---

## Hybrid SEO + GEO Suites

Legacy SEO platforms that have added AI visibility layers.

- **[Semrush AI Visibility Toolkit](https://www.semrush.com)** — Side-by-side "Google Rank" and "ChatGPT Rank" dashboard. "Prompt Volume" estimates replace keyword volume. AI-mode rank tracking and AI search site audits. $99/mo add-on per domain.
- **[Ahrefs Brand Radar](https://ahrefs.com)** — Tracks AI citations alongside traditional backlinks. Expands into Reddit, TikTok, and YouTube descriptions (high-weight sources for LLMs). Entity graphing shows semantic distance between your brand and key topics.
- **[Writesonic GEO Platform](https://writesonic.com)** — Merges AI visibility monitoring with content creation. "Action Center" turns citation gaps into instant content recommendations. Good for high-velocity teams. From $39/mo.
- **[Alli AI](https://alliai.com)** — Automated on-page and technical optimization at scale. Supports GEO indirectly through structured execution. From $299/mo.
- **[Frase](https://www.frase.io)** — AI content brief generation with SERP question clustering. Improves structured content creation for answer engines. From $49/mo.

---

## Schema, Structured Data & Entity Tools

- **[Schema.org](https://schema.org)** — The vocabulary. Non-negotiable for GEO. Focus on `Organization`, `Person`, `LocalBusiness`, `Product`, `FAQPage`, `HowTo`, and `Article` schemas.
- **[Google Rich Results Test](https://search.google.com/test/rich-results)** — Validate your markup before deployment.
- **[Google NLP API](https://cloud.google.com/natural-language)** — Extract entities from text and measure salience scores. Use this to verify Google's understanding of your content.
- **[InLinks](https://inlinks.net)** — Automates internal linking based on entity relationships and generates advanced schema markup.
- **[WordLift](https://wordlift.io)** — Builds internal knowledge graphs and automates semantic markup for large websites.
- **[Kalicube Pro](https://www.kalicube.com)** — Automates entity home building, Knowledge Panel acquisition, and brand SERP auditing.
- **[Diffbot](https://www.diffbot.com)** — Extracts structured data from web pages to build custom knowledge graphs and analyze entity relationships.
- **[Schema Markup Validator](https://validator.schema.org)** — Official Schema.org validator. Use alongside Google's tool for cross-checking.

---

## Knowledge Graph Construction

### Enterprise Graph Databases

- **[Neo4j](https://neo4j.com)** — The industry standard property graph database. Cypher query language. Free, cloud, and enterprise plans.
- **[Amazon Neptune](https://aws.amazon.com/neptune)** — Managed graph infrastructure on AWS. Supports Gremlin, openCypher, and SPARQL.
- **[Stardog](https://www.stardog.com)** — Enterprise semantic layer with virtual graph access. Best for governed data layers across many systems.
- **[GraphDB](https://www.ontotext.com/products/graphdb)** — RDF repository with semantic search. Free and commercial editions.
- **[OpenLink Virtuoso](https://virtuoso.openlinksw.com)** — Graph and RDF database with SQL support. Best for semantic web and linked-data teams.

### AI-Native / Agent Context Graphs

- **[Graphiti](https://github.com/getzep/graphiti)** — Open-source temporal context graph framework from Zep. Tracks entities, facts, relationship changes, and provenance over time. Essential for AI-agent memory.
- **[Zep](https://www.getzep.com)** — Hosted service built on Graphiti. Context graphs, access rules, and retrieval for production AI apps.
- **[Inferagraph](https://inferagraph.com)** — Turns messy business knowledge into graph-backed search and reasoning.
- **[pg-ripple](https://github.com/pg-ripple)** — Postgres-based graph and retrieval work. For teams that want graph context without adding a separate database.
- **[FalkorDB](https://www.falkordb.com)** — Redis-adjacent property graph. Cypher-style queries. Good for GraphRAG work.

---

## Open-Source GEO Tools

- **[llms.txt Generator](https://github.com/topics/llms-txt)** — Multiple open-source implementations of the `llms.txt` standard (the "robots.txt for the AI era"). Provides clean, markdown-based directories for LLM crawlers.
- **[Schema.org JSON-LD Generators](https://github.com/search?q=json-ld+generator)** — Community-built generators for LocalBusiness, Product, FAQ, HowTo, and Organization markup.
- **[Perplexity Citation Tracker (Community)](https://github.com/search?q=perplexity+citation)** — Scripts and scrapers for tracking Perplexity citations at scale.
- **[AI Search Visibility Dashboards](https://github.com/search?q=ai+search+visibility)** — Open-source dashboards combining GEO data with traditional SEO metrics.

---

## AI Search Citation Research

### Citation Patterns by Engine

Research on how different AI engines select sources:

| Engine | Top Citation Sources | Content Preference | Avg Citations Per Answer |
|---|---|---|---|
| **ChatGPT** | Wikipedia (~47.9%), Forbes, NYT, established trade pubs | Long-form (1500–3000 words), conservative, educational | ~5.0 domains |
| **Perplexity** | Reddit (~46.7%), recent blog posts, original research | Data-driven, tables, comparisons, fresh (&lt;90 days) | ~7.3 domains |
| **Claude** | Dense documents, evergreen guides, research reports | Nuanced, structured, in-depth | Lower (synthesizes more) |
| **Gemini** | YouTube transcripts, Google-native sources | Multimodal, visual assets | Varies |

**Key insight:** Only **11% of cited domains overlap** between ChatGPT and Perplexity. A single-platform strategy is ineffective.

### Critical Research Findings

- **Recency is heavily weighted** by Perplexity. Content decay is real — old pages lose citation priority unless actively updated. Use `dateModified` schema and "Living Document" strategies.
- **Original data is citation gold.** Perplexity weights proprietary research, original statistics, and documented first-hand outcomes significantly higher than paraphrased content.
- **Tables and structured comparisons** are among the most powerful citation triggers on Perplexity. Clean HTML table data gets extracted directly into answers.
- **Domain authority accounts for ~15%** of Perplexity's ranking factors. Off-page SEO directly contributes to citation frequency.
- **AI-referred traffic converts 4.4x higher** than traditional search traffic. Lower volume, but far more qualified.
- **Reviews act as "Ground Truth"** for LLMs. When models encounter conflicting information, they default to sentiment found in user reviews. Fresh, verified reviews significantly increase citation probability.

---

## Content Formats That AI Engines Cite

### High-Citation Formats

1. **Original Research & Data** — Surveys, benchmarks, first-hand outcome reports. Perplexity especially rewards proprietary data.
2. **Structured Comparisons (X vs Y)** — Clean HTML tables with labeled columns. Perplexity extracts these directly.
3. **FAQ Schema Blocks** — Direct Q&A format. AI engines pull answers cleanly from FAQPage schema.
4. **HowTo Schema** — Step-by-step instructions with images and timestamps.
5. **Living Documents** — Continuously updated pillar pages with "Recent Updates" sections and accurate `dateModified` values.
6. **Entity-First Definitions** — Clear, unambiguous entity definitions with `sameAs` links to Wikidata, Wikipedia, and official sources.
7. **Expert Roundups with Attribution** — Named expert quotes with clear sourcing. AI engines cite the original source.

### Low-Citation Formats (Avoid)

- Thin listicles with no original insight
- AI-generated content without human verification (risk of "model collapse" filtering)
- Gated content that crawlers can't access
- Heavy commercial framing without educational balance
- Content behind JavaScript rendering without SSR

---

## Technical Foundations for GEO

### Must-Have Technical Setup

1. **Server-Side Rendering (SSR)** — ChatGPT and Claude crawlers do not execute JavaScript. Client-side rendered content is invisible.
2. **`llms.txt` File** — Place in root directory. Markdown-based index of your most important content for LLM crawlers. Considered critical future-proofing.
3. **Complete Schema Markup** — Organization, Person, Article, FAQ, HowTo, LocalBusiness. Use `@id` nodes and `sameAs` properties.
4. **Entity Consistency** — Same name, address, description across your site, Wikidata, Wikipedia, social profiles, and directories.
5. **Freshness Signals** — Active `dateModified` schema, recently updated content, current reviews.
6. **Clean HTML Structure** — Semantic HTML5, proper heading hierarchy, minimal DOM bloat. AI crawlers parse structure before content.

### Recommended Stack

| Layer | Tool / Standard |
|---|---|
| **Crawling** | SSR (Next.js, Nuxt, Astro) or Prerender.io |
| **Schema** | Schema.org JSON-LD + Google Rich Results Test |
| **Entity Verification** | Google NLP API + Wikidata |
| **Monitoring** | Profound / Peec AI / HubSpot Grader |
| **Content** | Frase / Writesonic (for scale) |
| **Knowledge Graph** | Neo4j / Graphiti (for advanced implementations) |

---

## Communities & Discussion

Where GEO and semantic SEO practitioners actually talk:

- **[r/SEO](https://www.reddit.com/r/SEO/)** — General SEO, increasing GEO discussions
- **[r/bigseo](https://www.reddit.com/r/bigseo/)** — Advanced SEO, entity-focused threads
- **[r/LocalSEO](https://www.reddit.com/r/LocalSEO/)** — Local SEO + GBP optimization
- **[r/MachineLearning](https://www.reddit.com/r/MachineLearning/)** — Technical discussions on LLM retrieval and RAG
- **[IndieHackers](https://www.indiehackers.com/)** — Bootstrapped founders discussing AI search impact
- **[Search Engine Land](https://searchengineland.com)** — Industry news, GEO coverage increasing
- **[Schema.org Community](https://github.com/schemaorg/schemaorg)** — GitHub discussions on structured data evolution
- **[Wikidata Project Chat](https://www.wikidata.org/wiki/Wikidata:Project_chat)** — Entity data discussions
- **[LinkedIn — GEO & Semantic SEO](https://www.linkedin.com)** — Search for GEO-focused newsletters and groups

---

## People to Follow

| Name | Focus | Where to Follow |
|---|---|---|
| **Amit Bachbut** | GEO strategy, AI visibility intelligence | LinkedIn, Profound blog |
| **Jason Barnard** | Entity SEO, Knowledge Panels, Brand SERPs | Kalicube, LinkedIn |
| **Cindy Krum** | Mobile-first indexing, AI search, entity understanding | MobileMoxie, Twitter/X |
| **Kevin Indig** | Growth SEO, content strategy, AI impact | Newsletter, LinkedIn |
| **Aleyda Solis** | Technical SEO, international, AI search readiness | Twitter/X, Newsletter |
| **Mike King** | Technical SEO, JavaScript, AI crawler behavior | iPullRank, Twitter/X |
| **Lily Ray** | E-E-A-T, algorithm updates, AI search | Amsive, Twitter/X |
| **Cyrus Shepard** | Content strategy, entity optimization | Zyppy, Twitter/X |
| **Marie Haynes** | Google algorithm analysis, AI Overviews | Marie Haynes Consulting, Newsletter |
| **Bernard Huang** | Entity-first SEO, topical authority | Clearscope, Twitter/X |

---

## Research Papers & Deep Reads

### Academic / Technical

- **"GEO: Generative Engine Optimization"** — Original academic paper defining the field. Covers citation probability optimization, statistical parity, and fluency optimization.
- **"Retrieval-Augmented Generation for Large Language Models"** — Survey paper on RAG architectures. Essential for understanding how Perplexity and similar engines retrieve and synthesize.
- **"Knowledge Graphs"** — Survey by Hogan et al. (2021). The foundational text for knowledge graph construction and reasoning.
- **"BERT: Pre-training of Deep Bidirectional Transformers"** — Understanding how Google's NLP models process entities and context.

### Industry Deep Dives

- **"Mastering Generative Engine Optimization in 2026"** — Search Engine Land. Comprehensive guide on building, executing, and measuring GEO strategy.
- **"ChatGPT vs Perplexity for SEO: How Each Engine Actually Picks Its Citations"** — Resocial. Side-by-side breakdown of citation logic.
- **"Top 15 Generative Engine Optimization (GEO) Platforms for 2026"** — Evertune. Platform comparison with implementation notes.
- **"The Master Guide to Entity-Based SEO Strategy"** — Outpace SEO. Entity strategy execution guide with tool recommendations.
- **"Knowledge Graph Software and Tools (2026)"** — Atlas Workspace. Developer-focused comparison of graph databases and AI context tools.

### Essential Concepts

- **Information Gain** — The net new value your content adds to the existing index. Not repeating what the top 10 results say, but expanding the Knowledge Graph with new relationships and data.
- **Model Collapse** — When AI models train on too much AI-generated content, quality degrades. Human-generated content (reviews, forums, expert guides) becomes more valuable.
- **Source Stack** — The hierarchy of data LLMs trust: Foundation (brand assets) → Validation (reviews/UGC) → Amplification (PR/media).

---

## Contributing

This list is opinionated and incomplete by design. GEO is evolving weekly.

**To contribute:**
1. Fork this repo
2. Add your resource under the correct section
3. Include a one-line description of why it matters
4. Submit a PR

**Criteria for inclusion:**
- Must be directly relevant to GEO, semantic SEO, entity optimization, or knowledge graphs
- Prefer tools with free tiers or open-source licenses
- No affiliate links
- No thin content or AI-generated marketing fluff

---

*Curated by [Farrukh Abdullah](https://farrukh.top) — Semantic SEO & GEO Consultant | Faisalabad, Pakistan | Serving clients globally*

*Certifications: IBM • Moz • BrightLocal • Anthropic*

*Last updated: August 2026*
