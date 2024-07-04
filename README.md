# Third-Party-API-Analysis

## Detailed Information of APIs

| Name of Service                               | Owner               | What Data You Can Get                                          | Licensing Terms                            | URL to the API                                                                                    | Suitable for Commercial Use | Notes                                               | More Info                                                                                                                                                                                                                                                                                                                                                  |
| --------------------------------------------- | ------------------- | -------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------- | --------------------------- | --------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Google PageSpeed Insights                     | Google              | Technical information about page speed and optimization        | Free                                       | [Google PageSpeed Insights API](https://developers.google.com/speed/docs/insights/v5/get-started) | Yes                         | Comprehensive performance insights.                 | Information about google api is [here](https://www.googleapis.com/pagespeedonline/v5/runPagespeed?url=https://kalibro.io&strategy=mobile)                                                                                                                                                                                                                  |
| WHOIS API                                     | WhoisXML API        | Domain registration information, expiration dates              | Freemium                                   | [WhoisXML API](https://www.whoisxmlapi.com/docs)                                                  | Yes                         | Useful for domain-related data.                     |
| OpenGraph API                                 | Facebook            | Metadata about web pages (title, description, image, etc.)     | Free                                       | [OpenGraph API](https://ogp.me/)                                                                  | Yes                         | Enhances social media sharing features.             | In this api, there should be tags and Metadata about web pages such as title, description, image, URL, and more. that are included in html like [this](https://developers.facebook.com/docs/sharing/webmasters)                                                                                                                                            |
| VirusTotal API                                | VirusTotal (Google) | Security audit information, file and URL analysis              | Free with limitations                      | [VirusTotal API](https://developers.virustotal.com/reference)                                     | No                          | Limited free tier, comprehensive security insights. | Security audit information, file and URL analysis for malware and other threats and more information is [here]()                                                                                                                                                                                                                                           |
| Twitter API                                   | Twitter             | Social media data (tweets, likes, retweets, etc.)              | Freemium                                   | [Twitter API](https://developer.twitter.com/en/docs/twitter-api)                                  | Yes                         | Access to Twitter data, rate limits apply.          | the pricing info is [here](https://developer.x.com/en/docs/twitter-api/getting-started/about-twitter-api)                                                                                                                                                                                                                                                  |
| Facebook Graph API                            | Facebook            | Social media data (posts, likes, comments, etc.)               | Freemium                                   | [Facebook Graph API](https://developers.facebook.com/docs/graph-api/)                             | Yes                         | Rich social media data, usage limits apply.         |
| Twinword Sentiment Analysis API               | Twinword            | Sentiment analysis of text and web pages                       | Could not test as Credit card was required | [Twinword Sentiment Analysis API](https://www.twinword.com/api/sentiment-analysis.php)            | Yes                         | Basic sentiment analysis, limitations on free tier. | the detailed information from aws marketplace [here](https://aws.amazon.com/marketplace/pp/prodview-szskhi4z2pohw?sr=0-1&ref_=beagle&applicationId=AWSMPContessa)                                                                                                                                                                                          |
| Social Mention API                            | Social Mention      | Social media monitoring, mentions, sentiment, keywords         | Free                                       | [Social Mention API](http://api.socialmention.com/)                                               | Yes                         | Simple social media monitoring.                     | Unclear api                                                                                                                                                                                                                                                                                                                                                |
| Mozscape API                                  | Moz                 | SEO metrics, link data, domain authority                       | Free with limitations                      | [Mozscape API](https://moz.com/products/api)                                                      | Yes                         | Comprehensive SEO data, limited free tier.          |
| Web of Trust (WOT) API                        | WOT                 | Reputation and safety scores of websites                       | Freemium                                   | [WOT API](https://www.mywot.com/en/developer)                                                     | Yes                         | Trust and safety metrics, rate limits apply.        | This Api can be used from the web page for free but to integrate this api, the pricing is [here](https://www.mywot.com/developers)                                                                                                                                                                                                                         |
| AYLIEN Text Analysis API                      | AYLIEN              | Sentiment analysis, entity recognition, text classification    | Free with limitations                      | [AYLIEN API](https://docs.aylien.com/textapi/)                                                    | Yes                         | Advanced text analysis, limited free tier.          | This api is for search for diffrent parameters and fetch the results of stories using the following [link](https://docs.aylien.com/newsapi/v6/getting-started/#api-endpoints) and takes ID and API key.                                                                                                                                                    |
| IBM Watson Natural Language Understanding API | IBM                 | Sentiment analysis, emotion detection, entity extraction       | Freemium                                   | [IBM Watson NLU API](https://cloud.ibm.com/apidocs/natural-language-understanding)                | Yes                         | Robust text analysis, usage costs may apply.        | This api could not be tested with endpoints as credit card information is required                                                                                                                                                                                                                                                                         |
| Lighthouse API                                | Google              | Performance metrics, accessibility, best practices, SEO scores | Free                                       | [Lighthouse API](https://developers.google.com/web/tools/lighthouse)                              | Yes                         | Integrated with PageSpeed Insights.                 | this api can be collectively used with Google Pagespeed with the same [link](https://www.googleapis.com/pagespeedonline/v5/runPagespeed?url=https://kalibro.io&strategy=mobile). This [Report](https://pagespeed.web.dev/analysis/https-kalibro-io/drs7c5v977?hl=en-US&form_factor=desktop) can be seen of kalibro.io generated from the chrome extension. |
| GTmetrix API                                  | GTmetrix            | Site performance, page load time, YSlow scores                 | Free with limitations                      | [GTmetrix API](https://gtmetrix.com/api/)                                                         | Yes                         | Detailed performance metrics, limited free tier.    | The pricing is [here](https://gtmetrix.com/pricing.html). For free Account, we can test from browser, in order to use APIs, there should be premium membership.                                                                                                                                                                                            |
| Screaming Frog SEO Spider API                 | Screaming Frog      | Sitemap generation, SEO audit information                      | Free with limitations                      | [Screaming Frog API](https://www.screamingfrog.co.uk/seo-spider/api/)                             | Yes                         | Comprehensive SEO audit tool, limited free tier.    | We get account once we purchase an account, the seo-spider is the tool that can be downloaded. The pricing is 199 £ / year. SEO-spider is easy to use and generates a meaningful report.                                                                                                                                                                   |
| Sitechecker API                               | Sitechecker         | Technical SEO audit, site performance, sitemap generation      | Freemium                                   | [Sitechecker API](https://sitechecker.pro/account/plans/)                                         | Yes                         | Useful for technical SEO insights.                  | This API generates a great auditing report for the given URL but unable to download /export without [pricing](https://sitechecker.pro/app/main/pricing).                                                                                                                                                                                                   |
| SEMrush API                                   | SEMrush             | Site audit, backlink audit, keyword research, site performance | Freemium                                   | [SEMrush API](https://www.semrush.com/api/)                                                       | Yes                         | Extensive SEO and marketing data, costs may apply.  | [Pricing](https://www.semrush.com/signup/get-free-trial/) This tool also generates good report about keywords, but forced to upgrade to guru / premium account to work further.                                                                                                                                                                            |

### Detailed Descriptions

1. **Google PageSpeed Insights API**

   - **Owner**: Google
   - **What Data You Can Get**: Technical information about page speed and optimization including performance scores, improvement opportunities, and diagnostics.
   - **Licensing Terms**: Free
   - **URL to the API**: [Google PageSpeed Insights API](https://developers.google.com/speed/docs/insights/v5/get-started)
   - **Usage**: Provides detailed performance metrics and suggestions for optimization.

2. **WHOIS API**

   - **Owner**: WhoisXML API
   - **What Data You Can Get**: Domain registration information, expiration dates.
   - **Licensing Terms**: Freemium
   - **URL to the API**: [WhoisXML API](https://www.whoisxmlapi.com/docs)
   - **Usage**: Useful for accessing domain-related data including ownership and expiration.

3. **OpenGraph API**

   - **Owner**: Facebook
   - **What Data You Can Get**: Metadata about web pages such as title, description, image, etc.
   - **Licensing Terms**: Free
   - **URL to the API**: [OpenGraph API](https://ogp.me/)
   - **Usage**: Enhances social media sharing by providing rich metadata.

4. **VirusTotal API**

   - **Owner**: VirusTotal (Google)
   - **What Data You Can Get**: Security audit information, file and URL analysis for malware and other threats.
   - **Licensing Terms**: Free with limitations
   - **URL to the API**: [VirusTotal API](https://developers.virustotal.com/reference)
   - **Usage**: Provides comprehensive security analysis for files and URLs, useful for detecting threats.

5. **Twitter API**

   - **Owner**: Twitter
   - **What Data You Can Get**: Social media data including tweets, likes, retweets, etc.
   - **Licensing Terms**: Freemium
   - **URL to the API**: [Twitter API](https://developer.twitter.com/en/docs/twitter-api)
   - **Usage**: Access to Twitter data for analytics and monitoring; rate limits apply.

6. **Facebook Graph API**

   - **Owner**: Facebook
   - **What Data You Can Get**: Social media data including posts, likes, comments, etc.
   - **Licensing Terms**: Freemium
   - **URL to the API**: [Facebook Graph API](https://developers.facebook.com/docs/graph-api/)
   - **Usage**: Provides rich social media data for analytics and engagement; usage limits apply.

7. **Twinword Sentiment Analysis API**

   - **Owner**: Twinword
   - **What Data You Can Get**: Sentiment analysis of text and web pages.
   - **Licensing Terms**: Free with limitations
   - **URL to the API**: [Twinword Sentiment Analysis API](https://www.twinword.com/api/sentiment-analysis.php)
   - **Usage**: Basic sentiment analysis useful for understanding user feedback.

8. **Social Mention API**

   - **Owner**: Social Mention
   - **What Data You Can Get**: Social media monitoring, mentions, sentiment, keywords.
   - **Licensing Terms**: Free
   - **URL to the API**: [Social Mention API](http://api.socialmention.com/)
   - **Usage**: Simple social media monitoring and sentiment analysis.

9. **Mozscape API**

   - **Owner**: Moz
   - **What Data You Can Get**: SEO metrics, link data, domain authority.
   - **Licensing Terms**: Free with limitations
   - **URL to the API**: [Mozscape API](https://moz.com/products/api)
   - **Usage**: Provides comprehensive SEO data for improving website performance.

10. **Web of Trust (WOT) API**

    - **Owner**: WOT
    - **What Data You Can Get**: Reputation and safety scores of websites.
    - **Licensing Terms**: Freemium
    - **URL to the API**: [WOT API](https://www.mywot.com/en/developer)
    - **Usage**: Useful for assessing the trust and safety of websites.

11. **AYLIEN Text Analysis API**

    - **Owner**: AYLIEN
    - **What Data You Can Get**: Sentiment analysis, entity recognition, text classification.
    - **Licensing Terms**: Free with limitations
    - **URL to the API**: [AYLIEN API](https://docs.aylien.com/textapi/)
    - **Usage**: Advanced text analysis capabilities for various applications.

12. **IBM Watson Natural Language Understanding API**

    - **Owner**: IBM
    - **What Data You Can Get**: Sentiment analysis, emotion detection, entity extraction.
    - **Licensing Terms**: Freemium
    - **URL to the API**: [IBM Watson NLU API](https://cloud.ibm.com/apidocs/natural-language-understanding)
    - **Usage**: Provides robust text analysis; usage costs may apply.

13. **Lighthouse API**

    - **Owner**: Google
    - **What Data You Can Get**: Performance metrics, accessibility, best practices, SEO scores.
    - **Licensing Terms**: Free
    - **URL to the API**: [Lighthouse API](https://developers.google.com/web/tools/lighthouse)
    - **Usage**: Integrated with Google PageSpeed Insights for detailed web performance analysis.

14. **GTmetrix API**

    - **Owner**: GTmetrix
    - **What Data You Can Get**: Site performance, page load time, YSlow scores.
    - **Licensing Terms**: Free with limitations
    - **URL to the API**: [GTmetrix API](https://gtmetrix.com/api/)
    - **Usage**: Detailed performance metrics; limited free tier.

15. **Screaming Frog SEO Spider API**

    - **Owner**: Screaming Frog
    - **What Data You Can Get**: Sitemap generation, SEO audit information.
    - **Licensing Terms**: Free with limitations
    - **URL to the API**: [Screaming Frog API](https://www.screamingfrog.co.uk/seo-spider/api/)
    - **Usage**: Comprehensive SEO audit tool; limited free tier.

16. **Sitechecker API**

    - **Owner**: Sitechecker
    - **What Data You Can Get**: Technical SEO audit, site performance, sitemap generation.
    - **Licensing Terms**: Freemium
    - **URL to the API**: [Sitechecker API](https://sitechecker.pro/app/)
    - **Usage**: Useful for technical SEO insights.

17. **SEMrush API**
    - **Owner**: SEMrush
    - **What Data You Can Get**: Site audit, backlink audit, keyword research, site performance.
    - **Licensing Terms**: Freemium
    - **URL to the API**: [SEMrush API](https://www.semrush.com/api/)
    - **Usage**: Extensive SEO and marketing data; costs may apply.
