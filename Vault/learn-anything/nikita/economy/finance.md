# Finance

I use [Wise](https://wise.com/home/) as my bank and like it. When I lived in UK, [Monzo](https://monzo.com) was nice too.

I try keep a minimum of ~ 3000 euro cash on my account (for emergency spending + any monthly bills). Rest in [invested](investing.md) in strong assets. Often this minimum goal is aspirational and I try to get by with what I have.

Tax wise, at least in [Europe](../travel/visited/europe.md), you pay ~ 21% VAT every 3 months. You then pay income tax once a year, at least in [NL](../travel/visited/netherlands.md) all that's done through a website. Income tax is often progressive so amount you pay depends on how much you earned in the year.

I found asking [ChatGPT](../machine-learning/chatgpt.md) questions regarding taxes/finances very useful. Do double check though as model can hallucinate.

There are ways to avoid paying the tax if you don't stay a tax resident in any one country for prolonged time (usually 180 days). But I haven't tried doing that.

I do budgets on quarterly bases as I send in my revenue for 3 months to pay VAT tax. Anything beyond the 3000 cash goal gets invested into my [portfolio of stocks/ETFs](investing.md) at each end of month. Might automate it at some point.

Aside from investing in ETFs, I use the money to invest in [ideas that interest me](../ideas/index.md). Pay [open source](../open-source/index.md) contributors whose libraries I like. And generally try to give back to community on whose work I build on.

I try reflect on my progress both financial and otherwise as part of my [look backs](../looking-back/index.md).

I want to build an app to help manage my finances better as well keep track of invoices I send and which invoices I paid out more easily too. Currently it's quite messy. I tried using [Notion](../tools/notion.md) for it and it looked something like:

![](https://i.imgur.com/w8CuFdU.png)

In some ways it's a light variation of [YNAB methodology](https://www.youneedabudget.com/method/). Goal is to be mindful of how the money gets spent monthly to make projections into future. Thus removing anxiety for potential future unforseen expenses.

I try to be mindful of more expensive things I buy but do try to never disregard spending money on quality [healthy food](../health/nutrition/foods.md) and essentials for my [well being](../life/happiness.md). All modern banks including Wise track spending into categories automatically.

As mentioned above, I want to build an app that would automate all things financing, safe investing & bookkeeping for me. Where tax is optimized based on all information that is available to me and payment of tax is easy as all the bookkeeping details are neatly organized.

[Fey](https://www.feyapp.com/) app looks interesting in this regard although it's focused on investing. Also [Mercury](https://mercury.com/) seems like a great bank I might move to. I am still new to managing finances in startups.

The app should:

1. Read live data from my bank(s)
2. All expenses automatically categorized (I should be able to instantly see how much was spent on what and how that change over last month or any other time period) (can get categories either from bank itself or write my own classifier)
3. Ability to make projections based on historical data
4. Ability to set goals on total value of assets
5. Ability to set limits on categories and ideally have the bank enforce those limits or at least remind me when I went over the limit as the app reads live data from the bank as each transaction gets made

For connecting to real time bank data, maybe [Nordigen](https://nordigen.com/en/) or [Tink](https://tink.com) can be used. Hopefully it's not too expensive to do.

[Actual Budget](https://actualbudget.com/) is in some ways close to what the UI for such an app should look like but it doesn't let you connect to EU banks.

[This person's Notion setup](https://twitter.com/heyeaslo/status/1591619161406713858) is close to the idea too.

It would also be nice to automate moving money from main account to good ETFs I select. FIAT [tends to deprecate quickly](https://twitter.com/levelsio/status/1471046183141265409) so it's good idea to own hard assets ([good ETFs](investing.md#Interesting-ETFs) being the safest investment).

I use [Interactive Brokers](https://www.interactivebrokers.co.uk/en/home.php) currently to make investments but honestly wish there was something better. The UI/UX of IB is horrendous but you can't easily purchase ETFs in any other app as EU citizen (I think at least).

If I needed a bank in US, I'd probably use [Mercury](https://mercury.com/) or [Column](https://news.ycombinator.com/item?id=31109170)

In EU, I'd use [Wise](https://wise.com/).

For processing payments on websites/apps, [Stripe Payment Links](https://stripe.com/en-nz/payments/payment-links) are easy to setup but the [pricing is steep](https://news.ycombinator.com/item?id=34609182) so avoid Stripe now in favor of [Adyen](https://www.adyen.com/).

Ideally Adyen builds better integration points with as much care into integrations as Stripe has.

[Lemon Squeezy](https://www.lemonsqueezy.com/) is nice tool to simply sell items online. [Paddle](https://www.paddle.com/) is [nice too](https://news.ycombinator.com/item?id=31522127). There are [other options](https://twitter.com/JordanMorgan10/status/1604324809583857664) though.

My personal goal though is to minimize fees I pay on each transaction over how nice DX is as I can abstract that away. Thus Adyen seems like a perfect company.

In future I'd love to build some things on top of global payment infrastructure and get those fees closer to minimum as possible. Perhaps by building on something like [TrueLayer](https://truelayer.com/) as you need a banking license to innovate in fin tech.

Use [Invoice Generator](https://invoice-generator.com/#/1) or [Cakedesk](https://cakedesk.app/) to create invoices but I do need to make something even nicer and more automated for my use cases.

Ideally anything related to finances is automated as much as possible for me.

[Minimum Viable Finance](https://www.causal.app/blog/the-ultimate-guide-to-finance-for-seed-series-a-companies) is a nice article to read to get a better sense of things you need to know as you try finance your own [startup](../business/startups/index.md).

> Want to study all the financial crisis that happened across history and understand the root causes of each one. Specifically I don't fully understand the importance of raising/lowering interest rates and how it influences the economy.

## Ongoing subscriptions

I use [Bobby](https://itunes.apple.com/us/app/bobby-track-subscriptions/id1059152023?mt=8) iOS app to track my ongoing subscriptions. I review it monthly as part of my finance check up. The app I mentioned above will cover the use case of Bobby too so hopefully I won't need this app in future.

![](https://images.nikiv.dev/bobby-22.png)

## Tracking what to buy next

I use [2Do](../macOS/apps/2do.md) to track what things I want to buy next. These are just tasks with `buy` tag in 2Do sorted by priority. Here is how it looks:

![](https://i.imgur.com/UsmrqL3.jpg)

## Notes

- FI is possible everywhere. The idea stays the same, save more than you spend, try generate passive income through stocks, dividends and property.
- [I think most people are going to mention credit cards in some way, but for me, it was how my actual bank accounts don't matter. It doesn't matter if I have $X in my savings and $Y in my checking account. I have $(X+Y) to budget and I need to budget $X for an emergency fund.](https://www.reddit.com/r/ynab/comments/908iob/what_was_the_hardest_part_of_ynab_for_you_to/)
  - Also, having $Z left over after budgeting doesn't mean I have $Z to blow. I have $Z to budget for next month since I already budgeted for my frivolous spending. That doesn't mean I don't just move $Z to something frivolous anyways.
- [It's a different way of thinking about budgeting. It's an envelope system. You have a pile of dollars (real dollars - these are all the dollars you own, right now, in your accounts), and a pile of envelopes. You begin stuffing dollar bills into envelopes - some into the bills coming due before you get paid again, some for groceries until you get paid again, some for gas until you get paid again, and with the smaller pile of dollars after those needs are taken care of, you begin to stuff dollars into your True Expenses - things like Car Maintenance, Insurance Payment, etc. When you run out of dollars, you STOP.](https://www.reddit.com/r/ynab/comments/93l0gm/im_missing_something_here_possibly_a_brain/)
  - You stop, because you can't put imaginary dollars into envelopes.
  - YNAB is all about the now - about giving jobs to the money you have. Not to the money you might have later on. It is a different way of thinking, but once you make that mental shift, it comes clear and works beautifully.
- [Invoiced has great invoice generator.](https://invoice-generator.com/#/1)
- [IBKR trades currency for you on the actual market at whatever price it's currently trading. No fee. Perfect for exchanging FIAT.](https://www.reddit.com/r/eupersonalfinance/comments/qswoo3/exchange_400k_usd_to_eur/)
- [After the financial crisis, banks were more tightly regulated, had to hold more capital, and the fed eventually started paying interest on excess reserves, so it should be fairly obvious that this means banks are encouraged to just park (some) of their reserves.](https://www.reddit.com/r/AskEconomics/comments/v16lhb/the_federal_reserves_balance_sheet_has_increased/)
- [You have 2 ways of receiving money, as an individual or as a company. If you need to spend your money you are going to be subject to personal income tax laws. There are 2 ways to reduce this kind of tax, run a legitimate business that enables you to write off big day to day spends (like run a catering company and you eat the food it buys) or move to a country with favourable income tax breaks for new residents (Greece/Spain). If you plan on saving your money then you can start a legitimate business in a country with low or zero income tax (Estonia, Caymen islands). That business could be to buy property or an investment vehicle, that way you can benefit from keeping more of the money pre tax accumulating in interest before it's taxed on your personal income tax. Saying all that, it's a lot of work to figure it all out and make the pieces fit, or expensive to hire a good accountant to figure it out for you. Especially if you have an average income where your only saving a few thousand I'm tax a year.](https://www.reddit.com/r/eupersonalfinance/comments/w6028r/what_is_an_effective_strategy_for_a_freelancer_or/)
- [If someone not paying their invoices for long time: First, create a paper trail of contact. Call them and follow up with an email documenting your call attempt and repeat your collection message. Continue this several more times as needed over several days. Only then escalate to an attorney letter. This process gives your attorney more firepower for the letter. Let them know they have x days until litigation, cc them with records of contact so they can't deny and let draft a very formal letter letting them know you have already taken steps to contact the people to take this to court. The very threat of having to deal with the court proceedings usually does the trick. I had the same thing happen (for less money mind you) after the letter was sent they paid almost the same day.](https://www.reddit.com/r/smallbusiness/comments/za71uf/client_not_paying_invoices_worth_20000_its_been/)
- [I call our cell phone/ internet company every once in awhile and ask for a discount. It's normally works. Just got a $25 discount off our cell/internet bill today. You can always look up rates of competitors and then claim you are going to switch. That normally gets them to go lower.](https://www.reddit.com/r/Fire/comments/zp1l39/what_are_some_unique_but_effective_ways_youve/)
- [VAT is about where the sale takes place, which for online digital goods is where the customer is, not where the business is.](https://www.reddit.com/r/eupersonalfinance/comments/123u9hw/do_i_have_to_charge_vat_if_my_company_is_eubased/)
- [US sales tax is not a VAT. If you're selling online goods and services, you only need to pay US sales tax if you have a "nexus" or presence in that state. That means you're either physically present there, have an office or factory or equipment in that state, OR if you're above certain limit (in $ terms). This varies per state. Google "sales tax nexus for online services" or similar keywords. If you're a EU company, the VAT is calculated based on the sale "location". For digital services (IIRC for digital goods as well) it's location of the user. Meaning if your user is US based, no VAT.](https://www.reddit.com/r/eupersonalfinance/comments/123u9hw/do_i_have_to_charge_vat_if_my_company_is_eubased/)

## Links

- [Important saving goals people should have](https://www.reddit.com/r/ynab/comments/8d4ab4/what_is_the_best_approach_for_budgeting_savings/)
- [The Shockingly Simple Math Behind Early Retirement](https://www.mrmoneymustache.com/2012/01/13/the-shockingly-simple-math-behind-early-retirement/)
- [Ask HN: What to do after \$8M (all cash, post tax) exit? (2018)](https://news.ycombinator.com/item?id=18600220)
- [Resources for those who want to better understand personal finance](https://github.com/kmt901/goodbye-money-confusion)
- [How to earn your Macroeconomics and Finance white belt (as a software developer) (2019)](https://notamonadtutorial.com/how-to-earn-your-macroeconomics-and-finance-white-belt-as-a-software-developer-136e7454866f)
- [Ask HN: Best Passive Income Method? (2019)](https://news.ycombinator.com/item?id=20052668)
- [What were the most influential learning resources you found while discovering FIRE? (2019)](https://www.reddit.com/r/financialindependence/comments/c9yan7/what_were_the_most_influential_learning_resources/)
- [Ask HN: What did you do when you suddenly got rich? (2019)](https://news.ycombinator.com/item?id=20521902)
- [Prophet](https://github.com/Emsu/prophet) - Financial markets analysis framework for programmers.
- [Financial Markets course](https://www.coursera.org/learn/financial-markets-global) - Overview of the ideas, methods, and institutions that permit human society to manage risks and foster enterprise.
- [QuantStack](https://quantstack.net/) - Team of developers and contributors of major open-source projects for scientific computing, who are passionate about science and technology.
- [Self-Study Plan for Becoming a Quantitative Developer](https://www.quantstart.com/articles/Self-Study-Plan-for-Becoming-a-Quantitative-Developer)
- [QuantLib](https://github.com/lballabio/QuantLib) - Free/open-source C++ library for quantitative finance.
- [Quadratic Payments: A Primer (2019)](https://vitalik.ca/general/2019/12/07/quadratic.html) ([HN](https://news.ycombinator.com/item?id=21737237))
- [A Primer on Investing for Designers and Developers (2019)](https://brianlovin.com/overthought/investing-for-designers-and-developers)
- [Roki](https://rotki.com/) - Open source asset analytics, tracking, management and tax reporting application that enables you to take ownership of your financial data. ([Code](https://github.com/rotki/rotki))
- [How to build wealth slowly](https://pjrvs.com/wealth)
- [HN: Reddit has become a guide to personal finance (2020)](https://news.ycombinator.com/item?id=22478854)
- [Ask HN: Book recommendations for understanding financial systems? (2020)](https://news.ycombinator.com/item?id=22573204)
- [HN: Dow Falls 2997 points worst drop since 1987 crash (2020)](https://news.ycombinator.com/item?id=22597192)
- [The Good Times for Airlines Are Over (2020)](https://www.bloomberg.com/opinion/articles/2020-03-17/the-good-times-for-airlines-are-over) - Also startup liquidity, trading from home and virus blockchain.
- [Ask HN: How bad will the 2020 economic crisis be?](https://news.ycombinator.com/item?id=22654131)
- [The ladders of wealth creation: a step-by-step roadmap to building wealth (2019)](https://nathanbarry.com/wealth-creation/)
- [Simple Personal Finance Tracking with GnuCash (2020)](https://www.csun.io/2020/05/17/gnucash-finance.html) ([HN](https://news.ycombinator.com/item?id=23237445))
- [Which books have been the most influential on your fatFIRE journey? (2020)](https://www.reddit.com/r/fatFIRE/comments/gpm6d0/which_books_have_been_the_most_influential_on/)
- [Gather](https://www.usegather.com/) - Collaborative finance tool.
- [Stripe](https://stripe.com/en-nl) - Online payment processing for internet businesses.
- [Financial Statements: A Beginner's Guide (2020)](https://www.causal.app/blog/whats-a-financial-statement) ([HN](https://news.ycombinator.com/item?id=23825606))
- [Awesome Foundations of Decentralized Finance (DeFi)](https://github.com/Mikerah/awesome-foundations-of-DeFi)
- [Why Credit Card Fraud Is Still a Thing (2020)](https://krebsonsecurity.com/2020/07/heres-why-credit-card-fraud-is-still-a-thing/) ([HN](https://news.ycombinator.com/item?id=23990960))
- [Ask HN: Do you have a daily cash stream? (2020)](https://news.ycombinator.com/item?id=24047683)
- [Best countries for FIRE? (2020)](https://www.reddit.com/r/EuropeFIRE/comments/i5gpeh/best_countries_for_fire/)
- [Mollie](https://www.mollie.com/en) - Effortless payments.
- [Awesome AI in Finance](https://github.com/georgezouq/awesome-ai-in-finance)
- [Paysend](https://paysend.com/) - Send money internationally. Nice for sending money to Russia at low (no) cost.
- [Tax strategies for large earnings surge (2020)](https://www.reddit.com/r/fatFIRE/comments/jdrl4a/tax_strategies_for_large_earnings_surge/)
- [Ask HN: Why isn’t finance a part of the core curriculum at schools? (2020)](https://news.ycombinator.com/item?id=24877408)
- [TrueLayer](https://truelayer.com/) - Simple Open Banking APIs. Build applications that securely access data and initiate payments in real time. ([GitHub](https://github.com/TrueLayer)) ([CLI](https://github.com/TrueLayer/truelayer-cli))
- [11FS](https://11fs.com/) - Creating digital financial services for banks.
- [Interview Primer for Quantitative Finance](https://github.com/dwcoder/QuantitativePrimer) ([PDF](https://github.com/dwcoder/QuantitativePrimer/blob/master/src/QuantitativePrimer.pdf))
- [Stripe Treasury](https://stripe.com/treasury) - Banking-as-a-service for platforms. ([Tweet](https://twitter.com/patio11/status/1334518202886328320)) ([HN](https://news.ycombinator.com/item?id=25289626))
- [Mercury Treasury](https://mercury.com/treasury) - Automatic cash management for high-growth startups.
- [The Games People Play with Cash Flow (2020)](https://commoncog.com/blog/cash-flow-games/) ([HN](https://news.ycombinator.com/item?id=25357669))
- [How Payment Transaction Processing Works (2020)](https://blog.privacy.com/how-payment-transactions-work/) ([HN](https://news.ycombinator.com/item?id=25332516))
- [Stripe’s payments APIs: the first ten years (2020)](https://stripe.com/blog/payment-api-design) ([HN](https://news.ycombinator.com/item?id=25455638))
- [Ask HN: About Financial Inequity (2020)](https://news.ycombinator.com/item?id=25504017)
- [hledger](https://github.com/simonmichael/hledger) - Cross-platform accounting software for both power users and folks new to accounting. ([Docs](https://hledger.org/))
- [Mintable](https://github.com/kevinschaich/mintable) - Automate your personal finances – for free, with no ads, and no data collection.
- [Awesome Financial Networks](https://github.com/gautier-marti/awesome-financial-networks)
- [Avera](https://avera.area120.com/) - Financial computation for the future.
- [Matt Levine: Money Stuff and Life Stuff Interview (2019)](https://www.youtube.com/watch?v=Knni2SjQvUs)
- [Finance Database](https://github.com/JerBouma/FinanceDatabase) - Database of 180.000+ symbols containing Equities, ETFs, Funds, Indices, Futures, Options, Currencies, Cryptocurrencies and Money Markets.
- [Every thought about personal finance I've ever had, as concisely as possible (2021)](https://blog.aadilali.com/posts/personal-finance.html) ([HN](https://news.ycombinator.com/item?id=26281108))
- [Finance as culture (2021)](https://luttig.substack.com/p/finance-as-culture) ([Tweet](https://twitter.com/absoluttig/status/1366191939930918915))
- [pValuation](https://github.com/robertmartin8/pValuation) - Quantamental finance research with python.
- [Python for Finance Book](https://home.tpq.io/books/py4fi/) - Mastering Data-Driven Finance. ([Code](https://github.com/yhilpisch/py4fi2nd))
- [On the Experience of Being Poor-Ish, for People Who Aren't (2021)](https://residentcontrarian.substack.com/p/on-the-experience-of-being-poor-ish) ([HN](https://news.ycombinator.com/item?id=26300139))
- [The Joy of Fuck-You Money (2018)](https://thedeepdish.org/fuck-you-money/) ([HN](https://news.ycombinator.com/item?id=26426915))
- [Good basic couple finance courses/books (2021)](https://twitter.com/kylemathews/status/1371290275478302721)
- [Early-Retirement Update (2021)](https://livingafi.com/2021/03/17/the-2021-early-retirement-update/) ([HN](https://news.ycombinator.com/item?id=26543527))
- [Short term investing tips (2021)](https://www.reddit.com/r/eupersonalfinance/comments/mewykz/12k_in_savings_1kmonth_extra_income_to_invest/)
- [VISA USDC coin explained (2021)](https://twitter.com/terryangelos/status/1376539932588531714)
- [Why Python is huge in finance? by Daniel Roos (2019)](https://www.youtube.com/watch?v=kBwOy-6CtAQ)
- [aat](https://github.com/AsyncAlgoTrading/aat) - Asynchronous, event-driven algorithmic trading in Python and C++.
- [Tips to diversify income with passive income streams (2021)](https://twitter.com/johndsaunders/status/1379390180445065219)
- [Checkout.com](https://www.checkout.com/) - Accept Payments Online.
- [Interactive financial modeling (2021)](https://www.youtube.com/watch?v=h1BGy6CV1co)
- [Maybe](https://maybe.co/) - Modern financial planning & investment management.
- [How People Get Rich Now (2021)](http://paulgraham.com/richnow.html) ([HN](https://news.ycombinator.com/item?id=26781052)) ([Reddit](https://www.reddit.com/r/slatestarcodex/comments/mpteal/how_people_get_rich_now_by_paul_graham/))
- [Just Be Rich (2021)](https://keenen.xyz/just-be-rich/) ([HN](https://news.ycombinator.com/item?id=26787654))
- [Learning Decentralized Finance](https://github.com/ajlopez/LearningDeFi)
- [Introduction to Machine Learning for Finance](https://algofin.substack.com/p/ml-101-an-introduction) ([HN](https://news.ycombinator.com/item?id=26868051))
- [The Greshm System (2021)](https://www.greshm.org/files/greshm.pdf) ([HN](https://news.ycombinator.com/item?id=26884532))
- [Balance](https://www.getbalance.com/) - B2B Payments for Merchants & Marketplaces.
- [finance-dl](https://github.com/jbms/finance-dl) - Tools for automatically downloading/scraping personal financial data.
- [Circle](https://www.circle.com/en/) - Payments infrastructure for internet businesses.
- [The Ultimate Guide to Inflation](https://www.lynalden.com/inflation/) ([HN](https://news.ycombinator.com/item?id=27099536))
- [Why Open Source Finance Will Win. (2019)](https://medium.com/balance-io/why-open-source-finance-will-win-a1f3a61544c2)
- [Lean FIRE Reddit Wiki](https://www.reddit.com/r/leanfire/wiki/index)
- [Anyone Retire in a LCOL Country and Regret it? (2021)](https://www.reddit.com/r/leanfire/comments/nfq3p7/anyone_retire_in_a_lcol_country_and_regret_it/)
- [Exec Sum](https://execsum.co/) - Daily Finance & Business Newsletter.
- [How to Get Rich without Being Lucky (2019)](https://nav.al/rich) ([HN](https://news.ycombinator.com/item?id=27245680))
- [DeFi Beyond the Hype – Wharton (2021)](https://wifpr.wharton.upenn.edu/wp-content/uploads/2021/05/DeFi-Beyond-the-Hype.pdf)
- [Stripe Payment Links](https://stripe.com/payments/payment-links) - Create a payment page in just a few clicks and share the link with your customers. ([Tweet](https://twitter.com/stripe/status/1397246058166632456)) ([HN](https://news.ycombinator.com/item?id=27280096))
- [Awesome Quant](https://github.com/wilsonfreitas/awesome-quant)
- [Personal Finance Reddit Wiki](https://www.reddit.com/r/personalfinance/wiki/index)
- [FerrumFIX](https://github.com/neysofu/ferrum-fix) - Financial Information eXchange protocol implemented in Rust.
- [If You Want To Transform IT, Start With Finance (2021)](https://zwischenzugs.com/2021/07/12/if-you-want-to-transform-it-start-with-finance/) ([HN](https://news.ycombinator.com/item?id=27825211))
- [Awesome Decentralized Finance](https://github.com/ong/awesome-decentralized-finance)
- [Spreadsheet formulas for personal finance (2021)](https://bou.ke/blog/formulas/) ([HN](https://news.ycombinator.com/item?id=28037317))
- [Best software for submitting receipts](https://twitter.com/maccaw/status/1424826881828954123)
- [TigerBeetle](https://github.com/coilhq/tigerbeetle) - Distributed financial accounting database designed for mission critical safety and performance to power the future of financial services. ([Web](https://www.tigerbeetle.com/)) ([Why need it](https://twitter.com/phil_eaton/status/1568247444684554241)) ([HN](https://news.ycombinator.com/item?id=32779851))
- [Go DB Ledger](https://github.com/darcys22/godbledger) - Accounting Software with GRPC endpoints and SQL Backends. ([Web](https://godbledger.com/))
- [How you can track your personal finances using Python (2021)](https://sgoel.dev/posts/how-you-can-track-your-personal-finances-using-python/) ([HN](https://news.ycombinator.com/item?id=28418925))
- [Invoy](https://invoy.app/) - Super simple invoicing. ([Twitter](https://twitter.com/invoyco))
- [Increase](https://increase.com/) - Build your own bank. From the Federal Reserve, directly to our own API endpoints. ([HN](https://news.ycombinator.com/item?id=32828669))
- [Pandora Papers](https://www.icij.org/investigations/pandora-papers/) - Largest investigation in journalism history exposes a shadow financial system that benefits the world’s most rich and powerful. ([Article](https://www.theguardian.com/news/2021/oct/03/pandora-papers-biggest-ever-leak-of-offshore-data-exposes-financial-secrets-of-rich-and-powerful)) ([HN](https://news.ycombinator.com/item?id=28738407)) ([HN](https://news.ycombinator.com/item?id=28738450)) ([Reddit](https://www.reddit.com/r/worldnews/comments/q0ibjr/pandora_papers_most_expansive_expose_of_financial/)) ([Reddit](https://www.reddit.com/r/worldnews/comments/q0v52w/pandora_papers_biggest_ever_leak_of_offshore_data/))
- [ExpatFinance.us](https://www.expatfinance.us/home) - Resources for bureaucratic and financial matters when moving to a new country.
- [Stripe's low-hanging fruits (2021)](https://twitter.com/patrickc/status/1450208990974021635)
- [How you can track your personal finances using Python](https://sgoel.dev/posts/how-you-can-track-your-personal-finances-using-python/) ([Lobsters](https://lobste.rs/s/uq4vpy/how_you_can_track_your_personal_finances))
- [How credit cards make money (2021)](https://bam.kalzumeus.com/archive/how-credit-cards-make-money/) ([HN](https://news.ycombinator.com/item?id=29121353))
- [Bits about Money by Patrick McKenzie (patio11)](https://bam.kalzumeus.com/) - About the modern financial infrastructure that the world sits atop of.
- [Stripe for book-keeping tools (2021)](https://twitter.com/maccaw/status/1457509961970372608)
- [Which Stripe improvement you want to see most (2021)](https://twitter.com/patrickc/status/1458263819776512001)
- [Debit cards are hidden financial infrastructure (2021)](https://bam.kalzumeus.com/archive/debit-cards-are-hidden-financial-infrastructure/) ([HN](https://news.ycombinator.com/item?id=29206462))
- [Breaking down the 'payment for order flow' debate (2021)](https://a16z.com/2021/02/17/payment-for-order-flow/) ([HN](https://news.ycombinator.com/item?id=29210628))
- [Wise](https://wise.com/) - Online Money Transfers | International Banking Features.
- [An Introduction to Machine Learning in Quantitative Finance](https://github.com/deepintomlf/mlfbook)
- [Modern Treasury](https://www.moderntreasury.com/) - Makes payment operations simple, scalable and secure.
- [Ucelofka](https://github.com/shenek/ucelofka) - Simple program to issue invoices (CLI/Web).
- [Building Stripe Tax (2021)](https://stripe.com/blog/building-stripe-tax)
- [Arc Invoice](https://arcinvoice.com/) - Free Invoicing App for Freelancers and Small Businesses. ([Code](https://github.com/Panshak/arcinvoice))
- [Monzo](https://monzo.com/) - Online bank based in the United Kingdom. ([GitHub](https://github.com/monzo)) ([Awesome](https://github.com/rdingwall/awesome-monzo))
- [Wealthsimple](https://www.wealthsimple.com/en-gb/) - Powerful financial tools to help you grow and manage your money. ([Twitter](https://twitter.com/wealthsimple))
- [Bank transfers as a payment method (2021)](https://bam.kalzumeus.com/archive/bank-transfers-as-a-payment-method/) ([HN](https://news.ycombinator.com/item?id=29357215))
- [Advances in Financial Machine Learning](https://github.com/jjakimoto/finance_ml)
- [Primer](https://primer.io/) - No code automation for payments.
- [Quant-Finance-Resources](https://github.com/PyPatel/Quant-Finance-Resources)
- [Awesome-Quant-Machine-Learning-Trading](https://github.com/grananqvist/Awesome-Quant-Machine-Learning-Trading)
- [Awesome Deep Trading](https://github.com/cbailes/awesome-deep-trading)
- [Learn Accounting for Free](https://www.accountingcoach.com/) ([HN](https://news.ycombinator.com/item?id=29625571))
- [Scamwicks and Stop Cascades (2021)](https://www.machow.ski/posts/scamwicks-and-stop-cascades/)
- [Leverage, Liquidation and Insurance Funds (2021)](https://www.machow.ski/posts/leverage_liquidation_and_insurance_funds/)
- [On Being Broke](https://thomasjbevan.substack.com/p/on-being-broke) ([HN](https://news.ycombinator.com/item?id=30234518))
- [Plaid](https://plaid.com/en-eu/) - Enabling all companies to build fintech solutions. ([GitHub](https://github.com/plaid)) ([Docs](https://plaid.com/docs/)) ([React Plaid Link](https://github.com/plaid/react-plaid-link))
- [Actual](https://actualbudget.com/) - Super fast privacy-focused app for managing your finances. ([GitHub](https://github.com/actualbudget)) ([Code](https://github.com/actualbudget/actual)) ([Tweet](https://twitter.com/jlongster/status/1520063046101700610)) ([Going open source](https://actualbudget.com/open-source)) ([HN](https://news.ycombinator.com/item?id=31206536)) ([Server Code](https://github.com/actualbudget/actual-server))
- [Finality does not exist in payments (2022)](https://bam.kalzumeus.com/archive/no-payments-are-final/) ([HN](https://news.ycombinator.com/item?id=30350547))
- [Financial advice after a decade in tech (2022)](https://www.reddit.com/r/cscareerquestions/comments/swdgiq/financial_advice_after_a_decade_in_tech/)
- [Quick breakdown of what SWIFT is and why it matters](https://twitter.com/SahilBloom/status/1496861068945154056) ([HN](https://news.ycombinator.com/item?id=30456026))
- [Difference between SWIFT sanctions and targeted bank sanctions](https://twitter.com/daniel_mcdowell/status/1496985031205703683)
- [If SWIFT is banned, what then?](https://twitter.com/EmilyGorcenski/status/1497591347997384715)
- [SWIFT ELI5](https://www.reddit.com/r/worldnews/comments/t20u4i/comment/hyj4lio/?context=3)
- [TopHat](https://github.com/Athenodoros/TopHat) - Offline-first personal finances app.
- [Tell HN: SWIFT is not a payments transfer system (2022)](https://news.ycombinator.com/item?id=30510928)
- [Moving money internationally (2022)](https://bam.kalzumeus.com/archive/moving-money-internationally/) ([HN](https://news.ycombinator.com/item?id=30535225))
- [How international money transfers work (2016)](https://media.ccc.de/v/33c3-8315-a_world_without_blockchain) ([HN](https://news.ycombinator.com/item?id=30540125))
- [Numary Ledger](https://github.com/numary/ledger) - Programmable financial ledger that provides a foundation for money-moving applications.
- [Why Moneyball is the best movie about trading ever made](https://twitter.com/AgustinLebron3/status/1505588577446490112)
- [Антикризисный риск-менеджмент личных финансов](https://github.com/codez0mb1e/resistance)
- [Sage](https://github.com/JohnStarich/sage) - Download from your banks and credit cards straight to your computer.
- [How to Escape Your Country’s Tax System (2022)](https://www.youtube.com/watch?v=W9xfjU6Hq-k)
- [Short course on Survival Analysis applied to the Financial Industry](https://github.com/sestelo/sa_financial)
- [Link](https://link.co/) - Simple, secure one-click payments by Stripe. ([HN](https://news.ycombinator.com/item?id=31030761))
- [Buy. Borrow. Die. | How The Rich Stay Rich](https://www.youtube.com/watch?v=4_XFqwN9zLU)
- [ProjectionLab](https://projectionlab.com/) - Simulate your Financial Future. Plan for Financial Independence. ([HN](https://news.ycombinator.com/item?id=31083093))
- [Ramp](https://ramp.com/) - Corporate cards and finance automation that scales with you.
- [Column](https://column.com/) - Nationally charted bank for developers. ([HN](https://news.ycombinator.com/item?id=31109170)) ([Twitter](https://twitter.com/columnbank))
- [Tracking Progress in FinNLP](https://github.com/YangLinyi/FinNLP-Progress)
- [FinQA: A Dataset of Numerical Reasoning over Financial Data (2021)](https://arxiv.org/abs/2109.00122) ([Code](https://github.com/czyssrs/FinQA))
- [NLP papers applicable to financial markets](https://github.com/maximedb/nlp_papers)
- [Deep Finance](https://github.com/sangyx/deep-finance) - Datasets, papers and books on AI & Finance.
- [Do very rich people bother with a pension? (2022)](https://www.reddit.com/r/UKPersonalFinance/comments/ubis8o/do_very_rich_people_bother_with_a_pension/)
- [Fintopea](https://www.fintopea.com/) - Free financial visualizations of publicly listed companies. ([Code](https://github.com/RaymondMoay/fintopea)) ([HN](https://news.ycombinator.com/item?id=31192956))
- [Polygon.io](https://polygon.io/) - Stock Market Data APIs.
- [Best payment processor out there that acts as a merchant of record (2022)](https://twitter.com/adamwathan/status/1520371027771117568)
- [Beancount](https://github.com/beancount/beancount) - Double-Entry Accounting from Text Files. ([Rust Tooling](https://github.com/twilco/beancount))
- [Stripe Financial Connections](https://stripe.com/en-gb-nl/financial-connections) ([HN](https://news.ycombinator.com/item?id=31262361))
- [How to have a billion dollar exit with zero capital gains tax (2022)](https://axiomalpha.com/how-to-use-the-unlimited-tax-loophole/) ([HN](https://news.ycombinator.com/item?id=31320519))
- [Xolo Go](https://www.xolo.io/zz-en/go) - Invoice clients in the EU, USA and Canada without registering a company.
- [Ask HN: Is There Hope for Micropayments? (2022)](https://news.ycombinator.com/item?id=31386483)
- [Tips for financial responsibility](https://twitter.com/Rational_Answer/status/1023120471926218753)
- [Stripe App Marketplace](https://marketplace.stripe.com/) ([HN](https://news.ycombinator.com/item?id=31494001)) ([Tweet](https://twitter.com/auchenberg/status/1529131505364062208))
- [Ask HN: How do you record your personal finances? (2022)](https://news.ycombinator.com/item?id=31605741)
- [Awesome Systematic Trading](https://github.com/wangzhe3224/awesome-systematic-trading)
- [tessa](https://github.com/ymyke/tessa) - Find financial assets and get their price history without worrying about different APIs or rate limiting.
- [Inflation is structural](https://twitter.com/Trinhnomics/status/1534046184032964609)
- [Nordigen](https://nordigen.com/en/) - Free banking data & premium insights.
- [Stripe Apps](https://stripe.com/docs/stripe-apps) - Lets you embed custom user experiences directly in the Stripe Dashboard and orchestrate the Stripe API. ([Code](https://github.com/stripe/stripe-apps))
- [ExpatFIRE Reddit](https://www.reddit.com/r/ExpatFIRE/)
- [Lessons you learned about money and personal finance?](https://twitter.com/ankurnagpal/status/1541417358815789057)
- [greeks](https://github.com/streamlet-dev/greeks) - Library for modeling financial instruments using lazy and/or streaming graphs.
- [Free invoice builder](https://app.freeinvoicebuilder.com/)
- [Books to read to understand financial crime (2022)](https://www.economist.com/the-economist-reads/2022/07/11/the-best-books-to-read-to-understand-financial-crime) ([HN](https://news.ycombinator.com/item?id=32091288))
- [Serverless Invoices](https://invoices.mokuapp.io/) - Free invoicing tool for freelancers and small businesses. ([Code](https://github.com/mokuappio/serverless-invoices))
- [Understanding Jane Street (2022)](https://www.thediff.co/p/jane-street) ([HN](https://news.ycombinator.com/item?id=32314623))
- [Living on $100k - How much I spend in a month (2022)](https://www.youtube.com/watch?v=qNj2rAyhQbM)
- [Exchange-core](https://github.com/exchange-core/exchange-core) - Open source market exchange core.
- [FinTA](https://github.com/peerchemist/finta) - Common financial technical indicators implemented in Pandas.
- [ISO8583](https://github.com/moov-io/iso8583) - Implements an ISO 8583 message reader and writer. Give developers an easy way to create and integrate bank processing into their own software products.
- [Ask HN: How do you and your spouse handle big income differences? (2022)](https://news.ycombinator.com/item?id=32586361)
- [Ask HN: Why hasn't the ACH system been more abused? (2022)](https://news.ycombinator.com/item?id=32641259)
- [It’s not what you earn, it’s what you get to keep. My 10 favorite tax hacks for business owners.](https://twitter.com/baldridgecpa/status/1568961457878110211)
- [Tiingo Python](https://github.com/hydrosquall/tiingo-python) - Python client for interacting with the Tiingo Financial Data API (stock ticker and news data).
- [Venice](https://github.com/usevenice/venice) - Fastest way to get financial data from Plaid into your Postgres database. Go from zero to production in 5 minutes without a single line of code.
- [Orderbook: an experimental order filling engine written in Go (2022)](https://dylanlott.com/orderbook/) ([Lobsters](https://lobste.rs/s/ml37oz/orderbook_experimental_order_filling))
- [ginvoicer](https://github.com/tinyzimmer/ginvoicer) - Command line utility and library for generating professional looking invoices in Go.
- [Tips with using Stripe Checkout (2022)](https://twitter.com/MeredithNeyrand/status/1580251338276945920)
- [Kill Bill](https://github.com/killbill/killbill) - Open-Source Subscription Billing and Payments Platform. ([Web](https://killbill.io/)) ([HN](https://news.ycombinator.com/item?id=33263603))
- [MarketStore](https://github.com/alpacahq/marketstore) - DataFrame Server for Financial Timeseries Data.
- [What's That Charge?!](https://www.whatsthatcharge.com/) - Identify those mysterious charges on your credit card statement.
- [Tier](https://github.com/tierrun/tier) - Terraform for Stripe. ([HN](https://news.ycombinator.com/item?id=33429972))
- [Adyen](https://www.adyen.com/) - End-to-end payments, data, and financial management in a single solution.
- [tick-rs](https://github.com/tarkah/tickrs) - Real time ticker data in your terminal. Built with Rust. Data sourced from Yahoo! Finance.
- [Algo-Trader](https://github.com/idanya/algo-trader) - Trading bot with support for real time trading, backtesting, custom strategies and much more.
- [Wallstreet](https://github.com/mcdallas/wallstreet) - Real time Stock and Option tools.
- [Demystifying Financial Leverage (2022)](https://bam.kalzumeus.com/archive/demystifying-financial-leverage/) ([HN](https://news.ycombinator.com/item?id=33563555))
- [Puffin](https://github.com/siddhantac/puffin) - Simple Go TUI to manage personal finances (using hledger).
- [The Short-Term Predictability of Returns in Order Book Markets: a Deep Learning Perspective (2022)](https://arxiv.org/abs/2211.13777) ([Code](https://github.com/lorenzolucchese/deepOBs))
- [Expensify](https://www.expensify.com/) - Financial collaboration, centered around chat. ([Code](https://github.com/Expensify/App))
- [Stripe’s Pricing Breakdown](https://github.com/getlago/lago/wiki/Stripe%27s-real-pricing:-a-primer) ([HN](https://news.ycombinator.com/item?id=33920019))
- [Formance](https://www.formance.com/) - Modular developer platform to build and operate complex money flows of any size and shape. ([Code](https://github.com/formancehq/stack))
- [rust_ledger](https://github.com/ebcrowder/rust_ledger) - Rust implementation of ledger, the command line accounting tool.
- [Most impactful book read this year (2022)](https://www.reddit.com/r/fatFIRE/comments/zp4g1f/most_impactful_book_read_this_year/)
- [The infrastructure behind ATMs (2023)](https://www.bitsaboutmoney.com/archive/the-infrastructure-behind-atms/) ([HN](https://news.ycombinator.com/item?id=34221157))
- [ISO 8583 - Wikipedia](https://en.wikipedia.org/wiki/ISO_8583)
- [Order matching engine (orderbook) written in Rust](https://github.com/dgtony/orderbook-rs)
- [matching_engine](https://github.com/fmstephe/matching_engine) - Simple financial trading matching engine. Built to learn more about how they work.
- [How to Build an Exchange (2017)](https://www.youtube.com/watch?v=b1e4t2k2KJY)
- [Show HN: List of Stripe Alternatives (2023)](https://news.ycombinator.com/item?id=34281730)
- [Invoice Template – Figma](https://www.figma.com/community/file/1134906513047172687)
- [hyperswitch](https://github.com/juspay/hyperswitch) - Open Source Financial Switch to make payments fast, reliable and affordable. ([Web](https://hyperswitch.io/))
- [Sales calculations](https://github.com/chantelle-lingerie/sales) - Manage order calculations based on invoices, refunds, cancellations.
- [How to Live in Three Places and Save Taxes (2023)](https://www.youtube.com/watch?v=KAJTZGhSVK4)
- [Stripe Can’t Lose - But the the payments company’s dominance no longer seems inevitable (2023)](https://every.to/p/stripe-can-t-lose)
- [Ask HN: HN for Finance? (2023)](https://news.ycombinator.com/item?id=34706550)
- [Money Laundering and AML Compliance (2023)](https://www.bitsaboutmoney.com/archive/money-laundering-and-aml-compliance/) ([HN](https://news.ycombinator.com/item?id=34743896))
- [pdoc](https://github.com/OliverEvans96/pdoc) - Command-line invoice / receipt generator, which stores user/client/project info as YAML files, and produces PDFs.
- [Ask HN: What US bank post-SVB would you recommend? (2023)](https://news.ycombinator.com/item?id=35118725)
- [The End of Silicon Valley (Bank) (2023)](https://stratechery.com/2023/the-death-of-silicon-valley-bank/) ([HN](https://news.ycombinator.com/item?id=35134608))
- [Mercury Vault](https://mercury.com/vault) - Simple way to manage bank risk and protect every dollar they deposit. ([How it works](https://twitter.com/immad/status/1635302598831112192))
- [Minimum Viable Finance: The Guide for Seed/Series A Startups](https://www.causal.app/blog/the-ultimate-guide-to-finance-for-seed-series-a-companies) ([HN](https://news.ycombinator.com/item?id=35203260))
- [BloombergGPT: A Large Language Model for Finance (2023)](https://arxiv.org/abs/2303.17564) ([HN](https://news.ycombinator.com/item?id=35381036))
- [Payments 101 for a Developer](https://github.com/juspay/hyperswitch/wiki/Payments-101-for-a-Developer) ([HN](https://news.ycombinator.com/item?id=35714145))
- [Bank Failures Visualized](https://observablehq.com/@mbostock/bank-failures) ([HN](https://news.ycombinator.com/item?id=35795975))
- [Compotes](https://github.com/Orbitale/Compotes) - Small app to manage bank account operations and display rich analytics.
- [monetr](https://monetr.app/) - Budgeting application focused on planning for recurring expenses. ([Code](https://github.com/monetr/monetr))
- [Terzo AI](https://terzo.ai/) - Contract Intelligence and Analytics.
- [Bigcapital](https://bigcapital.ly/) - Open-source alternative to QuickBooks. ([Code](https://github.com/bigcapitalhq/bigcapital)) ([HN](https://news.ycombinator.com/item?id=36118990))
- [Data-Centric FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) - Open-source for Open Finance.
- [Pricing Money: A beginner's guide to money, bonds, futures and swaps](http://www.jdawiseman.com/books/pricing-money/Pricing_Money_JDAWiseman.html) ([HN](https://news.ycombinator.com/item?id=36358754))
- [Fuse](https://www.letsfuse.com/) - Unified API for financial data aggregators. ([HN](https://news.ycombinator.com/item?id=36494639))
