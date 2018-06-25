---
name: StockTwits
x-slug: stocktwits
description: StockTwits is a real-time social network for investors and traders. Download
  our app and visit StockTwits.com.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/944-stocktwits.jpg
x-kinRank: "8"
x-alexaRank: "6524"
tags: StockTwits
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocktwits/master/_listings/stocktwits/apis.md
specificationVersion: "0.14"
apis:
- name: Stocktwits Streams by Symbol
  x-api-slug: stocktwits
  description: Returns the most recent 30 messages for the specified symbol. Includes
    symbol object in response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/944-stocktwits.jpg
  humanURL: http://stocktwits.com
  baseURL: :////streams/symbol
  tags: ""
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocktwits/master/_listings/stocktwits/streamssymbol-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocktwits/master/_listings/stocktwits/streamssymbol-get-openapi.md
- name: Stocktwits
  x-api-slug: stocktwits
  description: StockTwits is a real-time social network for investors and traders.
    Download our app and visit StockTwits.com.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/944-stocktwits.jpg
  humanURL: http://stocktwits.com
  baseURL: :///
  tags: StockTwits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/stocktwits/master/_listings/stocktwits/openapi.md
x-common:
- type: x-authentication
  url: https://api.stocktwits.com/developers/docs/authentication
- type: x-base
  url: http://api.stocktwits.com
- type: x-blog
  url: http://blog.stocktwits.com
- type: x-blog-rss
  url: http://blog.stocktwits.com/feed/
- type: x-branding
  url: https://api.stocktwits.com/developers/docs/logos
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stocktwits
- type: x-crunchbase
  url: https://crunchbase.com/organization/stocktwits
- type: x-developer
  url: http://stocktwits.com/developers
- type: x-documentation
  url: https://api.stocktwits.com/developers/docs/api
- type: x-email
  url: privacy@stocktwits.com
- type: x-email
  url: parents@stocktwits.com
- type: x-email
  url: support@stocktwits.com
- type: x-email
  url: abuse@stocktwits.com
- type: x-embeddable
  url: https://api.stocktwits.com/developers/docs/stocktwits-for-websites
- type: x-getting-started
  url: https://api.stocktwits.com/developers/docs/start
- type: x-github
  url: https://github.com/stocktwits
- type: x-rate-limits
  url: https://api.stocktwits.com/developers/docs/rate_limiting
- type: x-status
  url: http://api-status.stocktwits.com/
- type: x-terms-of-service
  url: https://api.stocktwits.com/developers/api-terms
- type: x-twitter
  url: https://twitter.com/stocktwits
- type: x-website
  url: http://stocktwits.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---