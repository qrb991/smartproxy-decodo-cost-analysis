# Smartproxy review: the Decodo rebrand, what you actually pay per GB, and when $1/GB traffic is the smarter buy

The most useful thing anyone can tell you before you pay for Smartproxy is that Smartproxy isn't the name on the invoice anymore. The company rebranded to Decodo in 2025 and moved its storefront to decodo.com. Search the old name and you'll still get results — including smartproxy.org, a domain Decodo says has no connection to it and which its own May 2026 write-up links to research tying roughly 38% of that site's observed IPs to infrastructure Google disrupted earlier this year. So before anything else: if a deal looks like Smartproxy and isn't Decodo, walk away.

That leaves two real questions. Is the Decodo product worth the current price ladder, and what do you do if your volumes are too small or too uneven for a metered monthly plan? Both have answers, and the second one is where most people overpay.

## What happened to Smartproxy, in one paragraph

Decodo is Smartproxy with a new logo. Same network, same team, same support desk, same accounts. The company now advertises a residential and mobile pool in the 115M+ range across 195+ locations, and it kept the plan structure that made Smartproxy popular in the first place: per-GB billing, self-serve signup, no sales call required. Anything you read about Smartproxy before the rename — forum threads, tutorials, price screenshots — is evidence about Decodo's behaviour but not about its current prices. Behaviour survives a rebrand. Numbers don't. Treat 2024 pricing posts as historical documents.

## The advertised floor vs the rate a first-time buyer clicks

This is the part that decides your bill, and it's where proxy providers are reliably generous with the truth.

Decodo's residential page advertises entry pricing from $2/GB. That number is real and it is printed in a purchasable tier — the 1TB-per-month one. What a new buyer with no commitment actually sees on the card is a different figure. Based on published teardowns of the current pricing table and independent trackers, the ladder runs roughly like this, excluding VAT:

| Monthly commitment | Package price | Effective per GB |
| --- | --- | --- |
| 3 GB | ~$11.25 | ~$3.75 |
| 10 GB | ~$35 | ~$3.50 |
| 25 GB | ~$81.25 | ~$3.25 |
| 50 GB | ~$150 | ~$3.00 |
| 100 GB | ~$275 | ~$2.75 |
| 1,000 GB | ~$2,000 | ~$2.00 |
| Pay as you go | per GB | ~$4.00 |

So the honest reading is: the $2 rate is real but it lives behind a 1TB monthly commitment, and a buyer testing with 3 GB pays nearly double that. Every listed price is also quoted before VAT, which matters if you're billing from the EU. Rates and tier boundaries shift, so confirm on the live page before you commit budget.

Per-IP products follow the same pattern. Dedicated static residential IPs advertise from $0.27, which reflects traffic-based access rather than a private address; the dedicated IPs most buyers actually want land around $2.70–$3.33 per IP per month depending on bundle size. Datacenter sits at the cheap end — roughly $0.02 per IP or about $0.45/GB shared — and mobile starts around $2.25/GB.

## Terms that decide the bill more than the rate does

Three things about Decodo's billing matter more than the headline rate:

- **Trial and refund are alternatives, not a stack.** The free trial is 3 days including 100 MB, and it requires a payment method; when it ends it rolls into the plan you selected unless you cancel first. The 14-day money-back route applies to a purchase instead: first purchase only, request inside 14 calendar days, and under 20% of traffic used on regular plans (10% on Enterprise). Pick one deliberately rather than assuming you get both.
- **Subscription arithmetic cuts one way.** Trustpilot feedback on the platform sits around 4.3/5 and skews positive on support speed, but the recurring complaint is billing mechanics — upgrading mid-cycle without credit for the unused portion of the old plan, and refunds arriving as platform wallet balance rather than back on the card. That's a cash-flow problem, not a service-quality problem, and it only bites if you change plans mid-month.
- **Unused allowance is on the clock.** A metered subscription quotes per GB but bills on a calendar. Whatever you don't burn before renewal is gone. If your traffic is lumpy — heavy launch weeks, quiet months — that is the number to model, not the per-GB rate.

## What independent testing actually says

The performance story is genuinely strong. CNET's 2026 proxy roundup scored Decodo 9.5 and named it the best pick for businesses using under 100GB a month, citing best-in-class success rate and response times, an unusually usable browser extension, and low pay-as-you-go rates. The criticisms in the same review are worth as much as the praise: high-volume residential plans get expensive, and there's no city-level targeting on ISP and datacenter products. Aggregate ratings sit at 4.6/5 on G2 and around 4.3/5 on Trustpilot.

Where it stops making sense is scale and workload shape:

- You need more than ~100GB a month on residential, and the $2/GB tier becomes the only rational entry point.
- You want city, ZIP or ASN targeting on static or datacenter products.
- Your usage swings hard month to month and you can't predict the tier you'll fill.
- You only want a small volume to test a scraping setup before committing real money.

That last category is bigger than it looks. Most teams don't fail at proxies because they bought the wrong provider; they fail because they bought 25 GB up front to test something that needed 3 GB.

## The full plan lineup if you'd rather not run on a calendar

Here's where a pay-as-you-go model changes the arithmetic. 👉 [See the current pay-as-you-go proxy plans and top up only what you use](https://bit.ly/dataimPulse)

DataImpulse sells the same four proxy families — residential, datacenter, mobile and premium residential — but with no subscription, no renewal date and no expiry on purchased traffic. The minimum top-up is $5 across every product type, which buys 5 GB of residential, 10 GB of datacenter or 2.5 GB of mobile traffic. Here is the whole lineup as published:

| Proxy type | Intro (new users) | Basic | Advanced | Larger volumes | Effective rate | Get started |
| --- | --- | --- | --- | --- | --- | --- |
| Residential (90M+ IP pool, 195 countries) | 5 GB — $5 | 50 GB — $50 | 1 TB — $800 | 5 TB+, from $4,000 | $1.00/GB; $0.80/GB at 1 TB | [Start with the $5 residential intro](https://bit.ly/dataimPulse) |
| Datacenter | 10 GB — $5 | 100 GB — $50 | 1 TB — $450 | 5 TB+, from $2,250 | $0.50/GB; $0.45/GB at 1 TB | [See the datacenter rates](https://bit.ly/dataimPulse) |
| Mobile (5G/4G/3G/LTE) | 2.5 GB — $5 | 25 GB — $50 | 1 TB — $1,600 | 5 TB+, from $8,000 | $2.00/GB; $1.60/GB at 1 TB | [Check the mobile proxy pricing](https://bit.ly/dataimPulse) |
| Premium residential | 1 GB — $5 | 10 GB — $50 | 1 TB+, from $4,000 | Custom | $5.00/GB; $4.00/GB at 1 TB | [Compare premium residential plans](https://bit.ly/dataimPulse) |

The $5 entry covers all four types, traffic doesn't expire, and volume discounts kick in at the 1TB tier — 20% on residential and mobile, which is where the $0.80/GB figure comes from. Country-level targeting is included at no surcharge. State, city, ZIP and ASN targeting is a paid add-on and, per multiple reviews, roughly doubles traffic consumption, so budget for it rather than being surprised by it.

## The cost math on a realistic workload

Take the case that breaks Decodo's model: a team that needs residential traffic for a price-monitoring job, spiky by nature, averaging maybe 40 GB in a good month and 8 GB in a quiet one.

On a monthly metered plan, the 50 GB tier runs about $150 — and a quiet month still costs $150, with the unused allowance expiring at renewal. Four months at that tier is roughly $600 for somewhere between 32 GB and 160 GB of actual usage. On pay-as-you-go at $1/GB, 40 GB costs $40 and 8 GB costs $8. Size that against your own numbers before assuming the subscription is cheaper, because the cheapest-per-GB plan is only cheap if you fill it.

Now the reverse case. A team running a steady 400 GB a month of residential traffic will do better on a subscription with volume pricing than on any $1/GB balance, because a stable, high, predictable volume is exactly what tier discounts reward.

## Cheap per GB isn't the same as cheap per result

This is where a fair review has to push back on its own recommendation.

CNET tested 16 providers for that same roundup and placed DataImpulse at 7.6/10, noting the cheapest mobile proxies it saw but flagging a fraud score near the bottom of Proxyway's 2025 benchmark, a residential pool smaller than the majors, and mobile response times around 1.42 seconds — described as glacial. It also noted, oddly, that the more expensive premium tier scored worse on fraud than the basic one. TechRadar's separate review reported consistently high scraping success rates from the residential pool and praised the country-level targeting being bundled into the base rate, but the fraud-score finding is the one to keep in front of you.

What that means in practice: the real cost of a proxy is per successful request, not per gigabyte. A $1/GB pool that fails twice as often can cost more than a $3/GB pool that succeeds. If your targets are aggressively protected — retail, travel, ticketing, anything with serious bot management — test before you scale, on both sides.

The other honest limitation: DataImpulse is an ethically sourced residential, mobile and datacenter network, not a static ISP reseller and not a fully managed scraping API. If you need fixed ISP addresses for long-lived account sessions, or an end-to-end scraping product that handles parsing for you, it isn't the tool. Its own docs say as much.

## Support, sessions and the practical details

Sticky sessions are configurable from 1 to 120 minutes, with roughly 30 minutes as the realistic average — the actual duration depends on whether the real user behind the IP stays online, and the platform rotates automatically when they drop. That behaviour comes from the peer-sourced model rather than a bug, and it's the kind of limitation worth knowing before you build long session workflows on top of it.

Both username/password and IP whitelist authentication are supported, HTTP/HTTPS and SOCKS5 are both available, and the dashboard exposes request-level usage reporting with CSV export — date, host, requests, traffic, charged traffic, success or error. Live chat is human-staffed; a recorded test had a named agent answering a technical session question in about seven minutes, with a complete answer closer to twelve.

Two terms to note before paying: there's no free tier, so the minimum spend to touch the network is $5, and the Intro plans carry a 7-day money-back guarantee for card payments provided less than 80% of traffic has been consumed. Crypto purchases on Intro plans are non-refundable. 👉 [Check the current intro terms before you top up](https://bit.ly/dataimPulse)

## Who should buy which

**Stick with Decodo if** you need the deepest benchmarked success rates on defended targets, you're under 100GB a month and value a polished dashboard and browser extension, or you want a broad catalogue including site unblockers and scraping APIs under one contract. Budget from the tier table, not the banner, and don't change plans mid-cycle.

**Use pay-as-you-go if** your volumes are unpredictable, you're testing provider fit, you're running several small projects on one balance, or you want traffic that survives a quiet quarter. That's a billing-model advantage rather than a network-quality one, and it's the reason the cheaper provider isn't automatically the worse one for your workload. 👉 [Open a $5 balance and test it on your own targets](https://bit.ly/dataimPulse)

**Test both if** your targets include anything genuinely well defended. Buy the smallest unit each one sells, run the same requests through each, and compare cost per successful page rather than cost per gigabyte. That comparison takes an afternoon and settles the question permanently.

## Three quick answers

**Is Smartproxy still a company?** No — it's Decodo, and it has been since 2025. Same infrastructure, new name. Avoid any domain using the old brand that isn't the official one.

**Why does the advertised price differ from what I'm charged?** Because "from" rates usually belong to the largest tier in the table. At Decodo, $2/GB requires a 1TB monthly commitment. Add VAT if you're billing from the EU.

**What's the cheapest way to get residential traffic today?** Volume pricing if you fill it, pay-as-you-go if you don't. At $1/GB with no expiry, a 40 GB spiky month costs $40 instead of a $150 tier you only half use.
