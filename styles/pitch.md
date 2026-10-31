# Pitch

## Understand the relationship

Write as a vendor making first contact with a prospect who has never heard from you. The reader will decide in a few seconds whether this is worth their time, so say what you are selling and let the catalogue carry the message. The pitch is honest about being a pitch; that is what keeps it from sounding like a sales playbook.

The reader's own expertise does the matching. Supply precise coverage and let them notice what would be new to them. Do not explain why their work needs more data, quote their interviews back at them or describe their problem for them.

## Make the catalogue carry the voice

- Open with who you are commercially and why you are writing, in plain words: a data vendor, what the feeds are, who buys them, and that the reader might want to look at the catalogue. Do not introduce the company with ceremony, pretend familiarity or lead with a quote from the prospect.
- One sentence may connect the catalogue to the prospect's work. Keep it tentative and literal ("might be useful for pricing in live events in your forecasting models"). Do not promise outcomes.
- List the catalogue one feed per bullet: the source name, then its concrete scope. Use the names the reader would use (PACER, TDnet, BIS, OIRA), counts, coverage and where the feed is served from.
- Split anything crammed. A bullet that holds several unrelated sources loses each of them; the user split a single government bullet into White House, Truth Social, US regulation and sanctions, Chinese government and aviation.
- Choose feeds and details for the reader. Drop products they have no use for and capabilities that only matter to another buyer (follow/unfollow tracking for a forecasting firm). Keep the list long when the coverage is genuinely broad; concise means no filler, not a short list.
- State measurements as measurements, with the reference point ("84 ms median latency measured from `created_at`"). Keep launch status and other qualifiers.
- After the list, give delivery facts in one paragraph: format, transport, timestamps, history, custom work.
- Close with the next step as an offer, not a request for a meeting: samples or a call, if anything looks useful.

Subject lines name the company and what it is: "Synoptic (event feed vendor)".

## Keep it separate from the other styles

Builder explains a mechanism to a peer and may show reasoning; a pitch shows inventory and stops. Brand presents one product or announcement with structure; a pitch presents a catalogue to one reader and is explicit that it is a sales email. Do not import a Brand-style definition of the company, a Builder-style anecdote or any humor.

## Approved example

Cold email to Mantic, written with the user in October 2026 and approved by them. Product details and figures are the user's; do not reuse them as facts in a pitch for another product or later date without checking the current catalogue. The rejected openings for the same email are recorded in [calibration 004](../calibration/004.md).

> Subject: Synoptic (event feed vendor)
>
> Hi Toby, Ben,
>
> We’re a data vendor providing low-latency event feeds to trading firms. Thought you might be interested in taking a look at our data feed catalogue. I think some feeds might be useful for pricing in live events in your forecasting models.
>
> We cover:
> - X/Twitter: real-time posts from 100,000 accounts, with point-in-time history. We also provide custom Twitter accounts tracker with capacity of up to 500k accounts.
> - Telegram: live tracking of over 21 million public channels and groups.
> - Reddit: the post-and-comment firehose.
> - News: 141 publications, including Bloomberg, FT, WSJ and regional outlets.
> - Newswires (PRNewswire, Accesswire etc).
> - SEC EDGAR: full filings.
> - US earnings and corporate disclosures, including from IR pages.
> - APAC corporate disclosures: TDnet in Japan, HKEX in Hong Kong, SGX in Singapore, MOPS in Taiwan, KIND in South Korea, BSE and NSE in India. Served from Tokyo, Seoul and Mumbai.
> - Courts: PACER coverage of all newly filed cases in Federal districts, case docket tracking, plus FTC antitrust proceedings and bulk Google Scholar case law with daily updates.
> - White House: official releases and press-pool reports.
> - Trump Truth Social: 84 ms median latency measured from `created_at`.
> - US regulation and sanctions: BIS export controls, OFAC sanctions and OIRA rulemaking.
> - Chinese government: releases from the ministries of Commerce, Finance and Foreign Affairs.
> - Aviation: NOTAM aviation notices.
> - Science and biotech: FDA decisions and advisory materials, ClinicalTrials.gov changes, bioRxiv/medRxiv and abstracts from roughly 40 conferences.
> - USPTO patents and trademarks.
> - arXiv: papers across all subject areas.
> - Compute: spot/on-demand GPU and cloud-instance pricing from over 70 hyperscalers and neoclouds.
> - Other sources: real-time YouTube transcripts, Substack, Medium and 21 activist short-seller sources.
>
> The live feeds come as JSON over API or WebSocket, with source and receipt timestamps. We keep point-in-time history from each feed’s launch, with older backfills available for some sources. We also do custom/bespoke scraping projects for hard-to-scrape targets.
>
> Can send over samples or set up a call if anything looks useful.

## Check the draft

Does the first sentence say what is being sold? Could the reader scan the bullets and name what they do not have yet? Remove every sentence that explains the reader to themselves, and every bullet detail the reader has no use for.
