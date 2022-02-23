# Amazon-Data-Scrapper
It's a REST API build using node js and express to get product details,offers and even search products on amazon.

Usage

Base URL : https://ga-amazon-scrapper.herokuapp.com
For api key visit : https://www.scraperapi.com/ 

For this amazon scrapper to work you have to pass the api key as query
for example https://ga-amazon-scrapper.herokuapp.com/products/[productId]?apiKey=[here provide the api key]

EndPoints
1. /products/[productId]
It will fetch you information about the amazon product whose id is specified

2. /products/[productId]/reviews
It will fetch you the reviews of the amazon product whose id is specified

3. /products/[productId]/offers
It will fetch you the current offers on the amazon product whose id is specified(if there is any)

4. /search/[searchQuery]
It will fetch you the related products on amazon
