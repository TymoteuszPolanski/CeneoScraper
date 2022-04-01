# CeneoScraper

## Struktura opinii w serwisie [Ceneo.pl](https://www.ceneo.pl/)

|Składowa opinii|Selektor|Nazwa zmiennej|Typ danych|
|opinia|div.js_product-review|||
|identyfikator opinii|div.js_product-review\["data-entry-id"\]|||
|autor opinii|span.user-post__author-name|||
|rekomendacja autora|span.user-post__author-name > em|||
|liczba gwiazdek|span.user-post__score-count|||
|treść opinii|div.user-post__text|||
|lista zalet|#body > div.no-banner > div > div > div.screening-wrapper.bordered-tabs.js_tab-control.tab-control.tab-control__show--reviews > div.page-tab-content.reviews.tab-control__item--reviews.theme__bg--primary.cf > div > div.js_product-reviews.js_reviews-hook.js_product-reviews-container > div:nth-child(4) > div > div.user-post__content > div.review-feature > div|||
|lista wad|#body > div.no-banner > div > div > div.screening-wrapper.bordered-tabs.js_tab-control.tab-control.tab-control__show--reviews > div.page-tab-content.reviews.tab-control__item--reviews.theme__bg--primary.cf > div > div.js_product-reviews.js_reviews-hook.js_product-reviews-container > div:nth-child(1) > div > div.user-post__content > div.review-feature > div:nth-child(2)|||
|dla ilu osób przydatna|button.vote-yes >span|||
|dla ilu osób nieprzydatna|button.vote-no >span|||
|data wystawienia opinii|span.user-post__published > time:nth-child(1)\["datetime"\]|||
|data zakupu produktu|span.user-post__published > time:nth-child(2)\["datetime"\]|||
