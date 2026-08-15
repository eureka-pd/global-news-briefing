# Daily Global News Briefing — 2026-07-14 KST

- Publication window: 2026-07-13 04:00 KST to 2026-07-14 04:00 KST
- Convention: Times are KST unless noted. Verified facts and analysis are separated.

## Verified facts

### Technology

1. **An open-source tool now aggregates sessions from multiple AI coding agents.**
   - GeekNews featured [AgentsView](https://news.hada.io/topic?id=31370) at 09:31 on July 13. It discovers local sessions from more than 20 agents, including Claude Code and Codex, stores them in SQLite, and provides search, activity, token and cost analytics through a web UI and CLI.

2. **A small measurement compared the up-front token overhead of Claude Code and OpenCode.**
   - GeekNews highlighted the [logging-proxy comparison](https://news.hada.io/topic?id=31373) at 09:55. The author measured roughly 33,000 fixed input tokens for Claude Code versus 7,000 for OpenCode on a minimal task, while the cumulative gap narrowed substantially in multi-step work because of parallel tool calls. It is a July 2026 snapshot from one machine and a small sample.

3. **An analysis says Chromium 148's `Math.tanh` output can become an OS fingerprint.**
   - At 10:10, GeekNews posted an [analysis of V8's move to `std::tanh`](https://news.hada.io/topic?id=31380). The source argues that tiny floating-point differences in each operating system's `libm` can distinguish Linux, macOS and Windows, and points to the relevant V8 commit.

4. **Ploy published its own production-agent migration case for GPT-5.6.**
   - GeekNews featured the [Ploy case study](https://news.hada.io/topic?id=31404) at 03:40 on July 14. In the company's website-rebuild evaluation, GPT-5.6 averaged 3 minutes 42 seconds and $2.22, versus 8 minutes and $3.06 for Claude Opus 4.8. The samples were 10 and 11 runs respectively; this was not an independent benchmark.

5. **An EU advisory panel recommended an under-13 social-media restriction and scrutiny of AI companions.**
   - AI Times reported at 21:25 on the [European Commission panel's recommendations](https://www.aitimes.kr/news/articleView.html?idxno=40960), covering generative AI, chatbots, AI companions, recommender systems and deepfakes. This is a policy proposal, not enacted law; the EU may consider follow-up under the DSA, GDPR and AI Act.

6. **Korea secured the secretariat for a new IEC smart-manufacturing subcommittee.**
   - AI Times reported at 18:05 on the creation of [SC65F under IEC TC65](https://www.aitimes.kr/news/articleView.html?idxno=40958). Korea's standards agency said the group will cover digital-twin factories, connected smart manufacturing and AI-enabled autonomous manufacturing, with Korea coordinating operations and standards development.

7. **Google Cloud and Samsung Electronics are expanding enterprise agentic AI deployment.**
   - AI Times reported at 11:38 on a plan to [provide Gemini Enterprise to Samsung's global DX workforce](https://www.aitimes.kr/news/articleView.html?idxno=40951). The companies plan to connect internal systems and knowledge and build a dedicated security and governance environment. Productivity gains remain forward-looking.

### Markets and economy

1. **Korea's exports for July 1–10 reached a ten-day record on semiconductor strength.**
   - KBS World reported [provisional customs data](https://world.kbs.co.kr/service/news_view.htm?Seq_Code=202845&lang=e) at 09:46. Exports rose 53.9% year over year to $29.8 billion, semiconductor shipments jumped 193% to $11.2 billion, and the trade surplus was $6.4 billion.

2. **The KOSPI plunged 8.95% amid tech selling and Middle East tension.**
   - KBS World reported at 16:04 that the [KOSPI closed down 669.01 points at 6,806.93](https://world.kbs.co.kr/service/news_view.htm?Seq_Code=202861&lang=e). The KOSDAQ lost 4.55%, and the won stood at 1,503.4 per dollar as of 15:30.

3. **Global equities fell while oil and government-bond yields rose.**
   - A [Reuters market wrap published at 18:18 CEST](https://live.euronext.com/en/financial-news/stocks-slip-oil-rallies-and-bond-yields-rise-gulf-conflict-escalates) put the S&P 500 down 0.40%, the Nasdaq down 0.94% and the MSCI world index down 0.60% as of 15:43 GMT (00:43 KST on July 14). Brent was up 4.41% at $79.36 a barrel. The U.S. cash market closed after the briefing window, so these are intraday figures.

### Politics and geopolitics

1. **Former President Yoon Suk Yeol received a two-year sentence for illegally acquiring polling results.**
   - KBS World reported the [Seoul Central District Court ruling](https://world.kbs.co.kr/service/news_view.htm?Seq_Code=202864&lang=e) at 16:50. The court found him guilty of illegally obtaining results from 14 polls and ordered forfeiture of about 14 million won.

2. **The United States and Iran each claimed control of the Strait of Hormuz, while Trump proposed transit charges.**
   - An AP [article](https://apnews.com/article/iran-us-hormuz-strait-war-july-13-2026-6c2c44cfdd089d6393d18fa5930ed620), published at 11:45 on July 13 and updated at 02:19 on July 14, reported the conflicting claims and President Donald Trump's proposal for a 20% toll. The International Maritime Organization said there is no legal basis for mandatory fees to transit an international strait.

3. **Ukraine and nine European countries announced a ballistic-missile defense coalition.**
   - AP reported the [joint statement from talks in Paris](https://apnews.com/article/russia-ukraine-war-europe-coalition-putin-d813eb18fba24a57f7cb2000b302ef4d). The ten countries set a goal of building a shared European ballistic-missile defense capability, but announced no timetable or specific system.

## Analysis

- **AI competition is moving from models alone to operating cost, security, standards and governance.** Agent observability, token-overhead measurement, enterprise deployment and manufacturing standards all point to the growing importance of the operating layer.
- **Korea's selloff shows a collision between semiconductor fundamentals and short-term risk aversion.** Strong export data was outweighed by tech profit-taking, AI-valuation concerns and Hormuz risk.
- **Hormuz is the common driver across equities, oil and rates.** Control and toll claims remain disputed; volatility is likely to stay elevated until actual traffic and legal enforceability become clearer.

## Verification notes

- GeekNews archive `datetime` values for July 13 and 14, AI Times RSS/article metadata, and KBS, AP and Reuters timestamps were cross-checked.
- Items before July 13 04:00 were excluded; the July 14 03:40:50 item was inside the window.
- AI Times RSS and article pages were directly accessible, so active-browser manual control was not needed.
- Company cases, small-sample comparisons, policy recommendations and party claims remain explicitly attributed; U.S. equity figures are labeled intraday.
