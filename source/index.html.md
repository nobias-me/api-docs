---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to the Nobias Finance API! These API endpoints can get information on various stocks and authors.

<aside class="notice">
These APIs are a work in progress and have not been deployed it. I will update this page as APIs are deployed, expect them to be available starting 13th April. Please mock these API responses in your code to test. (Which you should continue to do as a good practice even after the API is available)
</aside>

# Stocks

## Get news for a stock

```shell
curl "api.nobias.com/spotcheck/finance/stock/news/<stock_ticker>"
```

> The above command returns JSON structured like this:

```json
{
    "stock": "AAPL",
    "authors": {
        "ykolgK9XRyAbwg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Shares down after Teck Resources withdraws application for Frontier oilsands project",
                "content": "Shares in Teck Resources Ltd. are trading down four per cent after the company said citing uncertainty over climate policies.\n\nThe Vancouver-based company said it will take a $1.13-billion writedown on the Frontier project in Alberta, which was expected to create thousands of jobs but was also produce about four million tonnes of greenhouse gas emissions per year over 40 years. In a letter to the federal environment minister, Teck CEO and President Don Lindsay says investors and customers increa",
                "url": "https://globalnews.ca/news/6588417/teck-resources-withdraws-frontier-oilsands-project-shares/",
                "accurate": null,
                "date": "2020-02-24T16:18:55Z"
            }
        ],
        "UNi0qUHCa4lILA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Glenview State Bank Trust Dept. books some of its profits in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 03 February 2020 00:13 EST\n\nAs per SEC filings for Q3/2019, Glenview State Bank Trust Dept. (CIK:0001598244) was ranked 867 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Glenview State Bank Trust Dept. decreased its position in Apple by 550 shares (or 0.73%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 550 shares is estimated at USD141,951. At the ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y49-3FD1-JB4F-Y08K-00000-00",
                "accurate": true,
                "date": "2020-02-03T06:29:38Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Inc. to Post Q2 2020 Earnings of $2.77 Per Share, Piper Sandler Forecasts (NASDAQ:AAPL)",
                "content": "Apple logo \n\nApple Inc. (NASDAQ:AAPL) - Research analysts at  Piper Sandler reduced their Q2 2020 earnings per share estimates for Apple  in a report released on  Tuesday, February 18th. Piper Sandler analyst M. Olson now anticipates that the iPhone maker will earn $2.77 per share for the quarter, down from their previous forecast of $3.01. Piper Sandler  has a \"Overweight\" rating and a $343.00 price objective on the stock. Piper Sandler also issued estimates for Apple's FY2020 earnings at $13.5",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y80-FP71-DXK2-M0J6-00000-00",
                "accurate": null,
                "date": "2020-02-20T18:07:23Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Inc. Expected to Post FY2020 Earnings of $13.83 Per Share (NASDAQ:AAPL)",
                "content": "Apple logo \n\nApple Inc. (NASDAQ:AAPL) - Research analysts at  Piper Sandler boosted their FY2020 EPS estimates for Apple  in a note issued to investors on  Wednesday, January 29th. Piper Sandler analyst M. Olson now forecasts that the iPhone maker will post earnings per share of $13.83 for the year, up from their previous forecast of $13.01. Piper Sandler currently  has a \"Overweight\" rating and a $343.00 price target on the stock. Piper Sandler also issued estimates for Apple's Q4 2020 earnings",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3V-RMC1-JB40-X42F-00000-00",
                "accurate": null,
                "date": "2020-02-01T04:22:11Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple’s coronavirus warning was a foreshock for earnings. But investors shouldn’t freak out just yet",
                "content": "Apple’s surprise warning that it won’t meet its first quarter revenue guidance because of the coronavirus sent tremors through global financial markets. Investors awoke Tuesday to the idea that other companies with exposure to China might not meet their first quarter earnings expectations, either. \n\nThe billion dollar question: Is the financial fallout from coronavirus a short-term problem or a longer-term trend? \n \n“This could be a very short-lived one-quarter blip,” JJ Kinahan, chief market st",
                "url": "https://www.nashfm1027.com/news/the-coronavirus-outbreak-will-hurt-q1-earnings-heres-why-investors-shouldnt-freak-out-just-yet/",
                "accurate": null,
                "date": "2020-02-19T06:49:36Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Market Snapshot: Dow futures point to lower open as Apple says coronavirus outbreak will hurt sales",
                "content": "Share  Tweet  Share  Share  Email  U.S. equity benchmarks Tuesday are indicated lower after Apple Inc. said a viral outbreak in China would hurt its second-quarter results, reigniting fears that the global economy could be harmed. Markets in the U.S., were closed in observance of Presidents Day.                 Related Items:    Share  Tweet  Share  Share  Email",
                "url": "http://dbxnetwork.com/2020/02/18/market-snapshot-dow-futures-point-to-lower-open-as-apple-says-coronavirus-outbreak-will-hurt-sales/",
                "accurate": true,
                "date": "2020-02-18T14:09:51Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "Facebook \n\nTwitter \n\nPinterest \n\nWhatsApp \n\nLinkedin \n\nReddIt \n\nEmail \n\nTelegram \n\n© Reuters. FILE PHOTO: The Apple Inc. logo is seen hanging at the entrance to the Apple store on 5th Avenue in New York \n\n(Reuters) – Shares of Apple Inc (O:) fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain. \n\nThe drop in Apple’s stock i",
                "url": "https://www.businessmayor.com/coronavirus-threatens-apple-supply-chain-sales-shares-drop/",
                "accurate": null,
                "date": "2020-02-18T14:31:00Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Surges Past Samsung to Become Top Smartphone Brand in Q4 2019",
                "content": "February 06 -- Apple overtook Samsung to emerge as the world's top-selling smartphone vendor for the first time in two years, according to figures from several analysts. Several outlets lately published estimated smartphone shipments for Q4 2019 and while there are slights variations, overall figures suggest Apple has managed to top its South Korean rival Samsung. The Cupertino based tech giant was the market leader in Q4 2019 with shipments surging to 72.9 million units in the last months of th",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y51-27V1-JBYT-H16N-00000-00",
                "accurate": null,
                "date": "2020-02-06T18:49:53Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Zendesk Inc has the Highest Future Earnings Growth in the Application Software Industry (ZEN, ADSK, PCYG, HUBS, EGHT)",
                "content": "Return to Headlines\rZendesk Inc has the Highest Future Earnings Growth in the Application Software Industry (ZEN, ADSK, PCYG, HUBS, EGHT) Written on Tue, 02/04/2020 - 2:31am By Shiri Gupta Below are the three companies in the Application Software industry with the highest future earnings growth. The growth of earnings per share (next fiscal year estimated vs. current fiscal year estimated) is important to gauge future profitability and relative value. Higher EPS growth generally justifies higher",
                "url": "http://www.mysmartrend.com/news-briefs/news-watch/zendesk-inc-has-highest-future-earnings-growth-application-software-industry-2",
                "accurate": null,
                "date": "2020-02-04T07:17:16Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: 11th largest institutional shareholder Palisade Capital Management LLC, NJ increases its position in Applied Industrial Technologies",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 08 February 2020 08:13 EST\n\nAs per SEC filings for Q3/2019, Palisade Capital Management LLC, NJ (CIK:0001009006) was ranked 11 out of 200 institutional shareholders of Applied Industrial Technologies (NYSE:AIT). Palisade Capital Management LLC, NJ increased its position in Applied Industrial Technologies by 21,783 shares (or 3.5%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Industrial Technologies was USD61.",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5D-7JW1-JB4F-Y19K-00000-00",
                "accurate": true,
                "date": "2020-02-08T14:19:51Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "GCP Applied Technologies (GCP) Q4 Earnings Top Estimates",
                "content": "GCP Applied Technologies (GCP) came out with quarterly earnings of $0.27 per share, beating the Zacks Consensus Estimate of $0.26 per share. This compares to earnings of $0.29 per share a year ago. These figures are adjusted for non-recurring items.\n\nThis quarterly report represents an earnings surprise of 3.85%. A quarter ago, it was expected that this specialty construction chemicals maker would post earnings of $0.26 per share when it actually produced earnings of $0.28, delivering a surprise",
                "url": "https://www.investing.com/analysis/gcp-applied-technologies-gcp-q4-earnings-top-estimates-200510798",
                "accurate": null,
                "date": "2020-02-26T13:38:44Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "SBI Cards IPO: How to apply for SBI Card IPO? Check price band, lot size, eligibility criteria",
                "content": "SBI Cards IPO: How to subscribe SBI Card IPO? Check price band, lot size, eligibility criteria \n\n SBI Cards IPO: The initial public offer or IPO of SBI Cards and Payment Services, India's one of the largest credit card issuer, will open next week on March 2. SBI Cards IPO will close for subscription on March 5. SBI Cards is 74% owned by SBI while Carlyle Group owns the remaining 26%. Carlyle bought the stake in 2017 from GE. As part of the IPO, SBI will divest 4% of its stake, while Carlyle will",
                "url": "https://m.dailyhunt.in/news/india/english/indiatvnews-epaper-intvnews/sbi+cards+ipo+how+to+apply+for+sbi+card+ipo+check+price+band+lot+size+eligibility+criteria-newsid-168193308",
                "accurate": true,
                "date": "2020-02-27T09:51:33Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "United States : Apple Reports Fourth Quarter Results",
                "content": "Apple announced financial results for its fiscal 2019 fourth quarter ended September 28, 2019. The Company posted quarterly revenue of $64 billion, an increase of 2 percent from the year-ago quarter, and quarterly earnings per diluted share of $3.03, up 4 percent. International sales accounted for 60 percent of the quarters revenue.\n\nWe concluded a groundbreaking fiscal 2019 with our highest Q4 revenue ever, fueled by accelerating growth from Services, Wearables and iPad, said Tim Cook, Apples C",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4J-XYJ1-F11P-X1KN-00000-00",
                "accurate": true,
                "date": "2020-02-04T21:41:47Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Indian shares drop as Apple’s warning signals virus impact",
                "content": "BENGALURU, Feb 18 (Reuters) – Indian shares tracked Asian peers lower on Tuesday, as a revenue warning from tech giant Apple Inc signalled mounting financial fallout on businesses from the coronavirus epidemic in China. \n \nThe iPhone maker warned late Monday it was unlikely to meet a sales target set just three weeks ago amid lost production and weakening demand in China, which supplied 18% of the company’s revenue in the year-ago quarter, after the outbreak. \n \nThe rapidly spreading virus has k",
                "url": "https://www.phoneweek.co.uk/indian-shares-drop-as-apples-warning-signals-virus-impact/",
                "accurate": true,
                "date": "2020-02-18T06:21:16Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Sargent Investment Group, LLC adds to its gains in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 03 February 2020 00:27 EST\n\nAs per SEC filings for Q3/2019, Sargent Investment Group, LLC (CIK:0001766157) was ranked 1260 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Sargent Investment Group, LLC increased its position in Apple by 660 shares (or 1.7%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the purchase value of 660 shares is estimated at USD170,341. At the ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y49-3FD1-JB4F-Y09D-00000-00",
                "accurate": true,
                "date": "2020-02-03T06:29:41Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Deutsche Bank Analysts Give Apple (NASDAQ:AAPL) a $305.00 Price Target",
                "content": "Apple logo Apple (NASDAQ:AAPL) has been assigned a $305.00 target price by equities researchers at Deutsche Bank  in a note issued to investors on Monday,            Borsen Zeitung  reports. The brokerage presently has a \"neutral\" rating on the iPhone maker's stock. Deutsche Bank's price target points to a potential downside of 1.46% from the company's current price. \n\nSeveral other equities research analysts have also issued reports on AAPL. Atlantic Securities lowered Apple from a \"neutral\" ra",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4C-0RB1-JB40-X09F-00000-00",
                "accurate": true,
                "date": "2020-02-03T18:15:43Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Warns Of Coronavirus Impact On Q2 Revenue",
                "content": "(RTTNews) - Apple Inc. (AAPL) said it doesn't expect to meet its revenue guidance for the second quarter due to lower smartphone demand, and temporary work slowdowns related to coronavirus outbreak in China. \n \nApple had said last month that it expects revenues to be between $63.0 billion and $67.0 billion for the second-quarter. Analysts polled by Thomson Reuters expect the company to report  revenues of $65.26 billion for the quarter. Analysts' estimates typically exclude special items. \n \nThe",
                "url": "https://markets.businessinsider.com/news/stocks/apple-warns-of-coronavirus-impact-on-q2-revenue-1028911411",
                "accurate": null,
                "date": "2020-02-18T03:13:30Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: 85th largest institutional shareholder State of New Jersey Common Pension Fund D decreases its position in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 04 February 2020 05:40 EST\n\nAs per SEC filings for Q3/2019, State of New Jersey Common Pension Fund D (CIK:0001483066) was ranked 85 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). State of New Jersey Common Pension Fund D decreased its position in Apple by 331,446 shares (or 9.2%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 331,446 shares is estima",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4H-XHV1-JB4F-Y0W2-00000-00",
                "accurate": null,
                "date": "2020-02-04T12:12:44Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Suppliers to Begin Shipping SiPs for Ultra-Wideband 'AirTags' in Q2-Q3 2020 [Report]",
                "content": "Apple suppliers will begin shipping SiPs (System in Package) for the company's upcoming ultra-wideband 'AirTags' in the second and third quarter of this year, reports analyst Ming-Chi Kuo. Shipments are expected to reach tens of millions of units in this year alone:\nWe expect Universal Asahi Electronics to begin shipping SiPs for UWB tags in 2–3Q20, with shipments reaching tens of millions in 2020. We believe that UWB tags can enhance the iOS search and AR application experience through the clos",
                "url": "https://www.iClarified.com/74517/apple-suppliers-to-begin-shipping-sips-for-ultrawideband-airtags-in-q2q3-2020-report",
                "accurate": null,
                "date": "2020-02-18T18:08:34Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Institutional shareholder UMB Bank NA increases its position in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 04 February 2020 19:15 EST\n\nAs per SEC filings for Q3/2019, UMB Bank NA (CIK:0000933429) was ranked 294 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). UMB Bank NA increased its position in Apple by 511 shares (or 0.11%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the purchase value of 511 shares is estimated at USD131,886. At the end of the quarter, UMB Bank NA held",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4P-6VW1-JB4F-Y30N-00000-00",
                "accurate": null,
                "date": "2020-02-05T01:32:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Global Syngas & Derivatives Market by Production Technology, Gasifier Type, Feedstock, Application, and Region – Forecast to 2024 – ResearchAndMarkets.com",
                "content": "The “Syngas & Derivatives Market by Production Technology, Gasifier Type, Feedstock (Coal, Natural Gas, Petroleum Byproducts, Biomass/Waste), Application (Chemicals, Fuel, and Electricity), and Region – Global Forecast to 2024” report has been added to ResearchAndMarkets.com’s offering. \n \nRising environmental concerns have been the major drivers for the growth of the syngas & amp ; derivatives market in order to provide alternative methods of fuel production. \n \nBiomass/waste segment is project",
                "url": "https://stocksnewsfeed.com/benzinga/global-syngas-derivatives-market-by-production-technology-gasifier-type-feedstock-application-and-region-forecast-to-2024-researchandmarkets-com/",
                "accurate": true,
                "date": "2020-01-01T14:17:38Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "VIRNETX : Shares Up 10% After Supreme Court Rejects Apple's Appeal",
                "content": "By Chris Wack \n   \nVirnetX Holding Corp. shares rose 11% to $4.50 after the U.S. Supreme Court denied Apple's petition for a writ of certiorari seeking review of the judgment of the U.S. Court of Appeals for the Federal Circuit in case 2018-1197. \n \nThe underlying judgment in the case awarded VirnetX $439.8 million in damages, fees, and interest. \n \n\"We are extremely pleased with the Supreme Court's decision not to hear Apple's writ of certiorari,\" said Kendall Larsen, VirnetX chief executive an",
                "url": "https://www.marketscreener.com/VIRNETX-HOLDING-CORPORATI-772237/news/VirnetX-Shares-Up-10-After-Supreme-Court-Rejects-Apple-s-Appeal-30054145/",
                "accurate": null,
                "date": "2020-02-24T17:37:32Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Coronavirus update: more than 73,000 cases, 1,873 deaths, Apple warns on second quarter Coronavirus update: Diagnosed COVID-19 cases exceed 73,000; death toll at 1,873",
                "content": "Coronavirus update: Diagnosed COVID-19 cases exceed 73,000; death toll at 1,873 \n\nCoronavirus update: Diagnosed COVID-19 cases exceed 73,000; death toll at 1,873 \n\nThere are 73,332 confirmed cases of COVID-19, the new coronavirus that was first identified late last year in Wuhan, China, and at least 1,873 deaths,... \n\n\n\nThe no. Of deaths in coronavirus in China is way higher but always being falsely reported by the communist government. So how could some misguided Americans vote for Marxist Sand",
                "url": "https://headtopics.com/us/coronavirus-update-more-than-73-000-cases-1-873-deaths-apple-warns-on-second-quarter-11378042",
                "accurate": null,
                "date": "2020-02-20T09:00:02Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple's Q2 Revenue Forecast Will Take A Hit Amidst Coronavirus Outbreak In China",
                "content": "IDC recently released a report that highlighted Apple dominated the premium segment in the Indian Smartphone market in Q4 2019. The report revealed that Apple reached a record 75.6% market share in Q4 2019 in the premium (US$500+) segment. Apple now warned that it'll fall short of its revenue goals in the second quarter, as the Coronavirus outbreak in China has halted the iPhones production. \n\nIn a recently published investor update, Apple mentioned that while the work has started to resume arou",
                "url": "https://m.dailyhunt.in/news/india/english/mashable+india-epaper-mashble/apple+s+q2+revenue+forecast+will+take+a+hit+amidst+coronavirus+outbreak+in+china-newsid-166205146",
                "accurate": null,
                "date": "2020-02-18T08:29:52Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Zacks: Brokerages Expect Science Applications International Corp (NYSE:SAIC) Will Post Earnings of $1.31 Per Share",
                "content": "Feb 17, 2020( DailyPolitical: http://www.dailypolitical.com/ Delivered by Newstex)  Wall Street brokerages predict that Science Applications International Corp (NYSE:SAIC) will announce earnings of $1.31 per share for the current quarter, Zacks Investment Research[1] reports. Four analysts have provided estimates for Science Applications International's earnings, with estimates ranging from $1.22 to $1.40. Science Applications International posted earnings of $1.17 per share in the same quarter ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7C-6YH1-JCMN-Y0WJ-00000-00",
                "accurate": true,
                "date": "2020-02-17T22:26:57Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT Posts Results of Operations for Fourth Quarter and Full Year 2019",
                "content": "Apple Hospitality REIT reported results of operations for the fourth quarter and full year ended December 31, 2019.\n\nIn a release on February 24, the Company noted Comparable Hotels is defined as the 232 hotels owned and held for use by the Company as of December 31, 2019. For hotels acquired during the periods noted, the Company has included, as applicable, results of those hotels for periods prior to the Company's ownership, and for dispositions and assets held for sale, results have been excl",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y9N-BDH1-F06S-P419-00000-00",
                "accurate": null,
                "date": "2020-02-28T12:24:32Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Shares down after Teck Resources withdraws application for Frontier oilsands project",
                "content": "WATCH ABOVE: Teck Resources has announced it is not going forward with its Frontier mine project. The development was expected to create thousands of jobs, but has now left politicians pointing fingers. As Breanna Karstens-Smith reports, it's a major blow for the oilsands industry in Alberta. Shares in Teck Resources Ltd. are trading down four per cent after the company said citing uncertainty over climate policies.\n\nThe Vancouver-based company said it will take a $1.13-billion writedown on the ",
                "url": "https://country105.com/news/6588417/teck-resources-withdraws-frontier-oilsands-project-shares/",
                "accurate": null,
                "date": "2020-02-24T16:32:38Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "MAGNUS CONCORDIA : Applications for the rights shares and number of unsubscribed rights shares subject to the unsubscribed arrangements pursuant to the rights issue on the basis of one (1) rights share for every two (2) existing shares held on the record",
                "content": "Hong Kong Exchanges and Clearing Limited and The Stock Exchange of Hong Kong Limited take no responsibility for the contents of this announcement, make no representation as to its accuracy or completeness and expressly disclaim any liability whatsoever for any loss howsoever arising from or in reliance upon the whole or any part of the contents of this announcement. \n \n(Incorporated in the Cayman Islands with limited liability) \n \n(Stock Code: 1172) \n \nAPPLICATIONS FOR THE RIGHTS SHARES AND NUMB",
                "url": "https://www.marketscreener.com/news/Magnus-Concordia-APPLICATIONS-FOR-THE-RIGHTS-SHARES-AND-NUMBER-OF-UNSUBSCRIBED-RIGHTS-SHARES-SUBJE--29943854/",
                "accurate": null,
                "date": "2020-02-05T10:39:37Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple announces that it will miss Q2 forecasted revenue due to the coronavirus",
                "content": "Image: Apple  \n   \nSupply and store closures in China have affected sales \n \n Print \n  Trade   \nRead More:  Apple  China  coronavirus  revenue \n\n  \n18 February 2020 | \n   \nApple announced that it will miss its forecasted revenue guidance for the second fiscal quarter of 2020 due to the coronavirus epidemic. The company had  projected  revenue for the quarter between $63 and $67 billion, and gross margin between 38 and 39%. Apple did not provide revised Q2 earnings estimates. \n \nIn a  released st",
                "url": "http://www.techcentral.ie/apple-announces-that-it-will-miss-q2-forecasted-revenue-due-to-the-coronavirus/",
                "accurate": true,
                "date": "2020-02-18T15:03:55Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Dine Brands Reports Mixed Fourth Quarter With Applebee's Comps Contracting, IHOP Showing Gains",
                "content": "Dine Brands Global, the parent of Applebee's and IHOP restaurants, reported mixed results for its fourth quarter, with earnings beating consensus but sales coming in below views and the company's outlook for the current year was also beneath analysts' expectations. \n\nAdjusted earnings increased to $1.78 a share from $1.70 a share previously, while the consensus on Capital IQ was for $1.71 a share. Total revenue rose to $227.5 million from $214.2 million, but the Street was looking for $233.2 mil",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y8V-1PD1-DY03-M31T-00000-00",
                "accurate": true,
                "date": "2020-02-24T15:44:43Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Reuters Insider – Reuters Today: European stocks sink on Apple warning, Alstom, Glencore",
                "content": "Click the following link to watch video:  Source: Insider\nDescription: European chip stocks slide on news that Apple will not meet its sales targets for the quarter due to the disruption caused by the coronavirus. Alstom has agreed to buy the rail division of Bombardier for up to 6.2 billion euros. Glencore reports its first annual net loss in five years. Short Link: \nVideo Transcript:\nVerified transcript not available",
                "url": "https://boereport.com/2020/02/18/reuters-insider-reuters-today-european-stocks-sink-on-apple-warning-alstom-glencore/",
                "accurate": null,
                "date": "2020-02-18T09:35:10Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: 15th largest institutional shareholder Neuberger Berman Group LLC increases its position in Applied Industrial Technologies",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 17 February 2020 16:50 EST\n\nAs per SEC filings for Q3/2019, Neuberger Berman Group LLC (CIK:0001465109) was ranked 15 out of 200 institutional shareholders of Applied Industrial Technologies (NYSE:AIT). Neuberger Berman Group LLC increased its position in Applied Industrial Technologies by 148,295 shares (or 27.9%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Industrial Technologies was USD61.94. At that pric",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7C-91B1-DXKH-N0HG-00000-00",
                "accurate": null,
                "date": "2020-02-17T22:23:55Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: 6th largest institutional shareholder JP Morgan Chase & Co increases its position in GCP Applied Technologies",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 16 February 2020 01:39 EST\n\nAs per SEC filings for Q3/2019, JP Morgan Chase & Co (CIK:0000019617) was ranked 6 out of 153 institutional shareholders of GCP Applied Technologies (NYSE:GCP). JP Morgan Chase & Co increased its position in GCP Applied Technologies by 14,451 shares (or 0.39%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of GCP Applied Technologies was USD21.61. At that price the purchase value of 14,451 shar",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y73-W4T1-JB4F-Y01V-00000-00",
                "accurate": null,
                "date": "2020-02-16T14:20:37Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Twin Capital Management Inc. keeps selling more of Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 01 February 2020 19:15 EST\n\nAs per SEC filings for Q3/2019, Twin Capital Management Inc. (CIK:0001059187) was ranked 476 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Twin Capital Management Inc. decreased its position in Apple by 48,700 shares (or 25.1%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 48,700 shares is estimated at USD12.6 million. At",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y42-8PR1-JB4F-Y159-00000-00",
                "accurate": null,
                "date": "2020-02-02T01:13:39Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "U.S. Patent and Trademark Office Releases Fortinet Inc's Patent Application for Controlling Bandwidth Usage by Media Streams by Limiting Streaming Options Provided to Client Systems",
                "content": "FULL TEXT\n\n\n\nPublication Name: Information Technology Patent NewsPatent Application Number: 16/054498Patent Publication Number: 20200045351International Patent Classification Codes: H04N 21/24 20060101 H04N021/24, H04L 29/06 20060101 H04L029/06Patent Status: Application\n\nAlexandria, Feb. 6 -- U.S. Patent and Trademark Office has released Fortinet Inc's patent application for controlling bandwidth usage by media streams by limiting streaming options provided to client systems. Paixao Pedro Miguel",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5C-KV71-DY0W-40YX-00000-00",
                "accurate": null,
                "date": "2020-02-08T10:38:37Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Brokerages Set Science Applications International Corp (NYSE:SAIC) Price Target at $100.20",
                "content": "Feb 24, 2020( Zolmax.com: http://www.zolmax.com/ Delivered by Newstex)  Science Applications International Corp (NYSE:SAIC) has received an average recommendation of \"Buy\" from the twelve analysts that are presently covering the stock, Marketbeat Ratings[1] reports. One analyst has rated the stock with a sell recommendation, one has assigned a hold recommendation and nine have issued a buy recommendation on the company. The average twelve-month target price among brokerages that have issued a re",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y8W-0JH1-F03R-N0M1-00000-00",
                "accurate": null,
                "date": "2020-02-24T22:11:41Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple’s ‘AirTag’ May Launch Q3 2020",
                "content": "MobileSyrup  Apple’s ‘AirTag’ Bluetooth tracker rumoured to launch in Q3 2020 https://t.co/ZR7fp7E9dd https://t.co/lFKRqsOuIZ  19 hours ago \n\nJ Terry Burch  Apple’s ‘AirTag’ Bluetooth tracker rumoured to launch in Q3 2020.\nhttps://t.co/2WfSsqorCy  19 hours ago \n\nMobileSyrup  Apple's 'AirTag' Bluetooth tracker rumoured to launch in Q3 2020\nhttps://t.co/ZR7fp7E9dd https://t.co/ZB4NdTzluv  20 hours ago",
                "url": "https://www.onenewspage.us/n/Internet/1zlqhne0xk/Apple-AirTag-May-Launch-Q3-2020.htm",
                "accurate": true,
                "date": "2020-02-19T18:28:32Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "SBI Cards IPO: How to apply for SBI Card IPO? Check price band, lot size, eligibility criteria",
                "content": "SBI Cards IPO: How to subscribe SBI Card IPO? Check price band, lot size, eligibility criteria \n  \nSBI Cards IPO: The initial public offer or IPO of SBI Cards and Payment Services, India's one of the largest credit card issuer, will open next week on March 2. SBI Cards IPO will close for subscription on March 5. SBI Cards is 74% owned by SBI while Carlyle Group owns the remaining 26%. Carlyle bought the stake in 2017 from GE. As part of the IPO, SBI will divest 4% of its stake, while Carlyle wil",
                "url": "https://www.newexpressnews.com/sbi-cards-ipo-how-to-apply-for-sbi-card-ipo-check-price-band-lot-size-eligibility-criteria/",
                "accurate": null,
                "date": "2020-02-27T11:21:14Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Alta Capital Management LLC books 31.5% of its gains in Apple in Q4",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 02 February 2020 22:39 EST\n\nAs per SEC filings for Q3/2019, Alta Capital Management LLC (CIK:0001093589) was ranked 285 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Alta Capital Management LLC decreased its position in Apple by 104,988 shares (or 21.8%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 104,988 shares is estimated at USD27.1 million. At",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y48-STP1-DXKH-N40G-00000-00",
                "accurate": true,
                "date": "2020-02-03T04:50:51Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "$2 Billion Castor Oil & Derivatives Market Insights by Product, Application and Region - Forecast to 2025",
                "content": "PR Newswire\n\n\n\nThe\"Castor Oil & Derivatives Market Size, Share & Trends Analysis Report By Product (Sebacic Acid, 12 HSA, Ricinoleic Acid, Castor Wax, Undecylenic Acid), By Application, By Region, And Segment Forecasts, 2019-2025\"report has been added toResearchAndMarkets.com'soffering.\n\n\n\nThe global castor oil and derivatives market size is expected to reach USD 2 billion by 2025, expanding at a CAGR of 6.7%.\n\nThe market is anticipated to grow at a fast pace owing to increasing demand from end-",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y60-PC41-JB72-1235-00000-00",
                "accurate": true,
                "date": "2020-02-11T05:32:24Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Top Apple analyst sees Q2 or Q3 introduction of a brand new iPhone feature",
                "content": "Remember Apple's AirTags? Working in sync with the Find My... app, the tags can be placed on items that you do not want to misplace and lose. The app will lead the owner of the item to its location using the U1 Ultra Wideband chip that . A leak last year revealed that the AirTags (codenamed B389) are small, round, and have the Apple logo on them. They also can be attached to a key ring. Kuo says that he expects the supply chain to produce 10 million Apple AirTags before the end of the year.",
                "url": "https://businesscomputingworld.co.uk/t/top-apple-analyst-sees-q2-or-q3-introduction-of-a-brand-new-iphone-feature/272117",
                "accurate": true,
                "date": "2020-02-19T03:24:38Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: 3rd largest institutional shareholder JP Morgan Chase & Co decreases its position in Applied Industrial Technologies",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 15 February 2020 17:02 EST\n\nAs per SEC filings for Q3/2019, JP Morgan Chase & Co (CIK:0000019617) was ranked 3 out of 200 institutional shareholders of Applied Industrial Technologies (NYSE:AIT). JP Morgan Chase & Co decreased its position in Applied Industrial Technologies by 201,193 shares (or 7.2%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Industrial Technologies was USD61.94. At that price the sale val",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6Y-H7F1-DXKH-N2JF-00000-00",
                "accurate": null,
                "date": "2020-02-15T23:15:34Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Analysts Trim Apple Hospitality REIT's Q3, 2019, and 2020 Earnings Forecasts",
                "content": "Forecasted earnings estimates for Q3 ending September 30, 2019, and the full year expectations for 2019 and 2020 for the years ending on December 31 for Apple Hospitality REIT Inc (NYSE:APLE, Recent Price: 15.28) have been scaled down. The Q3 earnings estimate has been decreased to $0.12 per share down from the previous consensus of $0.24 per share, while the estimate for 2019 has been decreased to $0.79 per share from the consensus of $0.83 per share and the full year 2020 estimate has also bee",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y42-Y4P1-DY03-M064-00000-00",
                "accurate": true,
                "date": "2020-02-02T05:46:24Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple To Miss Q2 Earnings As Coronavirus Outbreak Hits Both Supply And Demand",
                "content": "Apple Inc. (NASDAQ: AAPL ) on Monday said that it doesn’t expect to meet the earnings guidance for the quarter ending in March, as both its supply chain and the demand for its products is impacted by the novel coronavirus (COVID-19) outbreak. \n What Happened  \nThe consumer electronics giant makes iPhones and other products in China , where at least 1,868 people were confirmed dead from the virus by the end of Monday. \n \nApple previously outlined revenue quidance of $63 billion to $67 billion for",
                "url": "https://stocksnewsfeed.com/benzinga/apple-to-miss-q2-earnings-as-coronavirus-outbreak-hits-both-supply-and-demand/",
                "accurate": null,
                "date": "2020-02-18T05:18:57Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Roku earnings preview: First read on Disney and Apple impacts",
                "content": "By Emily Bary \n \nThe options market is looking for a 15.6% post-earnings swing, but that would be a smaller stock move than in recent quarters \n \nFresh off a carriage renegotiation with Fox Corp., Roku Inc. is about to face another test. \n \nThe streaming company is set to post December-quarter results on Thursday afternoon, with a report that will not only show how well Roku (ROKU) devices and connected TVs sold during the holidays but also provide some early indications of how Roku benefited fr",
                "url": "https://www.morningstar.com/news/marketwatch/20200211587/roku-earnings-preview-first-read-on-disney-and-apple-impacts",
                "accurate": true,
                "date": "2020-02-11T21:48:30Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "08:11 EST Apple Q2 revenues could be less than $60B, says Bernstein",
                "content": "Bernstein analyst A.M. Sacconaghi Jr. notes that Apple announced that it does not expect to meet its Q2 revenue guidance of $63B-$67B due to disruption from the coronavirus. In some ways, the announcement is not entirely a surprise given Apple's very high production exposure to China and sales into China, he contends. His analysis suggests that \"under plausible assumptions,\" Q2 revenues could be less than $60B. While Apple emphasized the shortfall did not reflect weakness in fundamental demand, ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7H-V8K1-JCD8-M4XR-00000-00",
                "accurate": null,
                "date": "2020-02-18T13:42:06Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Stock market live updates: Dow futures down 820, airlines slide, Apple drops",
                "content": "This is a live blog. Please check back for updates. \n  8:54 am: Here are Monday’s biggest analyst calls of the day  8:32 am: Chipmaker stock ETFs fall sharply   \nThe VanEck Vectors Semiconductor ETF (SMH) and the iShares PHLX Semiconductor ETF (SOXX) were both down more than 3% in the premarket, putting them on pace to break below their respective 50-dayy moving averages for the first time since Feb. 3. AMD, Nvidia, Micron and Lam Research led the ETFs lower in the premarket. — Francolla , Imber",
                "url": "https://stocksnewsfeed.com/cnbc/stock-market-live-updates-dow-futures-down-820-airlines-slide-apple-drops/",
                "accurate": null,
                "date": "2020-02-24T14:01:12Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop (Reuters) – Shares of Apple Inc fell 2 %...",
                "content": "(Reuters) – Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain. \n  \nCustomers walk past an Apple logo inside of an Apple store at Grand Central Station in New York, U.S., August 1, 2018. REUTERS/Lucas Jackson \n  \nThe drop in Apple’s stock is set to wipe nearly $30 billion off its market capitalization,",
                "url": "https://wallstreetreview.com/2020/02/18/coronavirus-threatens-apple-supply-chain-sales-shares-drop/",
                "accurate": true,
                "date": "2020-02-18T14:13:17Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT: 4Q Earnings Snapshot",
                "content": "RICHMOND, Va. (AP) _ Apple Hospitality REIT Inc. (APLE) on Monday reported a key measure of profitability in its fourth quarter. The results missed Wall Street expectations.\n\nThe Richmond, Virginia-based real estate investment trust said it had funds from operations of $70.6 million, or 32 cents per share, in the period.\n\nThe average estimate of four analysts surveyed by Zacks Investment Research was for funds from operations of 33 cents per share.\n\nFunds from operations is a closely watched mea",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y8W-7041-JC65-51J7-00000-00",
                "accurate": true,
                "date": "2020-02-24T23:01:00Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "FY2019 Annual Report: Apple Net Profit down 7.2% Corporate Wire Date: 26 December 2019 21:34 EST Release Date: December 19, 2019",
                "content": "AMERICAN RESULTS\n\nApple (NASDAQ:AAPL) reported net profit for the year-ended 28 September 2019 of $US55.3b, down 7.2% from $US59.5b in the previous year. Earnings per share (EPS) were down 0.3% from $US12.01 in FY2018 to $US11.97 in FY2019.\n\nMajor changes compared with previous year:\n\nFavourable Changes:\n- Total revenue to total assets up from 0.7 to 0.8\n- Sales and marketing expenses to Sales down from 42% to 39.4%\n- Current ratio up 36.3% from 1.1 to 1.5\n- Total current assets to Total Assets ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y80-JDR1-JB4F-Y1C2-00000-00",
                "accurate": null,
                "date": "2020-02-20T18:38:05Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Coronavirus outbreak likely to dent Apple's growth; iPhone maker set to miss its Q4 revenue target",
                "content": "Apple had forecast revenue of billion to billion for the fiscal second quarter ending in March. \n\nApple Inc. doesn’t expect to meet its revenue guidance for the March quarter because of work slowdowns and lower smartphone demand, showing that the virus outbreak in China is taking a bigger-than-predicted toll on one of the world’s most valuable companies. The company said that the iPhone, which generates the bulk of Apple’s revenue, is temporarily constrained due to production ramping up more slo",
                "url": "https://www.financialexpress.com/industry/technology/coronavirus-outbreak-likely-to-dent-apples-growth-iphone-maker-set-to-miss-its-q4-revenue-target/1871421/",
                "accurate": true,
                "date": "2020-02-18T05:37:06Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Roku Shares Surge As Disney, Apple Launches Drive Solid Q4 Revenue Gains",
                "content": "Roku Inc.  ( ROKU ) – Get Report  shares jumped higher in pre-market trading Friday after it posted stronger-than-expected fourth quarter revenues, and topped Street estimates for near-term sales, as customers flocked to its streaming service platform amid the launch of new offering from Disney and Apple.  \n \nRoku recorded a narrower-than-expected fourth quarter loss of 13 cents per share over the three months ending in December, as revenues surged nearly 50% to $411.2 million. Roku added 4.6 mi",
                "url": "https://www.thelivefeeds.com/roku-shares-surge-as-disney-apple-launches-drive-solid-q4-revenue-gains/",
                "accurate": null,
                "date": "2020-02-14T15:00:51Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus Spread Dents Views on China Smartphone Demand as Barclays Lowers Apple Earnings Views",
                "content": "The outbreak of a new coronavirus in China, which has killed about 500 people mainly in the Asian nation, could weigh on demand for smartphones and Barclays said it was lowering estimates for Apple's (AAPL) earnings to reflect the growing uncertainty around iPhone demand. \n\nAbout 10 million to 15 million units of smartphone demand \"could be at risk\" in the March quarter, Barclays analyst Tim Long said in a note. The firm reduced smartphone forecasts by 9% for the current period to 303 million an",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y54-T2G1-DY03-M1KJ-00000-00",
                "accurate": true,
                "date": "2020-02-07T05:19:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Boys Arnold & Co Inc. books some of its profits in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 02 February 2020 23:56 EST\n\nAs per SEC filings for Q3/2019, Boys Arnold & Co Inc. (CIK:0001082020) was ranked 567 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Boys Arnold & Co Inc. decreased its position in Apple by 719 shares (or 0.49%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 719 shares is estimated at USD185,569. At the end of the quarter, ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y49-3FD1-JB4F-Y085-00000-00",
                "accurate": null,
                "date": "2020-02-03T06:29:41Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Bermuda: Technology & Innovation Update Q1 2020 - Appleby",
                "content": "In each quarterly issue of the Appleby Asia Alert, we bring you\nall the latest legislative and regulatory updates in the offshore\njurisdictions of Bermuda, the Cayman Islands\n( Cayman ) and the British Virgin Islands\n( BVI ) in the technology and innovation sector. \nBermuda  \nBermuda has continued to revise and refine its\ntechnology-specific legislation as the industry has evolved and\ndeveloped.  Key changes in the past few months include\namendments to the Digital Asset Business Amendment Act, I",
                "url": "http://www.mondaq.com/Article/898548",
                "accurate": null,
                "date": "2020-02-28T12:38:34Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple shares drop due to coronavirus",
                "content": "GMT \n \nSource: Dukascopy Bank SA \n  \nDuring Tuesday, February 18, shares of Apple company dropped 3.10%. \n  \n\nThe main reason for the decline is due to coronavirus outbreak in China. The company's representatives announced that Apple would fail to hit its March sales forecast as it had been forced to shut operations due to the epidemic. \n  \nBack to feed       \nFor further information regarding potential cooperation, \nplease call us or make callback request. \n \nTo learn more about Dukascopy Bank ",
                "url": "http://www.dukascopy.com/swiss/english/marketwatch/market_news/Market-News-and-Research/125760/",
                "accurate": null,
                "date": "2020-02-18T15:59:17Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: 104th largest institutional shareholder Bessemer Group Inc. decreases its position in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 09 February 2020 01:28 EST\n\nAs per SEC filings for Q3/2019, Bessemer Group Inc. (CIK:0001054074) was ranked 104 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Bessemer Group Inc. decreased its position in Apple by 244,515 shares (or 8.5%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 244,515 shares is estimated at USD63.1 million. At the end of the q",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5M-3301-JB4F-Y517-00000-00",
                "accurate": true,
                "date": "2020-02-09T14:06:10Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "I-T Department clarifies 10% TDS applicable only on dividend paid by mutual funds, not on redemption of units",
                "content": "New Delhi: The tax department on Tuesday clarified that the Budget proposal of 10 percent TDS will be applicable only on dividend payment by mutual funds and not on gain arising out of redemption of units.\n\nFinance Minister Nirmala Sitharaman had in Budget 2020-21 scrapped dividend distribution tax (DDT) paid by companies and mutual funds on dividend paid to shareholders or unit holders.MoreIn place, it was proposed to levy tax deducted at source (TDS) of 10 percent on dividend/income paid by a ",
                "url": "https://in.finance.yahoo.com/news/t-department-clarifies-10-tds-083449171.html",
                "accurate": null,
                "date": "2020-02-05T08:48:40Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple (NASDAQ:AAPL) Price Target Raised to $343.00 at Piper Sandler",
                "content": "Feb 01, 2020( TheOlympiaReport: https://theolympiareport.com Delivered by Newstex)             https://www.marketbeat.com/logos/apple-inc-logo.pngApple (NASDAQ:AAPL) had its price objective boosted by Piper Sandler from $305.00 to $343.00 in a report released on Wednesday, The Fly[1] reports. The brokerage currently has an overweight rating on the iPhone maker's stock. Piper Sandler also issued estimates for Apple's Q2 2020 earnings at $3.01 EPS, Q3 2020 earnings at $2.50 EPS, Q4 2020 earnings a",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3Y-M6F1-F03R-N17N-00000-00",
                "accurate": null,
                "date": "2020-02-01T22:00:18Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Science Applications International's Consensus Projections for Q1, 2020, and 2021 Earnings Trimmed",
                "content": "Earnings estimates for Q1 ending October 31, 2019, and the full year forecasts for 2020 and 2021 for the years ending on January 31 for Science Applications International Corp (NYSE:SAIC, Recent Price: 90.43) have been reduced. The Q1 earnings estimate has been decreased to $1.34 per share a reduction from the previous consensus forecast of $1.45 per share, while the estimate for 2020 has been decreased to $5.44 per share from the consensus forecast of $5.50 per share and the full year 2021 esti",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4J-Y6S1-DY03-M51G-00000-00",
                "accurate": true,
                "date": "2020-02-04T17:47:51Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "243 25/02/2020 Applus+ 2019 Full Year Results Announcement",
                "content": "Applus Services, S.A. (\"Applus+\" or \"the Group\"), one of the world`s leading and most innovative companies in Testing, Inspection and Certification, today announces the results for the year ended 31 December 2019 (\"the period\"). Highlights Mid single digit organic revenue growth contributed by all divisions Good margin increase leading to double digit growth in Operating Profit and EPS Three acquisitions with EUR13 million revenue p.a. and strongly margin accretive Auto Irish contract renewed fo",
                "url": "http://www.myheadlinez.com/40281252/243-25022020-Applus-2019-Full-Year-Results-Announcement/",
                "accurate": true,
                "date": "2020-02-25T18:57:58Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Stock Traders Buy High Volume of Put Options on Applied Genetic Technologies (NASDAQ:AGTC)",
                "content": "Applied Genetic Technologies logo Applied Genetic Technologies Corp (NASDAQ:AGTC) saw unusually large options trading activity on Thursday. Stock traders purchased 2,688 put options on the company. This represents an increase of 975% compared to the average volume of 250 put options. \n\nIn other Applied Genetic Technologies news, major shareholder Patrick Johan Hendrik Krol sold 81,162 shares of the firm's stock in a transaction that occurred on Thursday, December 26th. The shares were sold at an",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y56-V3N1-JB40-X3VM-00000-00",
                "accurate": true,
                "date": "2020-02-07T17:56:44Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "India: CBDT issues clarification on the applicability of TDS provisions on Mutual Fund dividend",
                "content": "FULL TEXT\n\n\n\nThe Finance Bill, 2020 proposed to remove Dividend Distribution Tax (DDT) at the level of Company/ Mutual Fund and proposed to tax the same in the hands of share/unit holder. It was also proposed to levy TDS at the rate of 10% on the dividend/ income paid by the Company/Mutual Fund to its share/unit holder if the amount of such dividend/ income exceeds five thousand rupees in a Financial Year.\n\nQueries have been received to the effect that whether under the proposed section 194K, th",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4T-B8R1-JBHT-D1SX-00000-00",
                "accurate": null,
                "date": "2020-02-05T20:42:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "$10 Billion Bezos Bucks For Climate Change + Apple To Miss Q1 Targets | Digital Trends Live 2.18.20",
                "content": "On Digital Trends Live today: The slowdown in Chinese manufacturing due the coronavirus is starting to hit big tech as Apple reported yesterday it will miss Q1 guidance; Amazon CEO Jeff Bezos announced a $10 billion fund aimed at fighting climate change; Ring mandates two-factor authentication for users to login to their accounts; A 600-mile fuel celled big rig may soon hit the road from Nikola Corp; Fluent.ai and improving voice assistants; How are home security companies making their devices m",
                "url": "https://www.newsr.in/video/20200218/12835780/10-Billion-Bezos-Bucks-For-Climate-Change.htm",
                "accurate": true,
                "date": "2020-02-18T17:28:11Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Interim Report (Half Year) Analysis H2 2019: Hindustan Appliances reports 2.1% fall in Half-Yearly Net Profit Corporate Wire Date: 01 February 2020 08:11 IST Release Date: December 24, 2019",
                "content": "INDIAN RESULTS\n\nHindustan Appliances (BSE:531918), announced net profit of INR14.8 Lakhs ($US20,940) for the half year-ended 30 September 2019, down 2.1% from the previous corresponding period.\n\nCompared with the previous corresponding period [PCP; H/30 Sep 2018], year-over-year [y.o.y.] Revenue was up 23.7% and Net Profit was down 2.1%.\n\n\n\n Half year-ended 30 Sep 2019 30 Sep 2018\n Revenue, INR 27.8 Lakhs 22.5 Lakhs\n Revenue, $US 0.4 Lakhs 0.3 Lakhs\n PCP growth in Revenue % 23.67 -\n Net Profit, ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3W-06S1-JB4F-Y23S-00000-00",
                "accurate": null,
                "date": "2020-02-01T05:28:23Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Today is the last day to apply in ICL Organic Dairy Product IPO",
                "content": "Today is the last day to invest in the Noida-based SME IPO, ICL Organic Dairy Product. The company had extended its IPO period till February 7. \n\nThe SME IPO was oversubscribed by 2.25 times till Wednesday. It had received bids for 46,08,000 shares against the total issue size of 20,40,000 shares as per the BSE data. \n\nReports suggested that the IPO period is extended because a lot of investors were not able to apply to the issue due to last month's banking strike, which was held on January 31. ",
                "url": "https://m.dailyhunt.in/news/india/english/the+statesman-epaper-statesman/today+is+the+last+day+to+apply+in+icl+organic+dairy+product+ipo-newsid-164141424",
                "accurate": null,
                "date": "2020-02-07T10:04:16Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Analysts Trim Apple Hospitality REIT's Q3, 2019, and 2020 Earnings Forecasts",
                "content": "Forecasted earnings estimates for Q3 ending September 30, 2019, and the full year expectations for 2019 and 2020 for the years ending on December 31 for Apple Hospitality REIT Inc (NYSE:APLE, Recent Price: 15.28) have been scaled down. The Q3 earnings estimate has been decreased to $0.12 per share down from the previous consensus of $0.24 per share, while the estimate for 2019 has been decreased to $0.79 per share from the consensus of $0.83 per share and the full year 2020 estimate has also bee",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3W-XNG1-JBH1-X234-00000-00",
                "accurate": true,
                "date": "2020-02-01T11:03:02Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Quarterly Report Analysis Q2 2019: Hindustan Appliances reports 29.3% sequential rise in Quarterly Net Profit Corporate Wire Date: 01 February 2020 08:11 IST Release Date: December 24, 2019",
                "content": "INDIAN RESULTS\n\nHindustan Appliances (BSE:531918), announced net profit of INR8.3 Lakhs ($US11,808) for the quarter-ended 30 September 2019, up 29.3% from the previous quarter and up 0.4% from the year-earlier period.\n\nSequential Quarter comparison\n\n\n\n\n Quarter on Quarter Sep 30, 2019 Jun 30, 2019 Sep 30, 2019 Jun 30, 2019 Change\n Description INR Lakhs INR Lakhs $US ('000) $US ('000) (%)\n EBIT 8.3 6.5 11.8 9.4 Up 29.3\n Pre Tax Profit/(Loss) 8.3 6.5 11.8 9.4 Up 29.3\n Profit/(Loss) after Tax 8.3 6",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3W-06S1-JB4F-Y23R-00000-00",
                "accurate": null,
                "date": "2020-02-01T05:28:23Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Stifel Nicolaus Boosts Applied Materials (NASDAQ:AMAT) Price Target to $80.00",
                "content": "Feb 16, 2020( Week Herald: https://weekherald.com Delivered by Newstex)             https://www.marketbeat.com/logos/applied-materials-inc-logo.pngApplied Materials (NASDAQ:AMAT) had its target price boosted by Stifel Nicolaus from $72.00 to $80.00 in a report published on Thursday, The Fly[1] reports. They currently have a buy rating on the manufacturing equipment provider's stock.Several other equities research analysts also recently weighed in on the company. \n\nBidaskClub raised Applied Mater",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y75-54P1-JCMN-Y4SJ-00000-00",
                "accurate": null,
                "date": "2020-02-16T21:58:20Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "FY2019 Annual Report: Apple Hospitality REIT Net Profit down 16.6% Corporate Wire Date: 29 February 2020 10:33 EST Release Date: February 26, 2020",
                "content": "AMERICAN RESULTS\n\nApple Hospitality REIT (NYSE:APLE) reported net profit for the year-ended 31 December 2019 of $US172m, down 16.6% from $US206m in the previous year. Earnings per share (EPS) were down 14.4% from 90.0c in FY2018 to 77.0c in FY2019.\n\nMajor changes compared with previous year:\n\nFavourable Changes:\n- Total Liabilities to EBITDA of 4.4 compares favourably with the Joseph Piotroski benchmark of  less than 5. However, it has deteriorated by 15% from the previous year's ratio of 3.9.\n-",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y9X-8WS1-JB4F-Y10P-00000-00",
                "accurate": null,
                "date": "2020-02-29T18:25:28Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "CBDT says 10% TDS applicable only on dividend payment by mutual funds",
                "content": "CBDT has issued a clarification that the requirement of deducting TDSA at 10% will only apply for dividend payments by mutual funds. \n\nNo tax shall be required to be deducted by the mutual fund on income which is in the nature of capital gains, clarified Central Board of Direct Taxes. \n\nThe Finance Bill, 2020, has proposed the insertion of a new section - 194K - in the Income Tax Act, which states \"any person responsible for paying income arising from units of mutual fund or a specified company ",
                "url": "https://m.dailyhunt.in/news/india/english/live+mint-epaper-livemint/cbdt+says+10+tds+applicable+only+on+dividend+payment+by+mutual+funds-newsid-163567168",
                "accurate": null,
                "date": "2020-02-04T15:36:36Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT (NYSE:APLE) Issues Earnings Results, Misses Expectations By $0.22 EPS",
                "content": "Feb 25, 2020( The Markets Daily: https://www.themarketsdaily.com Delivered by Newstex)  Apple Hospitality REIT (NYSE:APLE) posted its quarterly earnings results on Monday. The real estate investment trust reported $0.11 earnings per share (EPS) for the quarter, missing the Thomson Reuters' consensus estimate of $0.33 by ($0.22), Fidelity Earnings[1] reports. The business had revenue of $289.97 million during the quarter, compared to analyst estimates of $288.45 million. \n\nApple Hospitality REIT ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y93-14V1-F03R-N13P-00000-00",
                "accurate": true,
                "date": "2020-02-25T22:34:43Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Connectivity Upgrades in NetActuate's Dubai Data Center Boost Application Delivery for End Users Across MENA",
                "content": "RALEIGH, N.C., Feb. 20, 2020 / -PRWeb/ -- NetActuate is pleased to announce improved network performance and expanded network service capacity from their Dubai data center. Local and regional providers have been added to boost application delivery speed and reliability both within the UAE and across MENA.\n\n\"Since the launch of services from our Dubai datacenter in 2018, we have seen demand grow quickly,\" said Mark Mahle, CEO and Principal Technology Architect for NetActuate. \"We are pleased to h",
                "url": "https://www.benzinga.com/pressreleases/20/02/n15377186/connectivity-upgrades-in-netactuates-dubai-data-center-boost-application-delivery-for-end-users-ac",
                "accurate": null,
                "date": "2020-02-20T18:03:14Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Raymond James Boosts Apple (NASDAQ:AAPL) Price Target to $360.00",
                "content": "Feb 02, 2020( TheOlympiaReport: https://theolympiareport.com Delivered by Newstex)             https://www.marketbeat.com/logos/apple-inc-logo.pngApple (NASDAQ:AAPL) had its target price lifted by Raymond James from $280.00 to $360.00 in a research note published on Wednesday morning, BenzingaRatingsTable[1] reports. Raymond James currently has an outperform rating on the iPhone maker's stock.Several other research analysts have also commented on AAPL. \n\nUBS Group set a $355.00 price target on A",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y45-JJV1-JCMN-Y38X-00000-00",
                "accurate": null,
                "date": "2020-02-02T21:47:38Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple fear they won't make second-quarter financial targets due to coronavirus",
                "content": "Apple is warning investors it won't meet its second-quarter financial targets. \n\nIt is because the coronavirus alert in China has cut production of iPhones. \n\nAll of its manufacturing facilities are outside Hubei province, the epicentre of the outbreak, and all have been reopened. \n\nShares slipped in Asia on Tuesday as the impact from the outbreak deepened, with news of China’s possible postponement of major events coming alongside Apple saying it would fail to meet its profit target since the v",
                "url": "http://www.breakingnews.ie/business/apple-fear-they-wont-make-second-quarter-financial-targets-due-to-coronavirus-982385.html",
                "accurate": null,
                "date": "2020-02-18T08:22:50Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Needham & Company LLC Raises Applied Materials (NASDAQ:AMAT) Price Target to $73.00",
                "content": "Applied Materials (NASDAQ:AMAT) had its price objective increased by stock analysts at Needham & Company LLC from $70.00 to $73.00 in a research report issued to clients and investors on Thursday, BenzingaRatingsTable reports. The brokerage currently has a “buy” rating on the manufacturing equipment provider’s stock. Needham & Company LLC’s price target would suggest a potential upside of 7.01% from the company’s previous close.\n\nSeveral other equities research analysts have also issued reports ",
                "url": "https://www.americanbankingnews.com/2020/02/13/needham-company-llc-raises-applied-materials-nasdaqamat-price-target-to-73-00.html",
                "accurate": true,
                "date": "2020-02-13T15:57:59Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: 57th largest institutional shareholder State Board of Administration of Florida Retirement System decreases its position in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 06 February 2020 17:56 EST\n\nAs per SEC filings for Q3/2019, State Board of Administration of Florida Retirement System (CIK:0000938076) was ranked 57 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). State Board of Administration of Florida Retirement System decreased its position in Apple by 139,426 shares (or 2.3%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y54-0JF1-JB4F-Y3FS-00000-00",
                "accurate": true,
                "date": "2020-02-07T01:14:18Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Opening Bell: Global Equities, U.S. Futures Plunge On Apple Forecast; Gold Up",
                "content": "Apple warns of disruption in both production and distribution because of coronavirus epidemic\n\nSafe haven assets rise\n\nOil falls on Sino economic slowdown\n\nKey Events \n\nContracts on U.S. indices, including for the NASDAQ, Dow and S&P 500, all fell this morning, in tandem with global stocks, after Apple (NASDAQ:AAPL) warned it won’t be able to meet its quarterly revenue targets for March.\n\nThe reason for the miss: knock-on effects from the coronavirus' impact on China's workforce and economy, whe",
                "url": "https://www.investing.com/analysis/opening-bell-global-equities-us-futures-plunge-on-apple-forecast-gold-up-200508255",
                "accurate": null,
                "date": "2020-02-18T12:48:37Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Tender Notice: MINISTRY OF PUBLIC HEALTH Seeks \"Acquisition Surgical Gown, Foley Fr Probe 22 Foley Probe Fr 24, Container to Discard Capacity 12 Liters For Hospital Amistad Japan Guatemala, Belongs to the First Quarter of 2020 Opinion 01-2020; Application",
                "content": "Guatemala, Feb. 26 -- MINISTRY OF PUBLIC HEALTH has posted a tender notice for \"Acquisition Surgical Gown, Foley Fr Probe 22 Foley Probe Fr 24, Container to Discard Capacity 12 Liters For Hospital Amistad Japan Guatemala, Belongs to the First Quarter of 2020 Opinion 01-2020; Application No. 020,084,147,148, -2020..\"\n\nTender Details: Title: Acquisition Surgical Gown, Foley Fr Probe 22 Foley Probe Fr 24, Container To Discard Capacity 12 Liters For Hospital Amistad Japan Guatemala, Belongs To The F",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y98-JGC1-JDKC-R2X4-00000-00",
                "accurate": true,
                "date": "2020-02-26T19:47:29Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "FILE PHOTO: The Apple Inc. logo is seen hanging at the entrance to the Apple store on 5th Avenue in New York \n(Reuters) - Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain. \n\nThe drop in Apple's stock is set to wipe nearly $30 billion(£23 billion) off its market capitalisation, just as it was inching ",
                "url": "https://news.yahoo.com/coronavirus-threatens-apple-supply-chain-135051100.html",
                "accurate": null,
                "date": "2020-02-18T15:23:07Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "(Reuters) - Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain. \n \nThe drop in Apple's stock is set to wipe nearly $30 billion off its market capitalization, just as it was inching closer to $1.5 trillion in value. The stock was trading down at $318.74. \n \nHowever, several Wall Street brokerages dubbed",
                "url": "https://wkzo.com/news/articles/2020/feb/18/coronavirus-threatens-apple-supply-chain-sales-shares-drop/986080/",
                "accurate": true,
                "date": "2020-02-18T14:06:25Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Morgan Stanley Increases Applied Materials (NASDAQ:AMAT) Price Target to $69.00",
                "content": "Feb 14, 2020( DailyPolitical: http://www.dailypolitical.com/ Delivered by Newstex)             https://www.marketbeat.com/logos/applied-materials-inc-logo.pngApplied Materials (NASDAQ:AMAT) had its price objective raised by Morgan Stanley from $68.00 to $69.00 in a report published on Monday morning, BenzingaRatingsTable[1] reports. Morgan Stanley currently has an equal weight rating on the manufacturing equipment provider's stock.Several other analysts also recently weighed in on AMAT. \n\nDA Dav",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6R-B7N1-F03R-N285-00000-00",
                "accurate": true,
                "date": "2020-02-14T22:49:49Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Hospitality REIT Q4 Modified FFO Misses, Revenue Tops Consensus",
                "content": "Apple Hospitality REIT (APLE) on Monday posted Q4 modified funds from operations of $0.32 per share, compared with $0.36 a year ago. That missed the consensus estimate of $0.33 compiled by Capital IQ.\n\nRevenue declined to $290 million from $295.3 million, exceeding analysts' projection of $289 million.\n\nPrice: 14.40, Change: -0.08, Percent Change: -0.55",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y8W-5TV1-DY03-M3BH-00000-00",
                "accurate": true,
                "date": "2020-02-24T22:47:14Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "United Kingdom Intellectual Property Office Publishes Application for Trademark \"FRUITFUL FUTURES\"",
                "content": "South Wales, Feb. 26 -- United Kingdom Intellectual Property Office (UKIPO) has registered trademark \"FRUITFUL FUTURES\" on Feb. 12. The details about the trademark application no. UK00003466255 published in the journal no. 2020/008 (Feb. 21).\n\nWith Clifford Chance LLP as representative, Fruit of the Loom Inc filed the trademark application for the below mentioned good(s)/service(s). Class 18 : Duffel bags and gym bags. Class 25 : Briefs, boxer shorts, undershirts, trunks, panties, lingerie, shir",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y9D-D0T1-F12F-F29K-00000-00",
                "accurate": true,
                "date": "2020-02-27T06:35:28Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Revance files U.S. application for frown line treatment; shares up 3% premarket",
                "content": "0 \n\nshares \n\nShareTweetSavePostSend \n\nYou Might Like \n\nTweets about this \n\nBreaking News$RVNC $AGN $NSRGY - Revance files U.S. application for frown line treatment; shares ahead 3% premarket https://t.co/LZY5AuYLWG 17 minutes ago \n\nSpotlight ð¦ \n\nWORTH WATCHING \n\nEnvironmentally friendly: One News Page is hosted on servers powered solely by renewable energy \n\n© 2020 One News Page Ltd. All Rights Reserved. \n\n© 2020 One News Page Ltd. All Rights Reserved. \n\nAbout us | Contact us  | Disclaimer  | P",
                "url": "https://www.onenewspage.us/n/Markets/1zlqhn8lkg/Revance-files-application-for-frown-line.htm",
                "accurate": true,
                "date": "2020-02-06T14:01:53Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Asia Sells On Apple’s Warning; European, US Futures Hint At Negative Start",
                "content": "Asian equities retraced a part of Monday’s advance after Apple warned that it won’t meet its revenue guidance this quarter due to a subdued production and lower demand in China and a disrupted global supply amid the coronavirus breakout. Even though Apple’s manufacturing partner facilities resumed activity last week, China hasn’t managed to get back to a normal rhythm just yet, and the latter could take a couple of more weeks, if not months. \n\nThe risk appetite remains fragile and gains in equit",
                "url": "https://uk.investing.com/analysis/asia-sells-on-apples-warning-european-us-futures-hint-at-negative-start-200438097",
                "accurate": null,
                "date": "2020-02-18T07:23:35Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "Shares of Apple Inc ( AAPL.O ) fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain.\n\nThe drop in Apples stock is set to wipe nearly $30 billion off its market capitalization, just as it was inching closer to $1.5 trillion in value. The stock was trading down at $318.74.\n\nHowever, several Wall Street brokerages dubbed Apple",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5RPB-0N21-JD88-304B-00000-00",
                "accurate": null,
                "date": "2020-02-20T21:47:29Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple's surprise sales warning pressures futures",
                "content": "By Medha Singh \n \n(Reuters) - U.S. stock index futures dropped on Tuesday as investors returned from a long weekend to a sales warning from Apple Inc that highlighted the impact of the coronavirus outbreak on global supply chains. \n \nThe world's most valuable technology firm said on Monday it was unlikely to meet its March-quarter sales guidance because of slower iPhone production and weaker demand in China. \n \nShares of the iPhone maker fell 3.1% in premarket trading, while those of Apple suppl",
                "url": "https://whtc.com/news/articles/2020/feb/18/apples-surprise-sales-warning-pressures-futures/986064/",
                "accurate": null,
                "date": "2020-02-18T13:19:42Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "$2 Billion Castor Oil & Derivatives Market Insights by Product, Application and Region - Forecast to 2025",
                "content": "DUBLIN, Feb. 10, 2020 /PRNewswire/ -- The report has been added to ResearchAndMarkets.com's offering.\n\nThe global castor oil and derivatives market size is expected to reach USD 2 billion by 2025, expanding at a CAGR of 6.7%.\n\nThe market is anticipated to grow at a fast pace owing to increasing demand from end-use industries, especially biodiesel, cosmetics, and pharmaceutical. The growth in the market can be attributed to increasing demand for biodegradable and sustainable products on account o",
                "url": "http://www.profitquotes.com/cgi/?a=news&ticker=a&w=&story=202002202002101230PR_NEWS_USPR_____IO14584",
                "accurate": true,
                "date": "2020-02-10T18:03:03Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Asian Stocks And American Futures Fall On Apple Warning",
                "content": "Asian stocks declined after Apple warned about its quarterly revenue. In a statement, the company said that it would not meet its guidance because of the coronavirus outbreak. The disease has limited iPhone’s production and demand. This is because China is the fastest-growing iPhone market in the world. Most iPhones are manufactured in the country. In China, the A50 index and Hang Seng declined by 160 and 401 points respectively. In Australia, the ASX declined by 18 points. In the United States,",
                "url": "https://www.actionforex.com/contributors/fundamental-analysis/272711-asian-stocks-and-american-futures-fall-on-apple-warning/",
                "accurate": true,
                "date": "2020-02-18T07:33:55Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "(Reuters) - Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain. \n\nCustomers walk past an Apple logo inside of an Apple store at Grand Central Station in New York, U.S., August 1, 2018.  REUTERS/Lucas Jackson \n\nThe drop in Apple’s stock is set to wipe nearly $30 billion off its market capitalization, ju",
                "url": "https://ca.reuters.com/article/businessNews/idCAKBN20C1T4",
                "accurate": true,
                "date": "2020-02-18T14:11:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple No.1 in Q4 smartphone shipments",
                "content": "The overall decline was partly due to weak shipment growth in China, where consumers are still waiting for cheaper 5G handsets. \n \nApple was No,1 in Q4 while Samsung was No.1 for the full year. Huawei was No.2 for the year and Apple No.3. \n \nApple shipped 73.8 million iPhones in 4Q19 for y-o-y growth of 7.9%. \n \n<?php echo do_shortcode('[inread_parallax slot=\"DFP-EW-InRead2-Mobile\" width=\"300\"]'); ??> \n  \n \n<?php echo do_shortcode('[inread_parallax slot=\"DFP-EW-InRead2-Mobile\" width=\"300\"]'); ??",
                "url": "https://www.phoneweek.co.uk/apple-no-1-in-q4-smartphone-shipments/",
                "accurate": true,
                "date": "2020-02-03T08:57:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "FY2020 Earnings Estimate for Applied Materials, Inc. Issued By KeyCorp (NASDAQ:AMAT)",
                "content": "Feb 17, 2020( Ticker Report: http://www.tickerreport.com/ Delivered by Newstex)  Applied Materials, Inc. (NASDAQ:AMAT) - Research analysts at KeyCorp lifted their FY2020 EPS estimates for shares of Applied Materials in a report released on Wednesday, February 12th. KeyCorp analyst W. Twigg now anticipates that the manufacturing equipment provider will post earnings of $4.23 per share for the year, up from their previous forecast of $3.65. KeyCorp currently has a \"Overweight\" rating and a $86.00 ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y79-SX31-F03R-N3BK-00000-00",
                "accurate": null,
                "date": "2020-02-17T13:36:09Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: 14th largest institutional shareholder LSV Asset Management increases its position in Apple Hospitality REIT",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 19 February 2020 13:46 EST\n\nAs per SEC filings for Q3/2019, LSV Asset Management (CIK:0001050470) was ranked 14 out of 233 institutional shareholders of Apple Hospitality REIT (NYSE:APLE). LSV Asset Management increased its position in Apple Hospitality REIT by 78,700 shares (or 4.7%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple Hospitality REIT was USD16.16. At that price the purchase value of 78,700 shares is",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7S-RPV1-JB4F-Y18M-00000-00",
                "accurate": null,
                "date": "2020-02-19T19:26:55Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Stock Traders Buy High Volume of Put Options on Applied Genetic Technologies (NASDAQ:AGTC)",
                "content": "Feb 07, 2020( The Markets Daily: https://www.themarketsdaily.com Delivered by Newstex)  Applied Genetic Technologies Corp (NASDAQ:AGTC) saw unusually large options trading activity on Thursday. Stock traders purchased 2,688 put options on the company. This represents an increase of 975% compared to the average volume of 250 put options.In other Applied Genetic Technologies news, major shareholder Patrick Johan Hendrik Krol sold 81,162 shares of the firm's stock in a transaction that occurred on ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y57-J721-F03R-N1M3-00000-00",
                "accurate": null,
                "date": "2020-02-07T22:52:28Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Stock market live updates: Dow futures drop 150, Apple leads slide, Tesla jumping",
                "content": "CNBC \n\n     \nBuyers and employees of the American multinational technology company Apple store are seen wearing face masks. \n \nMiguel Candela | SOPA |  \n     \nThis is a live blog. Check back for updates. \n  8:45 am: Tesla rises as analysts hike targets   \nShares of Tesla have risen more than 4% in premarket trading after analysts at Morgan Stanley and Bernstein raised their price targets on the stock. Both new targets are below where the stock closed on Friday, but Morgan Stanley’s Adam Jonas sa",
                "url": "https://www.ahlainnews.com/2020/02/18/stock-market-live-updates-dow-futures-drop-150-apple-leads-slide-tesla-jumping/",
                "accurate": true,
                "date": "2020-02-18T15:26:10Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: 35th largest institutional shareholder Sumitomo Mitsui Trust Holdings, Inc. increases its position in Applied Materials",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 03 February 2020 16:54 EST\n\nAs per SEC filings for Q3/2019, Sumitomo Mitsui Trust Holdings, Inc. (CIK:0001475365) was ranked 35 out of 974 institutional shareholders of Applied Materials (NASDAQ:AMAT). Sumitomo Mitsui Trust Holdings, Inc. increased its position in Applied Materials by 594,365 shares (or 16.1%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Materials was USD56.72. At that price the purchase valu",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4C-WGX1-DXKH-N4MR-00000-00",
                "accurate": true,
                "date": "2020-02-03T23:56:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Inc. (NASDAQ:AAPL) Expected to Earn FY2020 Earnings of $14.25 Per Share",
                "content": "Apple logo \n\nApple Inc. (NASDAQ:AAPL) - Analysts at  Jefferies Financial Group increased their FY2020 earnings estimates for Apple  in a research note issued on  Wednesday, February 5th. Jefferies Financial Group analyst K. Mcnealy now anticipates that the iPhone maker will post earnings per share of $14.25 for the year, up from their prior forecast of $14.15. Jefferies Financial Group  has a \"Buy\" rating and a $350.00 price objective on the stock. Jefferies Financial Group also issued estimates",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5B-HSG1-DXK2-M1M4-00000-00",
                "accurate": null,
                "date": "2020-02-08T04:18:28Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple (NASDAQ:AAPL) Price Target Increased to $385.00 by Analysts at DA Davidson",
                "content": "Feb 01, 2020( Transcript Daily: https://transcriptdaily.com Delivered by Newstex)             https://www.marketbeat.com/logos/apple-inc-logo.pngApple (NASDAQ:AAPL) had its target price hoisted by DA Davidson from $375.00 to $385.00 in a research note issued to investors on Wednesday, The Fly[1] reports. DA Davidson currently has a positive rating on the iPhone maker's stock.A number of other research firms have also recently weighed in on AAPL. \n\nJefferies Financial Group raised their price tar",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3Y-M6F1-F03R-N27D-00000-00",
                "accurate": true,
                "date": "2020-02-01T22:00:21Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "$1.31 Earnings Per Share Expected for Science Applications International Corp (NYSE:SAIC) This Quarter",
                "content": "Science Applications International logo Analysts predict that Science Applications International Corp (NYSE:SAIC) will post earnings of $1.31 per share for the current quarter, according to            Zacks . Four analysts have made estimates for Science Applications International's earnings. The highest EPS estimate is $1.40 and the lowest is $1.22. Science Applications International reported earnings per share of $1.17 during the same quarter last year, which suggests a positive year over year",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6V-BSC1-JB40-X33K-00000-00",
                "accurate": true,
                "date": "2020-02-15T04:39:23Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "United States : Apple Reports Record First Quarter Results",
                "content": "Apple announced financial results for its fiscal 2020 first quarter ended December 28, 2019. The Company posted quarterly revenue of $91.8 billion, an increase of 9 percent from the year-ago quarter and an all-time record, and quarterly earnings per diluted share of $4.99, up 19 percent, also an all-time record. International sales accounted for 61 percent of the quarters revenue.\n\nWe are thrilled to report Apples highest quarterly revenue ever, fueled by strong demand for our iPhone 11 and iPho",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4C-PGV1-JDJN-6353-00000-00",
                "accurate": true,
                "date": "2020-02-03T22:38:55Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple (NASDAQ:AAPL) Given a $368.00 Price Target by Morgan Stanley Analysts",
                "content": "Apple (NASDAQ:AAPL) has been assigned a $368.00 price objective by research analysts at Morgan Stanley in a note issued to investors on Tuesday, Borsen Zeitung reports. The firm currently has a “buy” rating on the iPhone maker’s stock. Morgan Stanley’s price objective would indicate a potential upside of 13.25% from the stock’s current price.\n\nSeveral other brokerages also recently weighed in on AAPL. Deutsche Bank restated a “neutral” rating and set a $305.00 target price on shares of Apple in ",
                "url": "https://www.americanbankingnews.com/2020/02/18/apple-nasdaqaapl-given-a-368-00-price-target-by-morgan-stanley-analysts.html",
                "accurate": null,
                "date": "2020-02-18T13:50:37Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus to Hurt Apple Earnings: Time to Buy These ETFs?",
                "content": "Apple’s (AAPL - Free Report) shares have been exhibiting one of its best rallies, having returned about 90% in the past year 21.6% gain in the S&P 500 and 36.2% advancement in the tech-heavy Invesco QQQ Trust (QQQ - Free Report) . Decent growth prospects and impressive product launches have been aiding this tech biggie.\n\nHowever, management issued an earnings warning on Feb 17 stating that the company might not be able to meet its quarterly revenue expectations issued on Jan 28, 2020, hurt by th",
                "url": "https://www.zacks.com/stock/news/771905/coronavirus-to-hurt-apple-earnings-time-to-buy-these-etfs",
                "accurate": true,
                "date": "2020-02-18T17:16:38Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple (NASDAQ:AAPL) Price Target Cut to $297.00 by Analysts at Barclays",
                "content": "Feb 18, 2020( DailyPolitical: http://www.dailypolitical.com/ Delivered by Newstex)  Apple (NASDAQ:AAPL) had its target price reduced by investment analysts at Barclays[1] from $304.00 to $297.00 in a research report issued on Tuesday, BenzingaRatingsTable[2] reports. The firm presently has an \"equal weight\" rating on the iPhone maker's stock. Barclays[3]'s price target indicates a potential downside of 8.60% from the stock's previous close.Several other research firms have also commented on AAPL",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7K-72Y1-F03R-N44J-00000-00",
                "accurate": null,
                "date": "2020-02-18T22:42:14Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Stocks - U.S. Futures Point Lower; Apple Warning Weighs, Walmart Misses",
                "content": "Investing.com -\n\nBy Peter Nurse\n\nInvesting.com - U.S. stocks are set to open sharply lower Tuesday, as investors return from a holiday to the shock news from tech giant Apple (NASDAQ:AAPL) that it wouldn't meet its March quarter sales guidance set just three weeks ago due to the ongoing coronavirus outbreak in China.\n\nAt 7:00 AM ET (1200 GMT), futures for the S&P 500 traded 0.5% lower, futures for the Nasdaq were down 0.8%, while the Dow Jones futures contract lost 0.6%. U.S. equity markets were",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7J-KX81-F11P-X2JV-00000-00",
                "accurate": true,
                "date": "2020-02-18T18:44:46Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "GCP Applied Technologies (GCP) to Release Earnings on Wednesday",
                "content": "Feb 24, 2020( DailyPolitical: http://www.dailypolitical.com/ Delivered by Newstex)  GCP Applied Technologies (NYSE:GCP) is set to release its earnings data before the market opens on Wednesday, February 26th. Analysts expect GCP Applied Technologies to post earnings of $0.25 per share for the quarter. \n\nPersons interested in participating in the company's earnings conference call can do so using this link[1]. GCP stock[2] opened at $21.13 on Tuesday. The company has a quick ratio of 2.33, a curr",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y91-JTJ1-F03R-N0P7-00000-00",
                "accurate": true,
                "date": "2020-02-25T13:44:27Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT rises 0.7% from 14-day low, 56th largest institutional shareholder Sumitomo Mitsui Trust Holdings, Inc. increases its position in Q4/2019 Monday February 03, 2020 16:00 EST",
                "content": "AMERICAN DAILY STOCK REPORT\n\nApple Hospitality REIT Inc (NYSE:APLE), the NYSE's largest Real estate holdings & development company by market cap, increased 9.0c (0.6%) from its previous close of $US14.92 on Friday. It hit a 14-day low of $US14.91 during the day but rose 0.7% before settling at $US15.01 on Monday. Its Williams % R is -90.3 which suggests it is oversold, a bullish signal. Its Relative Strength Index [RSI] is 29.5. An RSI reading of between 0 and 30 suggests Apple Hospitality REIT'",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4C-WGY1-DXKH-N0DM-00000-00",
                "accurate": true,
                "date": "2020-02-03T23:56:54Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "07:19 EST Credit Suisse views Apple Q1 shortfall as primarily transitory",
                "content": "Credit Suisse analyst Matthew Cabral notes that due to ongoing impacts from the coronavirus, Apple announced it does not expect to meet its prior Q1 revenue guidance of $63B-$67B. The analyst views the Q1 shortfall as primarily transitory versus permanent demand destruction. His long-term remains on the impact of 5G into the second half of the year and beyond, with key debates around Apple's pricing strategy and the impact on replacement cycles. Cabral has a Neutral rating and a $290 price targe",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7R-P0B1-DYWB-B1RH-00000-00",
                "accurate": null,
                "date": "2020-02-19T12:58:49Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Is It Smart To Buy Apple Inc. (NASDAQ:AAPL) Before It Goes Ex-Dividend?",
                "content": "   \n \nSome investors rely on dividends for growing their wealth, and if you're one of those dividend sleuths, you might be intrigued to know that Apple Inc. (NASDAQ:AAPL) is about to go ex-dividend in just 3 days. You can purchase shares before the 7th of February in order to receive the dividend, which the company will pay on the 13th of February. \n \nApple's next dividend payment will be US$0.77 per share, and in the last 12 months, the company paid a total of US$3.08 per share. Based on the la",
                "url": "http://www.dailymagazine.news/is-it-smart-to-buy-apple-inc-nasdaq-aapl-before-it-goes-ex-dividend-nid-1078715.html",
                "accurate": null,
                "date": "2020-02-03T13:38:12Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "$0.33 Earnings Per Share Expected for Apple Hospitality REIT Inc (NYSE:APLE) This Quarter",
                "content": "Apple Hospitality REIT logo Wall Street analysts expect Apple Hospitality REIT Inc (NYSE:APLE) to report earnings per share of $0.33 for the current quarter,            Zacks Investment Research  reports. Four analysts have made estimates for Apple Hospitality REIT's earnings. The highest EPS estimate is $0.34 and the lowest is $0.32. Apple Hospitality REIT reported earnings of $0.36 per share in the same quarter last year, which indicates a negative year over year growth rate of 8.3%. The busin",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y74-JVD1-JB40-X0WD-00000-00",
                "accurate": null,
                "date": "2020-02-16T18:05:45Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Royal Bank of Canada Increases Applied Materials (NASDAQ:AMAT) Price Target to $75.00",
                "content": "Applied Materials (NASDAQ:AMAT) had its price target increased by equities research analysts at Royal Bank of Canada to $75.00 in a research note issued on Thursday, The Fly reports. The brokerage currently has an “outperform” rating on the manufacturing equipment provider’s stock. Royal Bank of Canada’s price objective suggests a potential upside of 14.73% from the company’s current price.\n\nOther equities analysts also recently issued reports about the stock. Cowen reissued an “outperform” rati",
                "url": "https://www.americanbankingnews.com/2020/02/13/royal-bank-of-canada-increases-applied-materials-nasdaqamat-price-target-to-75-00.html",
                "accurate": null,
                "date": "2020-02-13T13:46:17Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Qingdao Kingking Applied Chemistry - A Share rises 7.0% from 14-day low, reports Net Profit of CNY18.0m ($US2.5m) Thursday February 06, 2020 15:30 CST",
                "content": "CHINESE DAILY STOCK REPORT\n\nQingdao Kingking Applied Chemistry Co., - A Share (SZ:002094), Shenzhen's 104th largest Chemicals company by market cap, increased 4.0 fen (1.0%) from its previous close of CNY4.06 on Wednesday. It hit a 14-day low of CNY3.83 during the day but rose 7.0% before settling at CNY4.10 on Thursday. Its Williams % R is -85.3 which suggests it is oversold, a bullish signal. Its Relative Strength Index [RSI] is 17.2. An RSI reading of between 0 and 30 suggests Qingdao Kingkin",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4Y-WCT1-JB4F-Y1X2-00000-00",
                "accurate": null,
                "date": "2020-02-06T12:11:45Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Cfra Raises Applied Materials (NASDAQ:AMAT) Price Target to $68.00",
                "content": "Applied Materials (NASDAQ:AMAT) had its price objective raised by equities researchers at Cfra from $60.00 to $68.00 in a research note issued to investors on Thursday, BenzingaRatingsTable reports. The firm currently has a “hold” rating on the manufacturing equipment provider’s stock. Cfra’s price target would indicate a potential downside of 1.45% from the company’s previous close.\n\nAMAT has been the subject of several other research reports. Citigroup raised their price target on Applied Mate",
                "url": "https://www.americanbankingnews.com/2020/02/13/cfra-raises-applied-materials-nasdaqamat-price-target-to-68-00.html",
                "accurate": null,
                "date": "2020-02-13T17:13:28Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Do Options Traders Know Something About Apple (AAPL) Stock We Don't?",
                "content": "Investors in Apple Inc.  AAPL need to pay close attention to the stock based on moves in the options market lately. That is because the Mar 20, 2020 $165 Put had some of the highest implied volatility of all equity options today. \n \nWhat is Implied Volatility? \n \nImplied volatility shows how much movement the market is expecting in the future. Options with high levels of implied volatility suggest that investors in the underlying stocks are expecting a big move in one direction or the other. It ",
                "url": "https://www.nasdaq.com/articles/do-options-traders-know-something-about-apple-aapl-stock-we-dont-2020-02-27",
                "accurate": true,
                "date": "2020-02-27T15:45:56Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Earnings Reaction History: Applied Materials, 40.0% Follow-Through Indicator, 3.9% Sensitive",
                "content": "Expected Earnings Release: 02/12/2020, After-hours\n\nAvg. Extended-Hours Dollar Volume: $94,988,969\n\nApplied Materials (AMAT) is due to issue its quarterly earnings report in the upcoming extended-hours session. Given its history, traders can expect very active trading in the issue immediately following its quarterly earnings announcement. Historical earnings event related premarket and after-hours trading activity in AMAT indicates that the price change in the extended hours is likely to be of l",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y69-0T91-JBH1-X2DM-00000-00",
                "accurate": null,
                "date": "2020-02-12T19:41:05Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Why Is Applied Industrial Technologies (AIT) Up 2% Since Last Earnings Report?",
                "content": "It has been about a month since the last earnings report for Applied Industrial Technologies (AIT). Shares have added about 2% in that time frame, outperforming the S&P 500.\n\nWill the recent positive trend continue leading up to its next earnings release, or is Applied Industrial Technologies due for a pullback? Before we dive into how investors and analysts have reacted as of late, let's take a quick look at its most recent earnings report in order to get a better handle on the important driver",
                "url": "http://www.zacks.com/stock/news/778616/why-is-applied-industrial-technologies-ait-up-2-since-last-earnings-report?cid=CS-ZC-FT-realtime_blog-778616",
                "accurate": null,
                "date": "2020-02-22T17:43:01Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Institutional shareholder Washington Trust Bank decreases its position in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 01 February 2020 20:06 EST\n\nAs per SEC filings for Q3/2019, Washington Trust Bank (CIK:0000861787) was ranked 845 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Washington Trust Bank decreased its position in Apple by 2,019 shares (or 2.6%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 2,019 shares is estimated at USD521,090. At the end of the quarte",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y42-FBC1-JB4F-Y1SY-00000-00",
                "accurate": null,
                "date": "2020-02-02T02:26:19Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Analysts Trim Apple Hospitality REIT's Q3, 2019, and 2020 Earnings Forecasts",
                "content": "Forecasted earnings estimates for Q3 ending September 30, 2019, and the full year expectations for 2019 and 2020 for the years ending on December 31 for Apple Hospitality REIT Inc (NYSE:APLE, Recent Price: 15.28) have been scaled down. The Q3 earnings estimate has been decreased to $0.12 per share down from the previous consensus of $0.24 per share, while the estimate for 2019 has been decreased to $0.79 per share from the consensus of $0.83 per share and the full year 2020 estimate has also bee",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3V-YYX1-DY03-M3J6-00000-00",
                "accurate": null,
                "date": "2020-02-01T05:21:00Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "(Reuters) - Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain.\n\nThe drop in Apple's stock is set to wipe nearly $30 billion off its market capitalization, just as it was inching closer to $1.5 trillion in value. The stock was trading down at $318.74.\n\nHowever, several Wall Street brokerages dubbed App",
                "url": "https://ca.finance.yahoo.com/news/coronavirus-threatens-apple-supply-chain-135747437.html",
                "accurate": true,
                "date": "2020-02-18T14:11:16Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: Carmichael Hill & Associates, Inc. adds to its gains in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 03 February 2020 00:33 EST\n\nAs per SEC filings for Q3/2019, Carmichael Hill & Associates, Inc. (CIK:0001730295) was ranked 1658 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Carmichael Hill & Associates, Inc. increased its position in Apple by 1,919 shares (or 8.6%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the purchase value of 1,919 shares is estimated at USD49",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y49-3FD1-JB4F-Y09S-00000-00",
                "accurate": true,
                "date": "2020-02-03T06:29:41Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q2 2020 EPS Estimates for Applied Materials, Inc. (NASDAQ:AMAT) Increased by Analyst",
                "content": "Applied Materials, Inc. (NASDAQ:AMAT) – Research analysts at KeyCorp raised their Q2 2020 EPS estimates for Applied Materials in a research note issued on Wednesday, February 12th. KeyCorp analyst W. Twigg now anticipates that the manufacturing equipment provider will post earnings per share of $1.04 for the quarter, up from their previous estimate of $0.97. KeyCorp currently has a “Overweight” rating and a $86.00 price objective on the stock. KeyCorp also issued estimates for Applied Materials’",
                "url": "https://www.americanbankingnews.com/2020/02/14/q2-2020-eps-estimates-for-applied-materials-inc-nasdaqamat-increased-by-analyst.html",
                "accurate": null,
                "date": "2020-02-14T13:38:11Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Institutional shareholder Adams Asset Advisors, LLC decreases its position in Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 01 February 2020 20:38 EST\n\nAs per SEC filings for Q3/2019, Adams Asset Advisors, LLC (CIK:0001386929) was ranked 967 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Adams Asset Advisors, LLC decreased its position in Apple by 1,487 shares (or 2.4%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 1,487 shares is estimated at USD383,784. At the end of th",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y42-FBC1-JB4F-Y1TN-00000-00",
                "accurate": null,
                "date": "2020-02-02T02:26:19Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple (AAPL) Down 9.8% Since Last Earnings Report: Can It Rebound?",
                "content": "It has been about a month since the last earnings report for Apple (AAPL - Free Report) . Shares have lost about 9.8% in that time frame, underperforming the S&P 500.\n\nWill the recent negative trend continue leading up to its next earnings release, or is Apple due for a breakout? Before we dive into how investors and analysts have reacted as of late, let's take a quick look at its most recent earnings report in order to get a better handle on the important catalysts. \n\nApple’s Q1 Earnings Beat, ",
                "url": "https://www.zacks.com/stock/news/786997/apple-aapl-down-98-since-last-earnings-report-can-it-rebound",
                "accurate": null,
                "date": "2020-02-27T16:15:56Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "United States : Apple Reports Fourth Quarter Results",
                "content": "Apple announced financial results for its fiscal 2019 fourth quarter ended September 28, 2019. The Company posted quarterly revenue of $64 billion, an increase of 2 percent from the year-ago quarter, and quarterly earnings per diluted share of $3.03, up 4 percent. International sales accounted for 60 percent of the quarters revenue.\n\nWe concluded a groundbreaking fiscal 2019 with our highest Q4 revenue ever, fueled by accelerating growth from Services, Wearables and iPad, said Tim Cook, Apples C",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y50-TJN1-F11P-X1CV-00000-00",
                "accurate": null,
                "date": "2020-02-06T20:31:13Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Stock Weekly: Huangshi Dongbei Electrical Appliance- B Share drops 3.9% on firm volume",
                "content": "CHINESE WEEKLY STOCK REPORT\n\nDateline: Friday February 28, 2020\nHuangshi Dongbei Electrical Appliance Co - B Share (SS:900956), Shanghai's 51st largest Machinery/Industrial goods company by market cap, has decreased 5.0c (or 3.9%) in the past week to close at $US1.22, ending a two-week streak of rises. Compared with the SSE Composite Index which fell 159.4 points (or 5.2%) in the week, this represented a relative price increase of 1.3%. The volume was 1.2 times average trading per week of 1.1 mi",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y9N-CT61-DXKH-N1TC-00000-00",
                "accurate": null,
                "date": "2020-02-28T13:04:13Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "FY2019 Annual Report: Applied Technology Net Profit up 109% Corporate Wire Date: 12 February 2020 00:32 JST Release Date: February 06, 2020",
                "content": "JAPANESE RESULTS\n\nApplied Technology (TO:4356) reported net profit for the year-ended 31 December 2019 of JPY471m ($US4.3m), up 108.7% from JPY226m ($US2.0m) in the previous year. Earnings per share (EPS) were up 108.7% from JPY79.09 (US71.62c) in FY2018 to JPY165.06 ($US1.52) in FY2019.\n\nMajor changes compared with previous year:\n\nFavourable Changes:\n- Total revenue up 28.2% from JPY3.4b ($US30.5m) to JPY4.3b ($US39.7m)\n- EBIT Margin up from 10.0% to 15.2%\n- EBIT to total assets up from 11.9% t",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y62-TPP1-DXKH-N1X7-00000-00",
                "accurate": true,
                "date": "2020-02-11T18:36:57Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple's surprise sales warning pressures futures",
                "content": "U.S. stock index futures dropped on Tuesday as investors returned from a long weekend to a sales warning from Apple Inc that highlighted the impact of the coronavirus outbreak on global supply chains.   \nThe world's most valuable technology firm said on Monday it was unlikely to meet its March-quarter sales guidance because of slower iPhone production and weaker demand in China. \n \nShares of the iPhone maker fell 3.1% in premarket trading, while those of Apple suppliers, including , , Qorvo Inc ",
                "url": "https://www.marketscreener.com/news/Apple-s-surprise-sales-warning-pressures-futures--30011986/?countview=0",
                "accurate": null,
                "date": "2020-02-18T13:05:45Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Kuo: Supply Chain to Ramp Up for Apple's Ultra Wideband Tags in Second to Third Quarter of 2020",
                "content": "Shanghai-based manufacturing company Universal Scientific Industrial will begin supplying the system-in-package for Apple's upcoming Ultra Wideband item tracking tags in the second to third quarter of 2020, with shipments to reach tens of millions of units by the end of the year, according to analyst Ming-Chi Kuo. \nIn a research note with TF International Securities, obtained by MacRumors, Kuo said Universal Scientific Industrial will be the primary supplier of the system-in-package for the tags",
                "url": "https://www.onenewspage.us/n/Computer+Industry/1zlqhndgmh/Kuo-Supply-Chain-to-Ramp-Up-for-Apple.htm",
                "accurate": true,
                "date": "2020-02-18T14:36:23Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "European stocks slide as Apple warns on coronavirus revenue hit; HSBC down 5.8%",
                "content": "European stocks declined on Tuesday morning following a weak handover from Asia, as Apple’s revenue guidance warning rocks electronics supplier shares and coronavirus fears persist. \n  \nThe pan-European Stoxx 600 fell 0.4% by mid-morning, paring earlier losses. Basic resources shed 1.4% to lead losses while utilities bucked the trend to climb 0.9%. \n   \nTech giant Apple on Monday warned that it does not expect to meet its second-quarter revenue forecast due to lower global iPhone supply and weak",
                "url": "https://www.thelivefeeds.com/european-stocks-slide-as-apple-warns-on-coronavirus-revenue-hit-hsbc-down-5-8/",
                "accurate": null,
                "date": "2020-02-18T12:35:53Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "$1.10 Earnings Per Share Expected for Applied Industrial Technologies (NYSE:AIT) This Quarter",
                "content": "Feb 08, 2020( TheOlympiaReport: https://theolympiareport.com Delivered by Newstex)  Wall Street analysts expect Applied Industrial Technologies (NYSE:AIT) to post earnings of $1.10 per share for the current quarter, Zacks Investment Research[1] reports. Two analysts have made estimates for Applied Industrial Technologies' earnings, with estimates ranging from $1.09 to $1.10. Applied Industrial Technologies posted earnings per share of $1.16 during the same quarter last year, which indicates a ne",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5J-P5V1-JCMN-Y009-00000-00",
                "accurate": null,
                "date": "2020-02-09T05:45:50Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "$2 Billion Castor Oil & Derivatives Market Insights By Product, Application And Region - Forecast To 2025",
                "content": "DUBLIN, Feb. 10, 2020 /PRNewswire/ -- The \"Castor Oil & Derivatives Market Size, Share & Trends Analysis Report By Product (Sebacic Acid, 12 HSA, Ricinoleic Acid, Castor Wax, Undecylenic Acid), By Application, By Region, And Segment Forecasts, 2019-2025\"... \n DUBLIN , Feb. 10, 2020 /PRNewswire/ -- The \"Castor Oil & Derivatives Market Size, Share & Trends Analysis Report By Product (Sebacic Acid, 12 HSA, Ricinoleic Acid, Castor Wax, Undecylenic Acid), By Application, By Region, And Segment Foreca",
                "url": "https://www.thestreet.com/press-releases/-2-billion-castor-oil-amp-derivatives-market-insights-by-product-application-and-region-forecast-to-2025-15234736",
                "accurate": null,
                "date": "2020-02-10T17:44:26Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Amid Coronavirus outbreak, Apple warns investors it won't meet its Q2 financial goals",
                "content": "February 27 -- Apple is warning investors that it won't meet its second-quarter financial guidance because the viral outbreak in China has cut the production of iPhones.\n\n\nThe Cupertino, California-based company said Monday that all of its iPhone manufacturing facilities are outside Hubei province, the epicenter of the outbreak, and all have been reopened. But the company said production is ramping up slowly.\n\"The health and well-being of every person who helps make these products possible is ou",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y9F-KXW1-DYDW-708V-00000-00",
                "accurate": true,
                "date": "2020-02-27T13:57:58Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "India: CBDT issues clarification on the applicability of TDS provisions on Mutual Fund dividend",
                "content": "The Finance Bill, 2020 proposed to remove Dividend Distribution Tax (DDT) at the level of Company/ Mutual Fund and proposed to tax the same in the hands of share/unit holder. It was also proposed to levy TDS at the rate of 10% on the dividend/ income paid by the Company/Mutual Fund to its share/unit holder if the amount of such dividend/ income exceeds five thousand rupees in a Financial Year.\n\nQueries have been received to the effect that whether under the proposed section 194K, the Mutual Fund",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y50-K7J1-JB5P-J2WR-00000-00",
                "accurate": true,
                "date": "2020-02-06T16:34:05Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: Washington Trust Bank keeps selling more of Applied Materials",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 01 February 2020 11:58 EST\n\nAs per SEC filings for Q3/2019, Washington Trust Bank (CIK:0000861787) was ranked 218 out of 974 institutional shareholders of Applied Materials (NASDAQ:AMAT). Washington Trust Bank decreased its position in Applied Materials by 4,427 shares (or 2.2%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Materials was USD56.72. At that price the sale value of 4,427 shares is estimated at US",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3Y-3PN1-JB4F-Y3V8-00000-00",
                "accurate": true,
                "date": "2020-02-01T18:23:15Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Roku earnings preview: First read on Disney and Apple impacts",
                "content": "By Emily Bary \n \nThe options market is looking for a 15.6% post-earnings swing, but that would be a smaller stock move than in recent quarters \n \nFresh off a carriage renegotiation with Fox Corp., Roku Inc. is about to face another test. \n \nThe streaming company is set to post December-quarter results on Thursday afternoon, with a report that will not only show how well Roku (ROKU) devices and connected TVs sold during the holidays but also provide some early indications of how Roku benefited fr",
                "url": "https://www.morningstar.com/news/marketwatch/20200211588/roku-earnings-preview-first-read-on-disney-and-apple-impacts",
                "accurate": null,
                "date": "2020-02-11T21:48:29Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Taiwan Province of China : Foreign Profit-seeking Enterprise Can Apply for Advance Assessment of Net Profit Ratio and Domestic Profit Contribution Ratio for Calculation of Income Derived from R.O.C.",
                "content": "The National Taxation Bureau of the Northern Area (NTBNA), Ministry of Finance, indicates that income earned by a foreign enterprise from a domestic enterprise is subject to withholding per statutory tax rates, which has been required to be withheld in advance at the time of payment. The foreign enterprise, in accordance with Article 8 of the Income Tax Act, can apply for re-calculating its R.O.C. source income afterwards by providing relevant evidential documentation to the competent authority.",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5F-JBP1-JDJN-62XX-00000-00",
                "accurate": true,
                "date": "2020-02-08T22:25:17Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Equities End Mixed, Pulled Lower by Apple's Warning on First-Quarter Guidance Over COVID-19",
                "content": "Stocks ended mixed Tuesday, weighed down by Apple's (AAPL) Monday announcement that it does not expect to meet its second-quarter guidance because its manufacturing partners in China are taking longer than expected to ramp up production  after being shuttered longer than planned due to the COVID-19 outbreak.\n\nApple in late January said second-quarter revenue would be between $63 billion and $67 billion, but it said on Monday that there had been a slower return to normal conditions than it had an",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7K-6481-JBH1-X10S-00000-00",
                "accurate": null,
                "date": "2020-02-18T21:50:58Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "UBS Group Raises Applied Materials (NASDAQ:AMAT) Price Target to $51.00",
                "content": "Applied Materials logo Applied Materials (NASDAQ:AMAT) had its price target lifted by analysts at UBS Group  from $48.00 to $51.00 in a report released on Thursday,            BenzingaRatingsTable  reports. The brokerage currently has a \"sell\" rating on the manufacturing equipment provider's stock. UBS Group's target price would indicate a potential downside of 21.98% from the company's previous close. \n\nA number of other research analysts have also recently weighed in on AMAT. Wells Fargo & Co ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6M-CWW1-DXK2-M40G-00000-00",
                "accurate": null,
                "date": "2020-02-14T06:29:57Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Q4 2019 Report: 189th largest institutional shareholder Harbor Island Capital LLC decreases its position in Applied Materials",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 01 February 2020 11:16 EST\n\nAs per SEC filings for Q3/2019, Harbor Island Capital LLC (CIK:0001730580) was ranked 189 out of 974 institutional shareholders of Applied Materials (NASDAQ:AMAT). Harbor Island Capital LLC decreased its position in Applied Materials by 2,266 shares (or 0.87%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Materials was USD56.72. At that price the sale value of 2,266 shares is estima",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3X-Y1K1-DXKH-N181-00000-00",
                "accurate": true,
                "date": "2020-02-01T17:22:10Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "FY2020 Earnings Estimate for Applied Materials, Inc. (NASDAQ:AMAT) Issued By B. Riley",
                "content": "Applied Materials logo \n\nApplied Materials, Inc. (NASDAQ:AMAT) - Stock analysts at  B. Riley upped their FY2020 earnings estimates for shares of Applied Materials  in a note issued to investors on  Thursday, February 13th. B. Riley analyst C. Ellis now anticipates that the manufacturing equipment provider will post earnings of $4.18 per share for the year, up from their prior forecast of $3.75. B. Riley currently  has a \"Buy\" rating and a $74.00 price target on the stock. B. Riley also issued es",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7B-JXF1-DXK2-M08D-00000-00",
                "accurate": null,
                "date": "2020-02-17T18:12:18Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "What's moving the market right now: Dow futures down 680, airlines slide, Apple drops",
                "content": "7:01 am: Coronavirus fears increase chances the Fed cuts interest rates \n\nThe Federal Reserve may be forced to cut interest rates this year as worries about the coronavirus keep spreading, according to an Evercore ISI note to clients on Monday. “With outbreaks of the Wuhan virus in South Korea and Italy suggesting that it may be on the brink of morphing into a global pandemic we raise our estimate of the likelihood that the Fed cuts interest rates this year to 45 per cent,” strategist Krishna Gu",
                "url": "https://www.businessmayor.com/whats-moving-the-market-right-now-dow-futures-down-680-airlines-slide-apple-drops/",
                "accurate": null,
                "date": "2020-02-24T12:17:22Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple shares drop as coronavirus sisrupts supply chain",
                "content": "British Herald  Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the i… https://t.co/SICX88iOoL  1 hour ago \n\nDavid smith  RT @markets : Apple Inc.’s shares fell 4.1% in pre-market trading after the company said the fallout from the coronavirus will cause it to m…  1 hour ago \n\nTinFoilSec™  Coronavirus threatens Apple supply chain, sales; shares drop https://t.co/OWsX3nByfL  2 hours ago \n\nChad Dunsby  Coronavirus threatens Apple supply",
                "url": "https://www.onenewspage.us/video/20200219/12837955/Apple-shares-drop-as-coronavirus-sisrupts-supply-chain.htm",
                "accurate": true,
                "date": "2020-02-19T11:56:28Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Cuts Its Revenue Guidance for Fiscal Q2",
                "content": "Apple's Banner Holiday-Season Quarter Tops Projections \nApple's fiscal first-quarter results released Tuesday provided the latest proof that the fears hanging over the consumer electronics icon might have been unfounded. The company's profits and revenue.. \n\nCredit: Cheddar Inc.     Duration: 02:53 Published 3 weeks ago",
                "url": "https://www.onenewspage.us/n/Markets/1zlqhnd8aa/Apple-Cuts-Its-Revenue-Guidance-for-Fiscal-Q2.htm",
                "accurate": null,
                "date": "2020-02-18T00:06:44Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: Cornerstone Investment Partners, LLC keeps selling more of Apple",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 01 February 2020 17:50 EST\n\nAs per SEC filings for Q3/2019, Cornerstone Investment Partners, LLC (CIK:0001328062) was ranked 347 out of 2821 institutional shareholders of Apple (NASDAQ:AAPL). Cornerstone Investment Partners, LLC decreased its position in Apple by 60,360 shares (or 17.6%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Apple was USD258.09. At that price the sale value of 60,360 shares is estimated at USD",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y3Y-XJY1-DXKH-N2HM-00000-00",
                "accurate": true,
                "date": "2020-02-01T23:20:24Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "India : CBDT issues clarification on the applicability of TDS provisions on Mutual Fund dividend",
                "content": "The Finance Bill, 2020 proposed to remove Dividend Distribution Tax (DDT) at the level of Company/ Mutual Fund and proposed to tax the same in the hands of share/unit holder. It was also proposed to levy TDS at the rate of 10% on the dividend/ income paid by the Company/Mutual Fund to its share/unit holder if the amount of such dividend/ income exceeds five thousand rupees in a Financial Year.\n\nQueries have been received to the effect that whether under the proposed section 194K, the Mutual Fund",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4X-B991-JDJN-631T-00000-00",
                "accurate": true,
                "date": "2020-02-06T04:01:56Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Analysts Scale Back Apple's Q2, 2020, and 2021 Earnings Forecasts",
                "content": "Apple Inc's (NASDAQ:AAPL, Recent Price: 319.00) consensus estimates for Q2 ending March 31, 2020, and the full year forecasts for 2020 and 2021 have been decreased. The Q2 earnings estimate has been scaled down to $2.84 per share down from the previous consensus estimate of $3.00 per share, while the estimate for 2020 has been scaled down to $13.76 per share from the consensus forecast of $13.91 per share and the full year 2021 estimate has also been reduced from $15.73 per share to $15.67 per s",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7P-B3T1-JBH1-X19J-00000-00",
                "accurate": null,
                "date": "2020-02-19T04:29:25Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Shares Drop As Coronavirus Disrupts Supply Chain",
                "content": "Apple shares fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower. \n \nThe fall came after Apple warned of lower sales in the current quarter, saying the coronavirus outbreak was pressuring its supply chain. \n \nAccording to Reuters, the drop in the iPhone maker's stock is set to wipe nearly $30 billion off its market capitalization. \n \nPrior to the outbreak, the company was inching closer to $1.5 trillion in value.",
                "url": "https://www.onenewspage.us/video/20200219/12836910/Apple-Shares-Drop-As-Coronavirus-Disrupts-Supply-Chain.htm",
                "accurate": null,
                "date": "2020-02-18T23:56:17Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "$2 Billion Castor Oil & Derivatives Market Insights by Product, Application and Region - Forecast to 2025",
                "content": "DUBLIN , Feb. 10, 2020 /PRNewswire/ -- The \"Castor Oil & Derivatives Market Size, Share & Trends Analysis Report By Product (Sebacic Acid, 12 HSA, Ricinoleic Acid, Castor Wax, Undecylenic Acid), By Application, By Region, And Segment Forecasts, 2019-2025\" report has been added to ResearchAndMarkets.com 's offering. \n\nThe global castor oil and derivatives market size is expected to reach USD 2 billion by 2025, expanding at a CAGR of 6.7%. \n\nThe market is anticipated to grow at a fast pace owing t",
                "url": "https://www.wfmz.com/news/pr_newswire/pr_newswire_food_beverages/billion-castor-oil-derivatives-market-insights-by-product-application-and/article_9a42c44f-5885-55b6-b55b-0f05aaec22ec.html",
                "accurate": null,
                "date": "2020-02-11T01:16:31Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Quarterly Report Analysis Q3 2019: Gree Electric Appliances reports Net Profit of CNY8.4b ($US1.2b) Corporate Wire Date: 05 February 2020 15:23 CST",
                "content": "CHINESE RESULTS\n\n\n\nGree Electric Appliances (SZ:000651) announced net profit for the quarter-ended 30 September 2019 of CNY8.4b ($US1.2b).\n\n\n\n\n Quarter-ended 30 Sep [Q3/2019] 30 Jun [Q2/2019] 31 Mar [Q1/2019]\n EPS, CNY 1.0 1.0 1.0\n Revenue, CNY billion 58.3 57.3 41.0\n Revenue, $US billion 8.2 8.0 5.8\n Sequential growth in Revenue % - 39.82 -\n Net Profit, CNY billion 8.4 8.1 5.7\n Net Profit, $US 1.2billion 1.1billion 796million\n Sequential growth in Net Profit % - 42.43 -\n\nCompared with the previ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4R-HRG1-JB4F-Y2MN-00000-00",
                "accurate": true,
                "date": "2020-02-05T09:43:07Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Applied Materials forecasts current quarter revenue, profit above estimates Feb 12 (Reuters) - Chip gear maker Applied Materials Inc forecast second-quarter revenue and profit above Wall Street estimates on Wednesday, as clients...",
                "content": "Feb 12 (Reuters) - Chip gear maker Applied Materials Inc forecast second-quarter revenue and profit above Wall Street estimates on Wednesday, as clients upgraded their semiconductor equipment ahead of a global 5G roll out. \n \nFor the current-quarter, the company expects revenue of $4.34 billion, plus or minus $200 million, above analysts' expectations of $4.05 billion, according to IBES data from Refinitiv. \n \nThe company expects adjusted profit to be in the range of 98 cents per share to $1.10 ",
                "url": "https://www.thisismoney.co.uk/wires/reuters/article-7997241/Applied-Materials-forecasts-current-quarter-revenue-profit-estimates.html",
                "accurate": true,
                "date": "2020-02-12T21:14:52Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Q4 2019 Report: 3rd largest institutional shareholder Capital World Investors decreases its position in Applied Materials",
                "content": "AMERICAN DAILY STOCK REPORT\n\nCorporate Wire Date: 22 February 2020 15:08 EST\n\nAs per SEC filings for Q3/2019, Capital World Investors (CIK:0001422849) was ranked 3 out of 974 institutional shareholders of Applied Materials (NASDAQ:AMAT). Capital World Investors decreased its position in Applied Materials by 7,225,462 shares (or 19.5%) in Q4/2019. During the quarter the Volume Weighted Average Price (VWAP) of Applied Materials was USD56.72. At that price the sale value of 7,225,462 shares is esti",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y8F-07W1-DXKH-N45Y-00000-00",
                "accurate": null,
                "date": "2020-02-22T21:15:12Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple’s coronavirus warning was a foreshock for earnings. But investors shouldn’t freak out just yet",
                "content": "Apple’s surprise warning that it won’t meet its first quarter revenue guidance because of the coronavirus sent tremors through global financial markets. Investors awoke Tuesday to the idea that other companies with exposure to China might not meet their first quarter earnings expectations, either. \n\nThe billion dollar question: Is the financial fallout from coronavirus a short-term problem or a longer-term trend? \n \n“This could be a very short-lived one-quarter blip,” JJ Kinahan, chief market st",
                "url": "https://www.wgowam.com/news/apples-coronavirus-warning-was-a-foreshock-for-earnings-but-investors-shouldnt-freak-out-just-yet/",
                "accurate": null,
                "date": "2020-02-19T06:55:25Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Asia stocks and US futures drop after Apple warning; STI down 0.4%",
                "content": "TOKYO (REUTERS) – US stock futures slipped from record levels on Tuesday (Feb 18) after Apple said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \n  \nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. \n  \nS&P500 e-mini futures dipped as much as 0.2 pe",
                "url": "https://fntalk.com/companies/asia-stocks-and-us-futures-drop-after-apple-warning-sti-down-0-4/",
                "accurate": null,
                "date": "2020-02-18T02:33:13Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Semiconductor Systems to Aid Applied Materials (AMAT) Q1 Earnings",
                "content": "Applied Materials, Inc. (AMAT - Free Report) fiscal first-quarter 2020 results, which are scheduled to be released on Feb 12, are likely to reflect solid momentum across Semiconductor Systems segment.\n\nThe underlined segment offers equipment for front-end operations in the semiconductor manufacturing process.\n\nWe note that the company has been leading the global semiconductor industry for over 20 years. Moreover, the company is a global leader in semiconductor equipment sales.\n\nMoreover, the seg",
                "url": "https://www.zacks.com/stock/news/760219/semiconductor-systems-to-aid-applied-materials-amat-q1-earnings",
                "accurate": null,
                "date": "2020-02-11T14:22:04Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Do Options Traders Know Something About Apple (AAPL) Stock We Don't?",
                "content": "Investors in Apple Inc. (AAPL - Free Report) need to pay close attention to the stock based on moves in the options market lately. That is because the Mar 20, 2020 $165 Put had some of the highest implied volatility of all equity options today.\n\nWhat is Implied Volatility?\n\nImplied volatility shows how much movement the market is expecting in the future. Options with high levels of implied volatility suggest that investors in the underlying stocks are expecting a big move in one direction or the",
                "url": "https://www.zacks.com/stock/news/786748/do-options-traders-know-something-about-apple-aapl-stock-we-dont",
                "accurate": null,
                "date": "2020-02-27T13:56:34Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Coronavirus threatens Apple supply chain, sales; shares drop",
                "content": "(Reuters) – Shares of Apple Inc fell 2 % on Tuesday and dragged the stocks of its suppliers across the globe lower, after the iPhone maker warned of lower sales in the current quarter acknowledging that the coronavirus outbreak was pressuring its supply chain. \n \nThe drop in Apple’s stock is set to wipe nearly $30 billion off its market capitalization, just as it was inching closer to $1.5 trillion in value. The stock was trading down at $318.74. \n \nHowever, several Wall Street brokerages dubbed",
                "url": "http://huffington-global.com/coronavirus-threatens-apple-supply-chain-sales-shares-drop/",
                "accurate": null,
                "date": "2020-02-18T21:57:47Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "O'Melveny & Myers, Davis Polk Advised on Returned Hong Kong IPO Application",
                "content": "O'Melveny & Myers and Davis Polk & Wardwell advised on a listing application that was returned in December by the Hong Kong Stock Exchange.\n\nThe application, filed by Chinese biotech company Akeso Inc., was jointly sponsored by Morgan Stanley and J.P.Morgan. This is the first time either bank has a sponsored main board listing application rejected by the stock exchange. In 2016, a Growth Enterprise Market listing application sponsored by J.P.Morgan was also returned.\n\n\n\nAccording to the applicat",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4J-HX61-JBM3-R04W-00000-00",
                "accurate": null,
                "date": "2020-02-04T15:20:12Z"
            }
        ],
        "SC_Sio2U4JD7cQ": [
            {
                "nobiasLeaning": "Buy",
                "title": "US STOCKS-Apples surprise sales warning pressures futures",
                "content": "(Reuters) - U.S. stock index futures dropped on Tuesday as investors returned from a long weekend to a sales warning from Apple Inc that highlighted the impact of the coronavirus outbreak on global supply chains. \n\nThe world’s most valuable technology firm ( AAPL.O ) said on Monday it was unlikely to meet its March-quarter sales guidance because of slower iPhone production and weaker demand in China. \n\nShares of the iPhone maker fell 3.1% in premarket trading, while those of Apple suppliers, inc",
                "url": "https://uk.reuters.com/article/usa-stocks/us-stocks-apples-surprise-sales-warning-pressures-futures-idUKL4N2AI33Q",
                "accurate": true,
                "date": "2020-02-18T13:10:59Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "US STOCKS-Apples surprise sales warning pressures futures",
                "content": "(Reuters) - U.S. stock index futures dropped on Tuesday as investors returned from a long weekend to a sales warning from Apple Inc that highlighted the impact of the coronavirus outbreak on global supply chains. \n\nThe world’s most valuable technology firm ( AAPL.O ) said on Monday it was unlikely to meet its March-quarter sales guidance because of slower iPhone production and weaker demand in China. \n\nShares of the iPhone maker fell 3.1% in premarket trading, while those of Apple suppliers, inc",
                "url": "https://in.reuters.com/article/usa-stocks/us-stocks-apples-surprise-sales-warning-pressures-futures-idINL4N2AI33Q",
                "accurate": null,
                "date": "2020-02-18T13:31:05Z"
            }
        ],
        "LESJ7cNvrmKoIw": [
            {
                "nobiasLeaning": "Sell",
                "title": "Samsung's Q4 Profit Tumbles As Apple Takes Lead In Smartphones",
                "content": "Lagos – Samsung has reported the end to a rough year, a day after its Chief rival Apple posted an all-time high in revenue and earnings and reclaimed its title as the world's biggest smartphone maker.\n\nSamsung said its fourth-quarter operating profit tumbled by 34% to 7.16 trillion won ($6 billion).\n\nIts overall revenue edged up 1% to 59.88 trillion won ($50.6 billion).\n\nLast year marked its worst performance since 2015, as noted by Reuters, with its operating profit falling by 52%. Apple on Tue",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4X-B991-JDJN-60TP-00000-00",
                "accurate": true,
                "date": "2020-02-06T03:58:57Z"
            }
        ],
        "s535d8DqW59Tbw": [
            {
                "nobiasLeaning": "Buy",
                "title": "Millions left on the table as Ontario doles out compensation to parents amid teachers’ strikes:Three-quarters of those eligible haven’t yet applied for payouts aimed at easing financial hit caused by teacher strike action, ministry figures show.",
                "content": "The province is paying out millions to parents as a result of escalating teacher strikes — but more than three quarters of those eligible for the child-care compensation have not applied. \n \nAs of Tuesday, the province had received 342,856 applications since announcing mid-January it would compensate parents between $25 and $60 per child, depending on their age, for each day schools, or school-based child-care centres, are closed because of a strike . That's less than a quarter of the roughly 1.",
                "url": "https://www.northbaynipissing.com/news-story/9843352-millions-left-on-the-table-as-ontario-doles-out-compensation-to-parents-amid-teachers-strikes/",
                "accurate": true,
                "date": "2020-02-06T08:26:28Z"
            }
        ],
        "BCCxkB9QFJdoqg": [
            {
                "nobiasLeaning": "Sell",
                "title": "US stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "TOKYO, Feb 18 (Reuters) - U.S. stock futures slipped from record levels on Tuesday after Apple Inc said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. \n\nS&P500 e-mini futures dipped as much as 0.2% i",
                "url": "https://www.msn.com/en-xl/money/topstories/global-markets-us-stock-futures-retreat-asia-dips-after-apple-warns-on-virus-impact/ar-BB106mZz?li=AAFNcqt",
                "accurate": true,
                "date": "2020-02-18T01:20:39Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "U.S. stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "By TOKYO (Reuters) - U.S. stock futures slipped from record levels on Tuesday after Apple Inc said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \n\nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. \n\nS&P500 e-mini futures dipped as much as 0.2% in ea",
                "url": "https://uk.finance.yahoo.com/news/u-stock-futures-retreat-asia-010228903.html",
                "accurate": true,
                "date": "2020-02-18T01:07:30Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "U.S. stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "TOKYO (Reuters) - U.S. stock futures slipped from record levels on Tuesday after Apple Inc ( AAPL.O ) said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \n\nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. \n\nS&P500 e-mini futures ESc1 dipped as much ",
                "url": "https://www.reuters.com/article/us-global-markets/u-s-stock-futures-retreat-asia-dips-after-apple-warns-on-virus-impact-idUSKBN20C02O",
                "accurate": null,
                "date": "2020-02-18T01:28:09Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "GLOBAL MARKETS-U.S. stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "TOKYO (Reuters) - U.S. stock futures slipped from record levels on Tuesday after Apple Inc said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \n\nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. \n\nS&P500 e-mini futures dipped as much as 0.2% in early",
                "url": "https://in.reuters.com/article/global-markets/global-markets-us-stock-futures-retreat-asia-dips-after-apple-warns-on-virus-impact-idINL4N2AI04O",
                "accurate": null,
                "date": "2020-02-18T02:51:33Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Global Markets: U.S. stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "MoreBy TOKYO (Reuters) - U.S. stock futures slipped from record levels on Tuesday after Apple Inc said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China.\n\nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic.\n\nS&P500 e-mini futures dipped as much as 0.2% in ",
                "url": "https://in.finance.yahoo.com/news/global-markets-u-stock-futures-023936819.html",
                "accurate": null,
                "date": "2020-02-18T02:57:45Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "GLOBAL MARKETS-U.S. stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "* Asian stock markets: tmsnrt.rs/2zpUAr4  \n\nBy TOKYO, Feb 18 (Reuters) - U.S. stock futures slipped from record levels on Tuesday after Apple Inc said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \n\nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. ",
                "url": "https://www.reuters.com/article/global-markets/global-markets-u-s-stock-futures-retreat-asia-dips-after-apple-warns-on-virus-impact-idUSL4N2AI04O",
                "accurate": true,
                "date": "2020-02-18T01:07:50Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "U.S. stock futures retreat, Asia dips after Apple warns on virus impact",
                "content": "Share this article \n\nBy \n\nTOKYO (Reuters) - Asian shares fell and Wall Street retreated from record highs on Tuesday after Apple Inc said it will not meet its revenue guidance for the March quarter as the coronavirus outbreak slowed production and weakened demand in China. \n\nThe warning from the most valuable company in the United States sobered investor optimism that economic stimulus by Beijing and other countries would protect the global economy from the effects of the epidemic. \n\nRecommended",
                "url": "https://www.metro.us/news/the-big-stories/us-stock-futures-retreat-asia-dips-after-apple-warns-virus-impact",
                "accurate": true,
                "date": "2020-02-18T02:51:58Z"
            }
        ],
        "TSbNCC8n9mQeAg": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple’s ‘AirTag’ Bluetooth tracker rumoured to launch in Q3 2020",
                "content": "It looks like Apple’s often-rumoured ‘AirTag’ is set to launch by the third quarter of 2020. \n \nThe rumour comes from reliable analyst Ming-Chi Kuo and was first reported by 9to5Mac. Kuo says that Apple has plans to produce tens of millions of Bluetooth tracking devices by the end of the year. Given the Q3 2020 release date, it’s likely that the AirTags will be revealed during Apple’s September iPhone event. \n \nThere’s also a possibility the AirTag could be revealed at WWDC given its an entirely",
                "url": "https://mobilesyrup.com/2020/02/18/apples-airtag-bluetooth-tracker-rumoured-launch-q3-2020/",
                "accurate": true,
                "date": "2020-02-18T23:13:18Z"
            }
        ],
        "Sb7frvq0_wap_w": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple (NASDAQ:AAPL) Price Target Cut to $297.00",
                "content": "Apple (NASDAQ:AAPL) had its price target trimmed by Barclays from $304.00 to $297.00 in a report published on Tuesday, BenzingaRatingsTable reports. The brokerage currently has an equal weight rating on the iPhone maker’s stock. \n \nOther equities research analysts also recently issued research reports about the stock. Nomura upped their price target on shares of Apple from $280.00 to $295.00 and gave the company a neutral rating in a research note on Wednesday, January 29th. Piper Sandler upped ",
                "url": "https://www.themarketsdaily.com/2020/02/22/apple-nasdaqaapl-price-target-cut-to-297-00.html",
                "accurate": null,
                "date": "2020-02-22T08:59:09Z"
            }
        ],
        "I9QRyk7yuaViJg": [
            {
                "nobiasLeaning": "Buy",
                "title": "Dow Futures Point to Fresh Record Highs As China Cuts US Tariffs, Grapples With Coronavirus",
                "content": "The Thursday Market Minute \n\nGlobal stocks rally, while U.S. equity futures point to fresh record highs on Wall Street, as China moves to both contain the coronavirus spread and cut tariffs on U.S.-made goods to help bolster its economic response. \nChina's tariff reductions, while linked to the December Phase 1 trade agreement, suggest its prepared to meeting commitments on agricultural and energy purchases this year despite the expected coronavirus slump. \nHealth authorities confirm another 3,0",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4Y-HPD1-F00X-J2P6-00000-00",
                "accurate": true,
                "date": "2020-02-06T09:39:17Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Scraps Q2 Revenue Guidance; Says Coronavirus Will Hit iPhone Supplies, China Demand",
                "content": "Apple Inc.  scrapped its second quarter revenue guidance Monday, citing the ongoing impact of the coronavirus outbreak in China, and noted that iPhone shortages would affect the tech giant's near-term sales.\n\nApple said manufacturing sites in China that had been closed by government officials following the coronavirus outbreak were coming back on line, but added the company was experiencing \"a slower return to normal conditions than we had anticipated.\" Apple said iPhone supplies will be tempora",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7C-83C1-F00X-J0DH-00000-00",
                "accurate": true,
                "date": "2020-02-17T22:01:16Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Scraps Q2 Revenue Guidance; Says Coronavirus Will Hit iPhone Supplies, China Demand",
                "content": "Apple cautioned investors Monday that the ongoing coronavirus outbreak would hit global iPhone supplies and near-term revenues. \nApple Inc.  ( AAPL ) - Get Report  scrapped its second quarter revenue guidance Monday, citing the ongoing impact of the coronavirus outbreak in China, and noted that iPhone shortages would affect the tech giant's near-term revenues. \n\nApple said manufacturing sites in China that had been closed by government officials following the coronavirus outbreak were coming bac",
                "url": "https://www.thestreet.com/investing/apple-scraps-q2-revenue-guidance-amid-coronavirus-spread",
                "accurate": true,
                "date": "2020-02-17T21:33:54Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Roku Shares Surge As Disney, Apple Launches Drive Solid Q4 Revenue Gains",
                "content": "Roku Inc.  shares jumped higher in pre-market trading Friday after it posted stronger-than-expected fourth quarter revenues, and topped Street estimates for near-term sales, as customers flocked to its streaming service platform amid the launch of new offering from Disney and Apple. \n\nRoku recorded a narrower-than-expected fourth quarter loss of 13 cents per share over the three months ending in December, as revenues surged nearly 50% to $411.2 million. Roku added 4.6 million new customers over ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6N-CGV1-JCHV-V0VM-00000-00",
                "accurate": true,
                "date": "2020-02-14T10:07:01Z"
            }
        ],
        "a3O6pqRhwna8HA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Stock market live updates: Dow futures down 700, airlines slide, Apple drops – CNBC",
                "content": "Traders work on the floor of the New York Stock Exchange.\nBrendan McDermid | Reuters\nThis is a live blog. Please check back for updates.10:10 am: Cramer says to watch Micron for signs of a turnaround\nCNBC's Jim Cramer said on \"Squawk on the Street\" that investors should watch the chip stock Micron to judge when the Chinese economy is rebounding from the coronavirus outbreak. Cramer said that Micron, which is down 3.5% and trading about $55 per share Monday morning, has several positive character",
                "url": "https://www.cnbc.com/2020/02/24/stock-market-today-live.html",
                "accurate": true,
                "date": "2020-02-24T15:13:06Z"
            }
        ],
        "4nbLX2tGrQkVrw": [
            {
                "nobiasLeaning": "Buy",
                "title": "Dow Jones Today, Futures Retreat As Coronavirus Cases Surge: Cisco Dives; Applied Materials, Tempur Sealy Soar On Earnings",
                "content": "Stock futures backed off briskly early Thursday as a surge in reported coronavirus cases in China pointed to a longer, deeper impact than expected. Applied Materials (AMAT), Tempur Sealy (TPX) and Linde (LIN) rallied on earnings news. Cisco Systems (CSCO) fell to the bottom of trhe Dow Jones today on disappointing quartlery results.\n\nNasdaq futures veered 0.9% below fair value, while S&P 500 futures fell 0.7% on the stock market today. Dow Jones futures dropped 0.6%, propped slightly by Caterpil",
                "url": "https://www.investors.com/market-trend/stock-market-today/dow-jones-today-futures-retreat-coronavirus-cases-surge-cisco-dives-tempur-sealy-soars/",
                "accurate": true,
                "date": "2020-02-13T13:42:21Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Dow Jones Today, Stocks Retreat As Coronavirus Cases Surge: Cisco Dives; Applied Materials, Tempur Sealy Soar On Earnings",
                "content": "https://www.investors.com/wp-content/uploads/2018/12/Stock-NYSE-09-adobe.jpg\n\nStocks staged a modest pullback on Thursday, following Wednesday's rally to new highs. Global markets traded lower after a surge in reported coronavirus cases in China raised concerns that authorities were mismanaging the outbreak. Tempur Sealy, Generac Holdings and Linde rallied on earnings news. Cisco Systems fell to the bottom of the Dow Jones today on disappointing quarterly results.\n\nThe Nasdaq pared its early dec",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6M-XX01-JCBB-K26H-00000-00",
                "accurate": null,
                "date": "2020-02-14T07:18:02Z"
            }
        ],
        "6BgMYySItNySUg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple will miss quarterly earnings estimates due to coronavirus",
                "content": "Apple issued a rare earnings warning on Monday, saying it would not meet quarterly revenue expectations due to the impact of the coronavirus, which will limit iPhone production and limit product demand in China. \n\nWhy it matters : Lots of companies rely on China for production, but unlike most U.S. tech companies, Apple also gets a significant chunk of its revenue from sales in China. \n\nDetails : The company said in a statement that it expects slower revenue due to a combination of slower iPhone",
                "url": "https://www.axios.com/apple-will-miss-quarterly-earnings-estimates-due-to-coronavirus-558c2871-eea6-47b6-9ab8-c0b1cd3f96ce.html",
                "accurate": null,
                "date": "2020-02-17T22:09:20Z"
            }
        ],
        "dEjVflcznjSr0g": [
            {
                "nobiasLeaning": "Sell",
                "title": "Brokerages Expect Applied Optoelectronics Inc (NASDAQ:AAOI) to Post -$0.23 Earnings Per Share",
                "content": "Wall Street brokerages expect that Applied Optoelectronics Inc (NASDAQ:AAOI) will announce earnings of ($0.23) per share for the current quarter, according to Zacks Investment Research . Five analysts have issued estimates for Applied Optoelectronics’ earnings. The highest EPS estimate is ($0.21) and the lowest is ($0.25). Applied Optoelectronics reported earnings of ($0.02) per share in the same quarter last year, which indicates a negative year-over-year growth rate of 1,050%. The company is s",
                "url": "https://www.themarketsdaily.com/2020/02/04/brokerages-expect-applied-optoelectronics-inc-nasdaqaaoi-to-post-0-23-earnings-per-share.html",
                "accurate": true,
                "date": "2020-02-04T13:14:50Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "UBS Group Analysts Give Apple (NASDAQ:AAPL) a $355.00 Price Target",
                "content": "Apple (NASDAQ:AAPL) has been assigned a $355.00 target price by equities research analysts at UBS Group  in a research report issued to clients and investors on Tuesday, Borsen Zeitung reports. The firm currently has a “buy” rating on the iPhone maker’s stock. UBS Group’s target price suggests a potential upside of 11.29% from the stock’s previous close. \n \nOther analysts also recently issued research reports about the stock. Robert W. Baird boosted their price objective on shares of Apple from ",
                "url": "https://www.themarketsdaily.com/2020/02/18/ubs-group-analysts-give-apple-nasdaqaapl-a-355-00-price-target.html",
                "accurate": null,
                "date": "2020-02-18T23:14:09Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Zacks: Applied DNA Sciences Inc (NASDAQ:APDN) Given Consensus Recommendation of “Strong Buy” by Analysts",
                "content": "Shares of Applied DNA Sciences Inc (NASDAQ:APDN) have been assigned a consensus broker rating score of 1.00 (Strong Buy) from the one analysts that cover the company, Zacks Investment Research reports. One analyst  has rated the stock with a strong buy rating. \n \nBrokerages have set a 1 year consensus price target of $8.00 for the company, according to Zacks. Zacks has also assigned Applied DNA Sciences an industry rank of 98 out of 255 based on the ratings given to related companies. \n  \nSevera",
                "url": "https://www.themarketsdaily.com/2020/02/28/zacks-applied-dna-sciences-inc-nasdaqapdn-given-consensus-recommendation-of-strong-buy-by-analysts.html",
                "accurate": true,
                "date": "2020-02-28T10:59:52Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT (NYSE:APLE) Issues  Earnings Results, Misses Expectations By $0.22 EPS",
                "content": "Apple Hospitality REIT (NYSE:APLE) posted its quarterly earnings results on Monday. The real estate investment trust reported $0.11 earnings per share (EPS) for the quarter, missing the Thomson Reuters’ consensus estimate of $0.33 by ($0.22), Fidelity Earnings reports. The business had revenue of $289.97 million during the quarter, compared to analyst estimates of $288.45 million. Apple Hospitality REIT had a return on equity of 5.37% and a net margin of 14.20%. \n \nAPLE stock traded down $0.40 d",
                "url": "https://www.themarketsdaily.com/2020/02/25/apple-hospitality-reit-nyseaple-issues-earnings-results-misses-expectations-by-0-22-eps.html",
                "accurate": null,
                "date": "2020-02-25T16:04:32Z"
            }
        ],
        "c8VBIEdAwFRBLg": [
            {
                "nobiasLeaning": "Buy",
                "title": "Top 5 Companies in the Application Software Industry With the Highest Projected Earnings Growth (RNG, HUBS, PAYC, AVYA, AMSWA)",
                "content": "Written on Sat, 02/01/2020 - 5:25am \n \nBy Shiri Gupta \n \nBelow are the three companies in the Application Software industry with the highest projected earnings growth.  The growth of earnings per share (current fiscal year estimated vs. last year actual) is important to gauge future profitability and relative value.  Higher EPS growth generally justifies higher earnings multiples. \n\nRingcentral In-A ranks highest with a projected earnings growth of 210.0%.  Following is Hubspot Inc with a projec",
                "url": "http://www.mysmartrend.com/news-briefs/news-watch/top-5-companies-application-software-industry-highest-projected-earnings-grow",
                "accurate": true,
                "date": "2020-02-01T11:25:22Z"
            }
        ],
        "glaQ7dr3JeklSA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple says that it won't meet its Q2 guidance because of coronavirus impact",
                "content": "What you need to know   Apple has told investors that it won't meet its previous earnings guidance for Q2.  It made the predictions on January 28.  Since then the impact of coronavirus has worsened.   \nApple says the situation in China is still evolving. \n \nApple has issued a note to investors today, informing them that it won't meet the Q2 earnings guidance that was issued on January 28. It says that the current coronavirus situation is impacting it in two ways. \n  \nOur quarterly guidance issue",
                "url": "https://www.imore.com/apple-says-it-wont-meet-its-q2-earnings-guidance-because-coronavirus-impact",
                "accurate": null,
                "date": "2020-02-17T23:39:40Z"
            }
        ],
        "59Kxog3fymRQAA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Applegreen (LON:APGN) Shares Up 2.6%",
                "content": "Applegreen PLC (LON:APGN)’s share price shot up 2.6% during mid-day trading on Thursday . The company traded as high as GBX 467 ($6.14) and last traded at GBX 467 ($6.14), 34,472 shares were traded  during mid-day trading. An increase of 84% from the average session volume of 18,685 shares. The stock had previously closed at GBX 455 ($5.99). \n \nSeparately, Berenberg Bank lifted their target price on Applegreen from GBX 610 ($8.02) to GBX 630 ($8.29) and gave the company a “buy” rating in a resea",
                "url": "https://mayfieldrecorder.com/2020/02/13/applegreen-lonapgn-shares-up-2-6.html",
                "accurate": null,
                "date": "2020-02-14T00:36:33Z"
            }
        ],
        "DU3NmrDCQXvPew": [
            {
                "nobiasLeaning": "Sell",
                "title": "Earnings Preview: GCP Applied Technologies (GCP) Q4 Earnings Expected to Decline",
                "content": "Feb 19, 2020( Zacks Investment Research: http://www.zacks.com/ Delivered by Newstex)  GCP Applied Technologies (GCP) is expected to deliver a year-over-year decline in earnings on lower revenues when it reports results for the quarter ended December 2019. This widely-known consensus outlook gives a good sense of the company's earnings picture, but how the actual results compare to these estimates is a powerful factor that could impact its near-term stock price.The stock might move higher if thes",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7T-6MV1-JCMN-Y0S8-00000-00",
                "accurate": true,
                "date": "2020-02-19T22:44:23Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Semiconductor Systems to Aid Applied Materials (AMAT) Q1 Earnings",
                "content": "Want the latest recommendations from Zacks Investment Research? Today, you can download 7 Best Stocks for the Next 30 Days. Click to get this free report \n  \nItron, Inc. (ITRI): Free Stock Analysis Report \n  \nApplied Materials, Inc. (AMAT): Free Stock Analysis Report \n  \nBenefitfocus, Inc. (BNFT): Free Stock Analysis Report \n  \nAlteryx, Inc. (AYX): Free Stock Analysis Report \n  \nTo read this article on Zacks.com click here. \n  \nZacks Investment Research",
                "url": "http://www.zacks.com/stock/news/760219/semiconductor-systems-to-aid-applied-materials-amat-q1-earnings?cid=CS-ZC-FT-analyst_blog%7Cearnings_preview-760219",
                "accurate": null,
                "date": "2020-02-11T16:43:53Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Zacks Earnings Trends Highlights: Apple, Starbucks, Wynn Resorts and Royal Caribbean",
                "content": "Feb 20, 2020( Zacks Investment Research: http://www.zacks.com/ Delivered by Newstex) ; For Immediate ReleaseChicago, IL - February 20, 2020 - Zacks Director of Research Sheraz Mian says, 'Total S...00 earnings are now expected to be up +1.0% on +5.0% higher revenues. The virus impact notwithstanding, estimates have fallen less than other recent periods.'Q1 Estimates Holding Up Despite Virus ImpactNote: The following is an excerpt from this week's Earnings Trends[1]report. You can access the full",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y81-6061-F03R-N0X0-00000-00",
                "accurate": null,
                "date": "2020-02-20T22:40:55Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Hospitality REIT (APLE) Q4 FFO Lag Estimates",
                "content": "Feb 24, 2020( Zacks Investment Research: http://www.zacks.com/ Delivered by Newstex)  Apple Hospitality REIT (APLE) came out with quarterly funds from operations (FFO) of $0.32 per share, missing the Zacks Consensus Estimate of $0.33 per share. This compares to FFO of $0.36 per share a year ago. These figures are adjusted for non-recurring items.This quarterly report represents an FFO surprise of -3.03%. A quarter ago, it was expected that this hotel-owning real estate investment trust would pos",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y90-97G1-JCMN-Y3CC-00000-00",
                "accurate": true,
                "date": "2020-02-25T05:51:46Z"
            }
        ],
        "iNYjrad67Euh1Q": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT (NYSE:APLE) Hits New 1-Year Low Following Weak Earnings",
                "content": "Shares of Apple Hospitality REIT Inc (NYSE:APLE) reached a new 52-week low during mid-day trading on Monday after the company announced weaker than expected quarterly earnings. The company traded as low as $14.53 and last traded at $14.56, with a volume of 1072799 shares changing hands. The stock had previously closed at $15.09. \n \nThe real estate investment trust reported $0.11 earnings per share (EPS) for the quarter, missing the Zacks’ consensus estimate of $0.33 by ($0.22). The firm had reve",
                "url": "https://www.tickerreport.com/banking-finance/5103767/apple-hospitality-reit-nyseaple-hits-new-1-year-low-following-weak-earnings.html",
                "accurate": null,
                "date": "2020-02-26T11:22:00Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Zacks: Brokerages Expect Applied Materials, Inc. (NASDAQ:AMAT) Will Announce Earnings of $0.92 Per Share",
                "content": "Equities research analysts expect Applied Materials, Inc. (NASDAQ:AMAT) to report $0.92 earnings per share (EPS) for the current quarter, according to Zacks Investment Research . Five analysts have made estimates for Applied Materials’ earnings. The lowest EPS estimate is $0.91 and the highest is $0.93. Applied Materials posted earnings of $0.81 per share during the same quarter last year, which would indicate a positive year-over-year growth rate of 13.6%. The firm is scheduled to report its ne",
                "url": "https://www.tickerreport.com/banking-finance/4914813/zacks-brokerages-expect-applied-materials-inc-nasdaqamat-will-announce-earnings-of-0-92-per-share.html",
                "accurate": null,
                "date": "2020-01-01T07:21:08Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "FY2020 Earnings Estimate for Applied Materials, Inc. Issued By KeyCorp (NASDAQ:AMAT)",
                "content": "Applied Materials, Inc. (NASDAQ:AMAT) – Research analysts at  KeyCorp lifted their FY2020 EPS estimates for shares of Applied Materials  in a report released on  Wednesday, February 12th. KeyCorp analyst W. Twigg now anticipates that the manufacturing equipment provider will post earnings of $4.23 per share for the year, up from their previous forecast of $3.65. KeyCorp currently  has a “Overweight” rating and a $86.00 target price on the stock. KeyCorp also issued estimates for Applied Material",
                "url": "https://www.tickerreport.com/banking-finance/5057727/fy2020-earnings-estimate-for-applied-materials-inc-issued-by-keycorp-nasdaqamat.html",
                "accurate": true,
                "date": "2020-02-17T08:18:55Z"
            }
        ],
        "n0bA2bn1oNNjpA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Due to Coronavirus Outbreak in China Apple Revises its Q2 Revenue",
                "content": "Apple, the world's first trillion-dollar company, revises its Q2 profit expectations: Apple, the world's first trillion-dollar company in terms of market capitalization, has revised its expectations in quarter 2 of 2020. It is due to the deadly coronavirus that had killed as per official estimate until now more than 1886 people. Apple says that the slowdown is only temporary, and as usual, its primary objective is the health of its employees. \n\nOn August 2, 2018, when the Apple share was traded ",
                "url": "https://www.newsbricks.com/technology/due-to-coronavirus-outbreak-in-china-apple-revises-its-q2-revenue/08446",
                "accurate": null,
                "date": "2020-02-18T12:53:08Z"
            }
        ],
        "_E4RN1nMc2tWyg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Shares Drop After Virus Warning Rattles Tech Investors",
                "content": "(Bloomberg) -- Apple Inc.’s shares fell 4.1% in pre-market trading after the company said the fallout from the coronavirus will cause it to miss its sales targets this quarter, sending shockwaves across tech stocks globally.\n\nShares of Apple’s European suppliers fell in early trading, echoing an earlier decline in their Asian counterparts. Europe’s benchmark Stoxx Tech Index fell as much as 1.6% on Tuesday, with Dialog Semiconductor Plc down 6%, AMS AG dropping 5.1% and STMicroelectronics NV fal",
                "url": "https://finance.yahoo.com/news/apple-shares-drop-virus-warning-093151589.html",
                "accurate": true,
                "date": "2020-02-18T11:39:46Z"
            }
        ],
        "xXnlY-szWhEBlQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "B. Riley Weighs in on Applied Materials, Inc.’s Q1 2021 Earnings (NASDAQ:AMAT)",
                "content": "Applied Materials, Inc. (NASDAQ:AMAT) – Investment analysts at  B. Riley issued their Q1 2021 EPS estimates for shares of Applied Materials  in a research note issued on  Monday, February 10th. B. Riley analyst C. Ellis anticipates that the manufacturing equipment provider will post earnings per share of $0.96 for the quarter. B. Riley  has a “Buy” rating and a $74.00 price objective on the stock. B. Riley also issued estimates for Applied Materials’ Q2 2021 earnings at $1.07 EPS, Q3 2021 earnin",
                "url": "https://www.modernreaders.com/news/2020/02/14/b-riley-weighs-in-on-applied-materials-inc-s-q1-2021-earnings-nasdaqamat.html",
                "accurate": true,
                "date": "2020-02-14T08:18:44Z"
            }
        ],
        "Mk-XjP9GQkBAhQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "Equity Indices And Futures Decline On Revenue Warning By Apple",
                "content": "General Trend: \n  Asian Apple suppliers trade broadly lower (decliners include Taiwan Semi, AAC Technologies, Sunny Optical, Largan, Hon Hai)  Sectors moving lower in Japan include Electric Appliances (includes Apple’s suppliers), general weakness in tech shares weighs on Softbank  Shanghai property index drops over 1% as PBOC said to deny that it plans to ease property loan cap  Declining sectors in Australia include Energy and Consumer Discretionary, financials move higher  Australian corporat",
                "url": "https://www.actionforex.com/contributors/fundamental-analysis/272704-equity-indices-and-futures-decline-on-revenue-warning-by-apple/",
                "accurate": true,
                "date": "2020-02-18T06:59:18Z"
            }
        ],
        "pHceLqxjkCG5iA": [
            {
                "nobiasLeaning": "Buy",
                "title": "GoDaddy posts solid Q4 with Business Applications growth",
                "content": "GoDaddy posted solid fourth quarter results on Thursday, with its largest revenue gains in its business applications segment. \nFourth quarter net income was $61.1 million, or 34 cents per share. Total revenue was $780.4 million, up 12.2 percent year-over-year.\nAnalysts were expecting earnings of 31 cents on revenue of $777.18 million. \nFor the full year, net income was $138.4 million, or 76 cents per share, on revenue of $2.99 billion.\n\"GoDaddy continues to execute against its strategy - empower",
                "url": "https://www.zdnet.com/article/godaddy-posts-solid-q4-with-business-applications-growth/",
                "accurate": true,
                "date": "2020-02-14T00:09:38Z"
            }
        ],
        "lcIAOJHYIl7XlA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Xiaomi’s Q4 2019 YoY growth is astonishing – much faster than Apple",
                "content": "Rate this post The latest report by IDC shows that global smartphone shipments in the fourth quarter of 2019 fell 1.1% year-on-year. However, Xiaomi grew significantly against the trend, with a year-on-year increase of 31.1%. This is the largest increase in the top 5. IDC data shows that in Q4 2019, Apple ranks first with a 20% market share, an increase of 7.9% year-on-year. Xiaomi’s Q4 2019 YoY growth is astonishing with a 31% increase. Samsung and Huawei fell 1.2% and 7.1%, respectively. Xiaom",
                "url": "https://www.gizchina.com/2020/02/04/xiaomis-q4-2019-yoy-growth-is-astonishing-much-faster-than-apple/",
                "accurate": null,
                "date": "2020-02-04T16:30:22Z"
            }
        ],
        "B16bo3eVw39Blg": [
            {
                "nobiasLeaning": "Buy",
                "title": "Q2 2020 EPS Estimates for Apple Inc. Reduced by Piper Sandler (NASDAQ:AAPL)",
                "content": "Apple Inc. (NASDAQ:AAPL) – Equities research analysts at  Piper Sandler cut their Q2 2020 earnings per share estimates for shares of Apple  in a report released on  Tuesday, February 18th. Piper Sandler analyst M. Olson now anticipates that the iPhone maker will earn $2.77 per share for the quarter, down from their prior forecast of $3.01. Piper Sandler  has a “Overweight” rating and a $343.00 price target on the stock. Piper Sandler also issued estimates for Apple’s FY2020 earnings at $13.59 EP",
                "url": "https://www.modernreaders.com/news/2020/02/22/q2-2020-eps-estimates-for-apple-inc-reduced-by-piper-sandler-nasdaqaapl.html",
                "accurate": true,
                "date": "2020-02-22T07:39:22Z"
            }
        ],
        "GA4aFDAmi815PQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple announces that it will miss Q2 forecasted revenue due to the coronavirus",
                "content": "Apple on Monday announced that it will miss its forecasted revenue guidance for the second fiscal quarter of 2020 due to the coronavirus epidemic. The company had projected revenue for the quarter between $63 and $67 billion, and gross margin between 38 and 39 percent. Apple did not provide revised Q2 earnings estimates.\nIn a released statement, Apple stated that it is, “experiencing a slower return to normal conditions than we had anticipated. As a result, we do not expect to meet the revenue g",
                "url": "https://www.macworld.com/article/3527421/apple-announces-that-it-will-miss-q2-forecasted-revenue-due-to-the-coronavirus.html",
                "accurate": true,
                "date": "2020-02-18T00:58:29Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple announces that it will miss Q2 forecasted revenue due to the coronavirus",
                "content": "Supply and store closures in China have affected sales. Credit: Apple / IDG Apple on Monday announced that it will miss its forecasted revenue guidance for the second fiscal quarter of 2020 due to the coronavirus epidemic. The company had projected revenue for the quarter between $63 and $67 billion, and gross margin between 38 and 39 percent.\n\nIn a released statement, Apple stated that it is, “experiencing a slower return to normal conditions than we had anticipated. As a result, we do not expe",
                "url": "https://www.pcworld.idg.com.au/article/671118/apple-announces-it-will-miss-q2-forecasted-revenue-due-coronavirus/",
                "accurate": true,
                "date": "2020-02-18T01:57:06Z"
            }
        ],
        "bOoVcA2Jt8Seqg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Indian shares drop as Apples warning signals virus impact",
                "content": "BENGALURU, Feb 18 (Reuters) - Indian shares tracked Asian peers lower on Tuesday, as a revenue warning from tech giant Apple Inc signalled mounting financial fallout on businesses from the coronavirus epidemic in China. \n\nThe iPhone maker warned late Monday it was unlikely to meet a sales target set just three weeks ago amid lost production and weakening demand in China, which supplied 18% of the company’s revenue in the year-ago quarter, after the outbreak. \n\nThe rapidly spreading virus has kil",
                "url": "https://uk.reuters.com/article/india-stocks/indian-shares-drop-as-apples-warning-signals-virus-impact-idUKL4N2AI0XV",
                "accurate": null,
                "date": "2020-02-18T05:25:32Z"
            }
        ],
        "RnIl2RTIumwOmQ": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Says It Will Miss Q1 2020 Revenue Target Due to Coronavirus",
                "content": "Apple has updated its financial guidance for the March quarter and announced that it will be missing its revenue estimates for the time period due to the Coronavirus outbreak. The company had announced its financial results for Q4 2019 on January 28 and provided its estimated revenue target for Q1 2020. The company had expected to generate revenue of $85.5 billion and $89.5 billion. However, the Coronavirus outbreak and the extended shutdown in China caused by the virus has affected Apple’s sale",
                "url": "http://www.iphonehacks.com/2020/02/apple-miss-q1-2020-revenue-target-coronavirus.html",
                "accurate": null,
                "date": "2020-02-18T03:04:21Z"
            }
        ],
        "fAuAz5MYg8xrMQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "Saudi Aramco announces IPO, UAE nationals can apply",
                "content": "(Reuters)\n\nSaudi Arabia's oil giant Aramco on Sunday announced its plan to launch an IPO and list on the Kingdom's main Tadawul bourse.\n\nAramco said the IPO would be split into two tranches - one each for institutional and individual investors. The Saudi market regulator has issued an exemption for non-resident institutional foreign investors to subscribe the IPO. While Saudi nationals would be eligible to receive bonus shares.\n\nDevesh Mamtani, president of investment and advisory services at Ce",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4J-XYJ1-F11P-X3HR-00000-00",
                "accurate": true,
                "date": "2020-02-04T21:24:33Z"
            }
        ],
        "3_0obq4s3K0i0w": [
            {
                "nobiasLeaning": "Buy",
                "title": "Xiaomi Has A Faster Growth Rate In Q4 2019 Than Apple",
                "content": "Rate this post On February 4, IDC released its latest report for the global smartphone shipments in the fourth quarter of 2019. According to it, the shipment fell by 1.1% year-on-year. However, Xiaomi has grown significantly against the trend, with a year-on-year increase of 31.1%. This is the largest increase in the previous TOP5. Also Read: Global Smartphone Shipments Increased By 1% YoY In The Third Quarter IDC data show that in the fourth quarter of 2019, Apple ranked first with a 20% market",
                "url": "https://www.gizchina.com/2020/02/04/xiaomi-has-a-faster-growth-rate-in-q4-2019-than-apple/",
                "accurate": true,
                "date": "2020-02-04T15:28:12Z"
            }
        ],
        "SZZCeuVhixcGJA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Buffett-owned Hathaway sold off 3.7 million Apple shares before latest earnings results announced",
                "content": "Much before the gloomy revenue guidance given out by tech giant Apple Inc, world-known investor Warren Buffett had dumped about $800 million worth of Apple stock in the last quarter, reports said citing SEC filings. \n\nBuffett's Berkshire Hathaway sold off 3.7 million shares during the between between October and December 2019 at a time when Apple's share price was rising at 30% from $219 to $294. It was a robust earnings quarter for the tech giant. \n\nEscaped Coronavirus outbreak impact \n\nWhile t",
                "url": "https://www.ibtimes.sg/buffett-owned-hathaway-sold-off-3-7-million-apple-shares-before-latest-earnings-results-announced-39642",
                "accurate": null,
                "date": "2020-02-19T05:50:31Z"
            }
        ],
        "OAOL1yQkkSMeJg": [
            {
                "nobiasLeaning": "Buy",
                "title": "Counterpoint: Samsung Lost To Apple In Q4 2019",
                "content": "Feb 03, 2020( Android Headlines: http://androidheadlines.com Delivered by Newstex)  Counterpoint has released[1] its latest report on the smartphone industry and it shows that Samsung's[2] crown might be in danger. Even though the South Korean giant remained the top vendor in 2019 as a whole, it lost to Apple in Q4. According to the firm's estimate, global shipments declined 1 percent year-over-year in 2019, which is an improvement over 2018's slump of 4 percent. Moreover, it seems like the mark",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4H-1171-JCMN-Y0KV-00000-00",
                "accurate": null,
                "date": "2020-02-04T06:37:10Z"
            }
        ],
        "4GoC7yCzU9-gRA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Bitcoin Daily: Binance Applies For Singapore Crypto License; CFTC Files Charges In Digital Ponzi Scheme",
                "content": "Posted by: in Bitcoin News Wire  1 min ago  \n  \nDefendants Breonna Clark of Denver, Colorado and Venture Capital Investments Ltd are charged with soliciting American citizens to trade foreign currency and Bitcoin using a communal digital pool. By … \nRead Full Story \n   Bitcoin News Editor \nThe ForexTV Bitcoin editor automatically searches and aggregates stories related to bitcoin and other crypto currencies. \n Latest posts by Bitcoin News Editor ( see all )",
                "url": "https://forextv.com/bitcoin-news/bitcoin-daily-binance-applies-for-singapore-crypto-license-cftc-files-charges-in-digital-ponzi-scheme/",
                "accurate": null,
                "date": "2020-02-17T05:35:03Z"
            }
        ],
        "dKV2H86yoED_GA": [
            {
                "nobiasLeaning": "Sell",
                "title": "6+ Key Takeaways from Apple’s Q1 2020 Earnings Call",
                "content": "Apple on Tuesday announced financial results for the first fiscal quarter of 2020, which lines up with the busy holiday shopping season (Q4 2019). In a nutshell, Apple did better than anyone expected. The company’s Q1 2020 quarter was its best ever, and many of Apple’s product categories set new records. Continue reading to learn […]\nRead More...",
                "url": "https://www.idropnews.com/news/6-key-takeaways-from-apples-q1-2020-earnings-call/128193/",
                "accurate": true,
                "date": "2020-02-04T17:11:26Z"
            }
        ],
        "oALYWk3Qs5MlQg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Kuo: Ultrawide band chip production ramp predicts Q3 2020 launch for Apple AirTags",
                "content": "As shared in a research note, TF Securities Ming-Chi Kuo expects Apple system-in-package partners to ramp up production of the ultra-wide band ‘AirTags’ in the second or third quarter of this year. \n \nKuo says that the supply chain will be producing tens of millions of units by the end of the year. Although not said explicitly, it suggests that Apple’s Tile-like trackers (referenced in code as ‘AirTags’) will be released this year. \n \n \n \nAssuming a fall release date given the reported productio",
                "url": "https://www.iphonefirmware.com/kuo-ultrawide-band-chip-production-ramp-predicts-q3-2020-launch-for-apple-airtags/",
                "accurate": true,
                "date": "2020-02-18T19:50:53Z"
            }
        ],
        "DmU_sH7lQA2FfA": [
            {
                "nobiasLeaning": "Sell",
                "title": "GCP Applied Technologies (NYSE:GCP) Updates FY 2020\nPre-Market Earnings Guidance",
                "content": "GCP Applied Technologies (NYSE:GCP) issued an update on its FY 2020\n\nPre-Market earnings guidance on Wednesday morning. The company provided earnings per share guidance of 0.79-0.95 for the period, compared to the Thomson Reuters consensus earnings per share estimate of $0.93. The company issued revenue guidance of $1.034-1.034 billion, compared to the consensus revenue estimate of $1.04 billion.GCP Applied Technologies also updated its FY20 guidance to $0.79-0.95 EPS.\n\nShares of GCP traded up $",
                "url": "https://www.thestockobserver.com/2020/02/27/gcp-applied-technologies-nysegcp-updates-fy-2020pre-market-earnings-guidance.html",
                "accurate": true,
                "date": "2020-02-27T19:05:22Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Brokerages Expect Applied Optoelectronics Inc (NASDAQ:AAOI) to Post -$0.23 Earnings Per Share",
                "content": "Analysts predict that Applied Optoelectronics Inc (NASDAQ:AAOI) will post earnings per share (EPS) of ($0.23) for the current quarter, Zacks Investment Research reports. Five analysts have provided estimates for Applied Optoelectronics’ earnings, with estimates ranging from ($0.25) to ($0.21). Applied Optoelectronics reported earnings of ($0.02) per share during the same quarter last year, which indicates a negative year-over-year growth rate of 1,050%. The business is expected to report its nex",
                "url": "https://www.thestockobserver.com/2020/02/08/brokerages-expect-applied-optoelectronics-inc-nasdaqaaoi-to-post-0-23-earnings-per-share.html",
                "accurate": null,
                "date": "2020-02-09T02:21:40Z"
            }
        ],
        "ErXglaDjS9ynXA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple (NASDAQ:AAPL) Price Target Increased to $365.00 by Analysts at Evercore ISI",
                "content": "Apple (NASDAQ:AAPL) had its price objective increased by stock analysts at Evercore ISI  from $360.00 to $365.00 in a note issued to investors on Wednesday, January 29th, BenzingaRatingsTable reports. The firm presently has an “outperform” rating on the iPhone maker’s stock. Evercore ISI’s price target would indicate a potential upside of 12.24% from the stock’s current price. \n \nSeveral other research analysts have also commented on the company. Tigress Financial  reiterated a “buy” rating on s",
                "url": "https://mayfieldrecorder.com/2020/02/06/apple-nasdaqaapl-price-target-raised-to-365-00-at-evercore-isi.html",
                "accurate": null,
                "date": "2020-02-07T03:51:17Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Inc. (NASDAQ:AAPL) to Issue $0.77 Quarterly Dividend",
                "content": "Apple Inc. (NASDAQ:AAPL) declared a quarterly dividend on Tuesday, January 28th, RTT News reports. Stockholders of record on Monday, February 10th will be paid a dividend of 0.77 per share by the iPhone maker on Thursday, February 13th. This represents a $3.08 dividend on an annualized basis and a dividend yield of 0.94%. The ex-dividend date is Friday, February 7th. \n \nApple has raised its dividend by an average of 7.8% annually over the last three years and has increased its dividend every yea",
                "url": "https://mayfieldrecorder.com/2020/02/13/apple-inc-nasdaqaapl-declares-0-77-quarterly-dividend.html",
                "accurate": null,
                "date": "2020-02-13T13:42:40Z"
            }
        ],
        "83sX0OZrG2hFtw": [
            {
                "nobiasLeaning": "Sell",
                "title": "Coronavirus: Apple warns of iPhone shortage because of deadly virus; Company says earnings will also be affected by drop in demand in China",
                "content": "Apple says it will not hit its quarterly earnings target after the coronavirus outbreak led to a cut in production of iPhones and a fall in demand in China.\n\nThe company, based in California, said all of its production plants in China had reopened but were only gradually returning to full production. None of its iPhone plants are in Hubei province, the centre of the deadly virus outbreak.\n\nApple had said in late January that it expected its second-quarter earning to be between $63 billion and $6",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7C-GXP1-JCJY-G02T-00000-00",
                "accurate": null,
                "date": "2020-02-18T02:33:27Z"
            }
        ],
        "Lft24q2orXMf1Q": [
            {
                "nobiasLeaning": "Sell",
                "title": "Nomura Raises Applied Materials (NASDAQ:AMAT) Price Target to $77.00",
                "content": "Applied Materials (NASDAQ:AMAT) had its price objective hoisted by Nomura from $75.00 to $77.00 in a research report released on Thursday morning, BenzingaRatingsTable reports. Nomura currently has a buy rating on the manufacturing equipment provider’s stock. \n \nSeveral other equities research analysts have also recently issued reports on AMAT. Cowen raised their price objective on Applied Materials from $75.00 to $78.00 and gave the stock an outperform rating in a report on Thursday. DA Davidso",
                "url": "https://zolmax.com/investing/nomura-raises-applied-materials-nasdaqamat-price-target-to-77-00/3654559.html",
                "accurate": true,
                "date": "2020-02-17T10:16:57Z"
            }
        ],
        "FE1mBVZiX7k_Xw": [
            {
                "nobiasLeaning": "Buy",
                "title": "Brokers Set Expectations for Apple Hospitality REIT Inc’s Q1 2020 Earnings (NYSE:APLE)",
                "content": "Apple Hospitality REIT Inc (NYSE:APLE) – Equities research analysts at B. Riley reduced their Q1 2020 earnings per share estimates for shares of Apple Hospitality REIT in a research report issued on Thursday, February 27th. B. Riley analyst B. Maher now anticipates that the real estate investment trust will earn $0.37 per share for the quarter, down from their previous estimate of $0.38. B. Riley currently has a “Buy” rating and a $16.00 target price on the stock. B. Riley also issued estimates ",
                "url": "https://www.thelincolnianonline.com/2020/02/28/brokers-set-expectations-for-apple-hospitality-reit-incs-q1-2020-earnings-nyseaple.html",
                "accurate": null,
                "date": "2020-02-28T11:45:24Z"
            }
        ],
        "rGsNmv2hiMCyBA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Q2 2020 Earnings Estimate for Applied Materials, Inc. Issued By B. Riley (NASDAQ:AMAT)",
                "content": "Applied Materials, Inc. (NASDAQ:AMAT) – Equities research analysts at  B. Riley boosted their Q2 2020 earnings estimates for Applied Materials  in a note issued to investors on  Thursday, February 13th. B. Riley analyst C. Ellis now anticipates that the manufacturing equipment provider will post earnings of $1.04 per share for the quarter, up from their prior forecast of $0.96. B. Riley  has a “Buy” rating and a $74.00 price target on the stock. B. Riley also issued estimates for Applied Materia",
                "url": "https://www.tickerreport.com/banking-finance/5051679/q2-2020-earnings-estimate-for-applied-materials-inc-issued-by-b-riley-nasdaqamat.html",
                "accurate": true,
                "date": "2020-02-15T08:16:10Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple (NASDAQ:AAPL) Given a $358.00 Price Target by Royal Bank of Canada Analysts",
                "content": "Royal Bank of Canada set a $358.00 price objective on Apple (NASDAQ:AAPL) in a research note issued to investors on Tuesday, Borsen Zeitung reports. The firm currently has a buy rating on the iPhone maker’s stock. \n \nA number of other equities analysts also recently commented on the stock. China Renaissance Securities began coverage on shares of Apple in a report on Monday, December 9th. They issued a buy rating and a $342.00 target price for the company. Maxim Group upgraded shares of Apple fro",
                "url": "https://www.tickerreport.com/banking-finance/5077506/apple-nasdaqaapl-given-a-358-00-price-target-by-royal-bank-of-canada-analysts.html",
                "accurate": true,
                "date": "2020-02-22T09:03:02Z"
            }
        ],
        "6eZV5GOyajk--w": [
            {
                "nobiasLeaning": "Buy",
                "title": "Fred Hickey on Apple's recent earnings release",
                "content": "Apple handily bested estimates with better than expected iPhone sales but weaker services growth ($400 million less than expected).  On the conference call CEO Tim Cook was asked which services segments caused the shortfall.  He avoided answering the analyst's question.  It's important because Apple's services businesses are supposed to pick up the slack from the no growth (and highly competitive) smartphone market.\n~ Fred Hickey, The High-Tech Strategist, February 4, 2020",
                "url": "http://notableandquotable.blogspot.com/2020/02/fred-hickey-on-apples-recent-earnings.html",
                "accurate": null,
                "date": "2020-02-13T19:52:18Z"
            }
        ],
        "ZL1x9N-V7lso2Q": [
            {
                "nobiasLeaning": "Buy",
                "title": "Bank of America Increases Apple (NASDAQ:AAPL) Price Target to $350.00",
                "content": "Apple (NASDAQ:AAPL) had its target price increased by stock analysts at Bank of America from $340.00 to $350.00 in a note issued to investors on Wednesday, January 29th. The brokerage currently has a “buy” rating on the iPhone maker’s stock. Bank of America ‘s price target points to a potential upside of 9.25% from the company’s current price. \n \nSeveral other equities analysts have also recently issued reports on AAPL. UBS Group  set a $355.00 price target on Apple and gave the company a “buy” ",
                "url": "https://mayfieldrecorder.com/2020/02/05/bank-of-america-boosts-apple-nasdaqaapl-price-target-to-350-00.html",
                "accurate": true,
                "date": "2020-02-05T18:51:54Z"
            }
        ],
        "mv7jACkLMe5kUw": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple's coronavirus warning was a foreshock for earnings. But investors shouldn't freak out just yet",
                "content": "Eastern Wash. farmer invites Bloomberg to her farm after edited clip goes viral 'You’re not robbing s***': Jack In The Box cashier ignores robber’s commands, Yakima police say Woman charged with raping child on camera says ex-boyfriend blackmailed her 'No Camping' signs appear across downtown Spokane 'Molest Me Mondays': The disturbing game Shaw Middle School parents were not notified about South Hill shooting suspect ordered to surrender gun, released from jail February acting like it's already",
                "url": "https://www.kxly.com/i/apples-coronavirus-warning-was-a-foreshock-for-earnings-but-investors-shouldnt-freak-out-just-yet/",
                "accurate": null,
                "date": "2020-02-19T18:34:09Z"
            }
        ],
        "iXqFYpeWzRQIwA": [
            {
                "nobiasLeaning": "Sell",
                "title": "Dow Jones Futures: Stock Market Rally Isn't 'Different This Time'; Alibaba, Nvidia Lead Key Earnings; Apple, Tesla In Focus",
                "content": "https://www.investors.com/wp-content/uploads/2019/06/Stock-ComputerChip-Electric01-adobe.jpg\n\nDow Jones futures were little changed Sunday night, along with S&P 500 futures and Nasdaq futures. The stock market rally showed surprising strength last week, but it isn't unprecedented. New coronavirus cases are trending lower, with Apple iPhone maker Foxconn and the Tesla Shanghai plant set to resume production. Alibaba stock, Nvidia stock, Dexcom stock, Shopify stock and Chegg stock among the most i",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y5T-23S1-DYTD-94YD-00000-00",
                "accurate": null,
                "date": "2020-02-10T07:17:04Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Dow Jones Futures Plunge As Coronavirus Stock Market Correction Intensifies; Tesla, Apple, Beyond Meat Notable Losers",
                "content": "Dow Jones futures plunged Friday, along with S&P 500 futures and Nasdaq futures, tumbling to session lows. The coronavirus stock market correction intensified Thursday, with the Dow Jones and other major indexes all falling more than 4%. The U.S. is monitoring thousands of people in California for possible Covid-19 infections, while coronavirus cases continued to spread.\n\nApple stock, Amazon.com (AMZN), Microsoft (MSFT), Nvidia (NVDA) and Tesla (TSLA) were among the big-cap losers Thursday. And ",
                "url": "https://www.investors.com/market-trend/stock-market-today/dow-jones-futures-coronavirus-stock-market-correction-tesla-apple-beyond-meat/",
                "accurate": true,
                "date": "2020-02-28T14:26:29Z"
            },
            {
                "nobiasLeaning": "Buy",
                "title": "Dow Jones Futures: AMD Ignores Apple-Led Retreat; Enphase, SolarEdge, Amedisys, 10X Genomics, Palomar Are Key Movers",
                "content": "https://www.investors.com/wp-content/uploads/2017/10/stock-eclipse-solar-shutter.jpg\n\nDow Jones futures rose modestly late Tuesday, along with S&P 500 futures and Nasdaq futures. The stock market rally held up well Tuesday despite an Apple revenue warning on the coronavirus. Enphase Energy, Amedisys and 2019 IPO stocks 10X Genomics and Palomar Holdings reported earnings.\n\nEnphase stock rose overnight, along with SolarEdge Technologies, which reports late Wednesday. Amedisys stock, 10X Genomics s",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7P-SSF1-JCBB-K4PJ-00000-00",
                "accurate": null,
                "date": "2020-02-19T07:20:33Z"
            }
        ],
        "cThUGeHEvXvSMA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Inc. (NASDAQ:AAPL) Forecasted to Post Q2 2020 Earnings of $3.02 Per Share",
                "content": "Apple Inc. (NASDAQ:AAPL) – Investment analysts at  Jefferies Financial Group raised their Q2 2020 earnings estimates for Apple  in a note issued to investors on  Wednesday, February 5th. Jefferies Financial Group analyst K. Mcnealy now forecasts that the iPhone maker will post earnings of $3.02 per share for the quarter, up from their prior forecast of $3.00. Jefferies Financial Group  has a “Buy” rating and a $350.00 price objective on the stock. Jefferies Financial Group also issued estimates ",
                "url": "https://www.modernreaders.com/news/2020/02/12/apple-inc-nasdaqaapl-forecasted-to-post-q2-2020-earnings-of-3-02-per-share.html",
                "accurate": null,
                "date": "2020-02-12T07:34:37Z"
            }
        ],
        "n3jIofa6_qhHGg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Megvii plans to refile as HK IPO application expires",
                "content": "Artificial intelligence (AI) company Megvii Technology’s IPO prospectus expired on Tuesday. But despite delaying the deal, the firm intends to resubmit a listing application, according to a source familiar with the matter.    The Chinese issuer, known best for the Face++ online facial recognition technology,  submitted a draft application  with the Hong Kong Stock Exchange (HKEX) on August 25, 2019. Based on HKEX’s rules, Megvii is required to update the financial numbers in its IPO documents af",
                "url": "https://www.globalcapital.com/article/b1kj8zbmslnfm1/megvii-plans-to-refile-as-hk-ipo-application-expires",
                "accurate": true,
                "date": "2020-02-27T14:18:27Z"
            }
        ],
        "XF5_fTxIHxBdwA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple's profit will drop by almost 30% if China bans its products, Goldman Sachs estimates (AAPL)",
                "content": "CNBC\n\n•An all-out ban on Apple products in China could wipe out almost 30% of Apple's profits, Goldman Sachs analysts estimate.\n\n•The report comes as the market anticipates a further escalation of the ongoing US-China trade dispute.\n\n•Apple shares fell nearly 2% on Wednesday.\n\n•Watch Apple trade live.\n\nApple's profits would plunge by almost 30% if China enacts a total ban on the company's products, according to Goldman Sachs. The dollar amount would be a reduction in net income by over $15 billi",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5W5J-PDN1-DXY7-W008-00000-00",
                "accurate": null,
                "date": "2020-02-10T18:32:06Z"
            }
        ],
        "cx3Vj4BagKzyuw": [
            {
                "nobiasLeaning": "Sell",
                "title": "Roku gains as Apple TV+ and Disney+ launches drive Q4 revenue surge",
                "content": "Roku posted pre-market gains as the streaming platform added 4.6 million new customers over the fourth calendar quarter, thanks in part to the launches of Apple TV+ and Disney+. \n \nApple TV+ is available on the Apple TV app on iPhone, iPad, Apple TV, iPod touch, Mac, select Samsung smart TVs, Amazon Fire TV and Roku devices, as well as at tv.apple.com , for $4.99 per month with a seven-day free trial. The Apple TV app is or will be available on LG, Sony and VIZIO smart TVs later this year. For a",
                "url": "https://macdailynews.com/2020/02/14/roku-gains-as-apple-tv-and-disney-launches-drive-q4-revenue-surge/",
                "accurate": true,
                "date": "2020-02-14T14:34:37Z"
            }
        ],
        "Jc2mvhUoMiT35w": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple AirTags Tipped To Launch In Q3 2020, Kuo Says",
                "content": "KEY POINTSA noted analyst claims Apple will launch its Tile-like tracker later this yearThe new device is expected to enhance the iPhone's ability to locate lost itemsThe new tracker is also expected to improve Apple's AR offerings\n\nAn analyst claims that Apple will launch its Tile-like trackers within the second and third quarter of the year.\n\nCupertino tech giant Apple is expected to launch a slew of new products this year. These expected products include a new iPhone lineup, new MacBooks with",
                "url": "https://www.ibtimes.com/apple-airtags-tipped-launch-q3-2020-kuo-says-2924945",
                "accurate": true,
                "date": "2020-02-19T12:00:07Z"
            }
        ],
        "3k5fiK4J39sk4g": [
            {
                "nobiasLeaning": "Sell",
                "title": "Global Silicone Derivative Market Top Key players, Regions, Type and Application Outlook upto 2020 to 2025",
                "content": "in a report titled, \"Silicone Derivative Market - Global Industry Analysis, Size, Share, Growth, Trends, and Forecast 2020 - 2025\", offers a complete 360 degree overview of the market. The analysts of the report have provided several crucial factors such as trends, drivers, restraints, and opportunities which are likely to have a tremendous impact on the market.\n\nSome of the prominent players hoping to garner sizeable shares in the overall Silicone Derivative market are Shin-Etsu Chemical Co., L",
                "url": "https://www.openpr.com/news/1925225/global-silicone-derivative-market-top-key-players-regions",
                "accurate": true,
                "date": "2020-02-10T10:56:18Z"
            }
        ],
        "0DPiKuNIrrVmDw": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple Says Coronavirus Will Stunt Its Quarterly Earnings",
                "content": "People wear protective masks at an Apple Store in Shanghai, China, January 29, 2020. (Aly Song/Reuters) Apple said in a press release Monday that it will not meet its revenue projections for the quarter due to the coronavirus outbreak in China, signaling that its iPhone production and Chinese demand for its products were being impacted by the severity of the disease. “Work is starting to resume around the country, but we are experiencing a slower return to normal conditions than we had anticipat",
                "url": "https://www.nationalreview.com/news/apple-coronavirus-will-stunt-quarterly-earnings/",
                "accurate": null,
                "date": "2020-02-18T07:10:46Z"
            }
        ],
        "ylvjQBNvBg91dQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple issues rare earnings warning, says coronavirus will cut into Q2 revenue and iPhone sales",
                "content": "Confirming speculation that the coronavirus will have an adverse impact on Apple’s bottom line, the Cupertino-based company today issued a brief press release stating that it’s expecting a revenue shortfall this quarter on account of the virus. The announcement shouldn’t come as much of a surprise in light of reports of factories in China shutting down as health professionals are still actively seeking to contain the coronavirus and prevent it from spreading further. \n \nAs Apple notes, the coron",
                "url": "https://bgr.com/2020/02/17/coronavirus-apple-lowers-revenue-march-quarter/",
                "accurate": true,
                "date": "2020-02-17T21:37:00Z"
            }
        ],
        "fBU2SFq0aC-i2Q": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Admits Coronavirus Will Make Company Miss Earnings Guidance This Quarter",
                "content": "As the impact of 2019 nCov (COVID-19, novel coronavirus) starts to settle in tech supply chains, corporations, their management, data research firms and investors are now starting to establish baseline estimates about the expected impact ton revenues and other metrics of financial performance from the breakout. Companies including Apple Inc ( NASDAQ:AAPL ), Qualcomm Incorporated and NVIDIA Corporation have factored in coronavirus-related disruptions into their earnings forecast. \n \nFor Apple, it",
                "url": "https://wccftech.com/apple-coronavirus-guidance-q2-2020-miss/",
                "accurate": true,
                "date": "2020-02-17T21:45:48Z"
            }
        ],
        "0jCi4dMnDi2twA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Bank of America Boosts Apple (NASDAQ:AAPL) Price Target to $350.00",
                "content": "Apple (NASDAQ:AAPL) had its target price boosted by Bank of America from $340.00 to $350.00 in a research note published on Wednesday morning. They currently have a buy rating on the iPhone maker’s stock.\n\nSeveral other equities analysts have also recently commented on AAPL. DA Davidson boosted their price target on shares of Apple from $375.00 to $385.00 and gave the company a positive rating in a report on Wednesday. China Renaissance Securities assumed coverage on shares of Apple in a report ",
                "url": "https://www.thestockobserver.com/2020/02/02/bank-of-america-boosts-apple-nasdaqaapl-price-target-to-350-00.html",
                "accurate": null,
                "date": "2020-02-02T13:17:43Z"
            }
        ],
        "x9A3NHNrT8bX4Q": [
            {
                "nobiasLeaning": "Sell",
                "title": "Warren is selling APPLE… Walmart just posted its biggest earnings miss August 2015… Looks like the recession has already arrived…",
                "content": "Facebook0 Twitter Email RSS feed - Syndicate IWB Subscribe To Our Newsletter t.co/QUYe7hHXVb t.co/XmQKvms25p — HowlingWolves (@HaulingWolves) February 17, 2020 $AAPL at risk of breaking its uptrend.\nUnconfirmed at this stage. pic.twitter.com/XMFB7BDEXO — Sven Henrich (@NorthmanTrader) February 18, 2020 Coming in ~4% shy of estimates, Walmart just posted its biggest earnings miss August 2015, says @HumOnTheMarkets $WMT — Carl Quintanilla (@carlquintanilla) February 18, 2020 Walmart earnings and o",
                "url": "https://www.investmentwatchblog.com/warren-is-selling-apple-walmart-just-posted-its-biggest-earnings-miss-august-2015-looks-like-the-recession-has-already-arrived/",
                "accurate": null,
                "date": "2020-02-18T20:52:43Z"
            }
        ],
        "nNhrJcvO75EnLQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "Hong Kong stocks fall as Apple warns of coronavirus impact and HSBC misses 2019 earnings estimate",
                "content": "Shanghai Composite ekes out small gains as economic uncertainties mount about the coronavirus outbreak  Ping An Good Doctor, Ali Health buck trend in Hong Kong, on investor hopes lockdown will lead new users to stick with online health platforms\n\nHong Kong stocks fell as sentiment soured after US tech giant Apple warned the coronavirus outbreak will hurt its March quarter target and HSBC missed its 2019 earnings estimates. \n\nThe Hang Seng Index declined 1.5 per cent Tuesday to 27,530.20. Of its ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7J-TNP1-JC8V-11YJ-00000-00",
                "accurate": null,
                "date": "2020-02-18T22:02:03Z"
            }
        ],
        "AwZ5kT-fVpOf6g": [
            {
                "nobiasLeaning": "Buy",
                "title": "Kuo: Supply Chain to Ramp Up for Apple's Ultra Wideband Tags in Second to Third Quarter of 2020",
                "content": "Shanghai-based manufacturing company Universal Scientific Industrial will begin supplying the system-in-package for Apple's upcoming Ultra Wideband item tracking tags in the second to third quarter of 2020, with shipments to reach tens of millions of units by the end of the year, according to analyst Ming-Chi Kuo.\nIn a research note with TF International Securities, obtained by MacRumors, Kuo said Universal Scientific Industrial will be the primary supplier of the system-in-package for the tags,",
                "url": "http://macworldinfo.blogspot.com/2020/02/kuo-supply-chain-to-ramp-up-for-apples.html",
                "accurate": true,
                "date": "2020-02-18T18:04:59Z"
            }
        ],
        "Vh1e3Zp1SS8ukg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Kuo: Supply Chain to Ramp Up for Apple's Ultra Wideband Tags in Second to Third Quarter of 2020",
                "content": "Kuo: Supply Chain to Ramp Up for Apple's Ultra Wideband Tags in Second to Third Quarter of 2020 Tuesday February 18, 2020 6:28 am PST by Joe Rossignol Shanghai-based manufacturing company Universal Scientific Industrial will begin supplying the system-in-package for Apple's upcoming Ultra Wideband item tracking tags in the second to third quarter of 2020, with shipments to reach tens of millions of units by the end of the year, according to analyst Ming-Chi Kuo.\rIn a research note with TF Intern",
                "url": "https://www.macrumors.com/2020/02/18/kuo-apple-uwb-tags-sip-2q-to-3q-2020/",
                "accurate": true,
                "date": "2020-02-18T14:48:13Z"
            }
        ],
        "1Z2n-uEOKIDryQ": [
            {
                "nobiasLeaning": "Buy",
                "title": "Coronavirus May Negatively Affect Apple’s Q1 Shipping Forecast",
                "content": "Apple Products  ( Pixabay )   \nThere have been concerns that this could impact the production of various consumer goods with  news of Coronavirus  spreading around China and the world.  \n\nApple would be one of those possibly affected. Apple CEO Tim Cook tells its investors that their production might be impacted due to the use of suppliers from Wuhan.  \n\nALSO READ:  Real-time and Interactive Coronavirus Online Map Now Available to Track Global Cases \nWhy the decline? \nApple analyst Ming-Chi Kuo ",
                "url": "https://www.techtimes.com/articles/247163/20200203/coronavirus-may-negatively-affect-apple-s-q1-shipping-forecast.htm",
                "accurate": true,
                "date": "2020-02-03T11:00:53Z"
            }
        ],
        "kZcVhhfrkTbE5g": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple (NASDAQ:AAPL) Price Target Increased to $375.00 by Analysts at Citigroup",
                "content": "Apple (NASDAQ:AAPL) had its price target boosted by Citigroup from $300.00 to $375.00 in a research note released on Wednesday morning, The Fly reports. Citigroup currently has a buy rating on the iPhone maker’s stock. \n \nOther analysts have also issued reports about the stock. China Renaissance Securities assumed coverage on shares of Apple in a research report on Monday, December 9th. They issued a buy rating and a $342.00 price target on the stock. Cascend Securities raised their price target",
                "url": "https://www.com-unik.info/2020/02/01/apple-nasdaqaapl-price-target-increased-to-375-00-by-analysts-at-citigroup.html",
                "accurate": true,
                "date": "2020-02-01T12:49:51Z"
            }
        ],
        "pCs93GzNct0LFw": [
            {
                "nobiasLeaning": "Buy",
                "title": "Apple, Uniqlo coming to ShopBack, end Q1 2020",
                "content": "Malaysians love shopping. And they certainly love savings. As revealed by ShopBack today, Malaysians are getting smarter in online shopping, as they scour the internet for the best deals and also use cashback platforms like ShopBack for further savings. ShopBack Malaysia has seen a phenomenal 150 percent spike in user growth in 2019 compared to a year ago, with a 200 percent growth in sales enabled through the cashback platform. This trend of hyper-growth is expected to continue; ShopBack Malays",
                "url": "https://vernonchan.com/apple-uniqlo-shopback-malaysia-q1-2020/",
                "accurate": true,
                "date": "2020-02-17T12:06:39Z"
            }
        ],
        "G1WqRujBoiDJSg": [
            {
                "nobiasLeaning": "Sell",
                "title": "GoDaddy posts solid Q4 with Business Applications growth",
                "content": "LogMeIn and Talend also reported fourth quarter results, along with restructuring plans. \n \nGoDaddy posted solid fourth quarter results on Thursday, with its largest revenue gains in its business applications segment.  \n\nFourth quarter net income was $61.1 million, or 34 cents per share. Total revenue was $780.4 million, up 12.2 percent year-over-year. \n\nAnalysts were expecting earnings of 31 cents on revenue of $777.18 million.  \n\nFor the full year, net income was $138.4 million, or 76 cents pe",
                "url": "https://www.zdnet.com/article/godaddy-posts-solid-q4-with-business-applications-growth/#ftag=RSSbaffb68",
                "accurate": true,
                "date": "2020-02-13T22:56:29Z"
            }
        ],
        "VmiHq6CikhGbWQ": [
            {
                "nobiasLeaning": "Buy",
                "title": "This week’s top stories: iOS 14 rumors, Apple’s record Q1 earnings, wireless charging mat, more",
                "content": "In this week’s top stories: Ming-Chi Kuo details what to expect from Apple in 2020, AAPL reports record earnings, the new emoji coming later this year, iOS 14 rumors, and more. Read on for all of this week’s biggest news. A new report from Ming-Chi Kuo on Wednesday detailed what to expect from Apple during the first half of 2020. Kuo reiterates that we should expect the iPhone SE 2, new iPad Pros, and MacBooks with scissor switch keys. Most notably, however, Kuo says to expect a smaller wireless",
                "url": "https://9to5mac.com/2020/02/02/this-weeks-top-stories-ios-14-rumors-apples-record-q1-earnings-wireless-charging-mat-more/",
                "accurate": true,
                "date": "2020-02-02T17:58:57Z"
            }
        ],
        "iLL8TXPotePJwQ": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT (NYSE:APLE) Announces Quarterly Earnings Results, Misses Expectations By $0.22 EPS",
                "content": "Apple Hospitality REIT (NYSE:APLE) issued its quarterly earnings results on Monday. The real estate investment trust reported $0.11 earnings per share for the quarter, missing the Zacks’ consensus estimate of $0.33 by ($0.22), Fidelity Earnings reports. The firm had revenue of $289.97 million for the quarter, compared to the consensus estimate of $288.45 million. Apple Hospitality REIT had a return on equity of 5.13% and a net margin of 13.57%. \n\nNYSE:APLE opened at $13.73 on Wednesday. Apple Ho",
                "url": "https://www.thestockobserver.com/2020/02/26/apple-hospitality-reit-nyseaple-announces-quarterly-earnings-results-misses-expectations-by-0-22-eps.html",
                "accurate": true,
                "date": "2020-02-26T13:36:52Z"
            }
        ],
        "xoqfACZpimxfbw": [
            {
                "nobiasLeaning": "Sell",
                "title": "Forum post: RE: BQ24105-Q1: About FDK Recommend Charging Procedure for Back-Up Batteries In-Vehicle Applications",
                "content": "Part Number: BQ24105-Q1 \n\nHi TI-team \n \nMy customer have some question about FDK Recommend Charging Procedure for Back-Up Batteries In-Vehicle Applications \n \n\n \n\n \n1. There are three different charging procedures depending on the battery voltage. \n \nEven when not using an external MCU, does the BQ24105-Q1 decide which charging procedure to use by itself ? \n \n2.Please tell me the content of health check. \n \nIn addition, it says \"If customer need\", how do you set the presence or absence of a heal",
                "url": "http://e2e.ti.com/support/power-management/f/196/p/878189/3257883#3257883",
                "accurate": true,
                "date": "2020-02-17T02:28:07Z"
            }
        ],
        "snxcHY3kUhNL4A": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Hospitality REIT (APLE) to Release Earnings on Monday",
                "content": "Apple Hospitality REIT (NYSE:APLE) is scheduled to be releasing its earnings data after the market closes on Monday, February 24th. Analysts expect Apple Hospitality REIT to post earnings of $0.33 per share for the quarter. Parties interested in participating in the company’s conference call can do so using this link. \n\nNYSE:APLE opened at $15.09 on Friday. The company has a quick ratio of 0.38, a current ratio of 0.38 and a debt-to-equity ratio of 0.47. Apple Hospitality REIT has a fifty-two we",
                "url": "https://www.thelincolnianonline.com/2020/02/22/apple-hospitality-reit-aple-to-release-earnings-on-monday.html",
                "accurate": null,
                "date": "2020-02-22T06:10:56Z"
            }
        ],
        "oS_N5x9jbYqfcg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Inc. Forecasted to Earn Q2 2020 Earnings of $3.00 Per Share (NASDAQ:AAPL)",
                "content": "Apple Inc. (NASDAQ:AAPL) – Research analysts at  Jefferies Financial Group decreased their Q2 2020 earnings per share estimates for Apple  in a research report issued on  Wednesday, January 29th. Jefferies Financial Group analyst K. Mcnealy now expects that the iPhone maker will post earnings of $3.00 per share for the quarter, down from their previous estimate of $3.05. Jefferies Financial Group currently  has a “Buy” rating and a $350.00 target price on the stock. Jefferies Financial Group als",
                "url": "https://www.modernreaders.com/news/2020/02/02/apple-inc-forecasted-to-earn-q2-2020-earnings-of-3-00-per-share-nasdaqaapl.html",
                "accurate": true,
                "date": "2020-02-02T08:19:06Z"
            }
        ]
    }
}
```



# Kittens

## Get All Kittens

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get()
```

```shell
curl "http://example.com/api/kittens"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let kittens = api.kittens.get();
```

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Max",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

This endpoint retrieves all kittens.

### HTTP Request

`GET http://example.com/api/kittens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

## Get a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.get(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Max",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

## Delete a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.delete(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.delete(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -X DELETE
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.delete(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "deleted" : ":("
}
```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

