<h1 align="center">Flipkart Scrapping</h1>

### what is this??

    This is a Python Scrapper for scrapping essential data from Flipkart website

## What can it Scrape?

* **[Scrap Flipkart](#scrap-flipkart)** 

## How to use this??

So simple!! Just go and type

```
pip install flipkart-scrapping
```
Bam!! You just installed a great scraping tool

## How to use in python??

    from flipkart_scrapping.FlipkartScrapping import fp_scrap

## Detailed documentation

### Scrap Mobile Specifications
This scraps data from [Flipkart Website](https://www.flipkart.com/)

    from flipkart_scrapping.FlipkartScrapping import fp_scrap
    scrap = fp_scrap()
    params = {"no_of_products":10, "max_comments":6}
    scrap.to_file("apple", "/home/rajesh/data.dat", params)


### What it will extract
* It will extract product details like name, price, overall rating, specs ratings, ratings and reviews

* The Scrapped data is stored in data.dat file where each record is in json format

Result data looks like this:
```
{
	"product": "APPLE iPhone 12 Mini",
	"price": "42999",
	"overall_rating": "4.6",
	"ratings_count": "31261",
	"reviews_count": "1874",
	"ratings": {
		"camera_rating": "4.6",
		"battery_rating": "3.9",
		"display_rating": "4.6",
		"value_for_money": "4.4"
	},
	"reviews": [{
		"review_rating": "5",
		"mini_review": "Awesome",
		"full_review": "Very nice product... i am fully satisfied thankyou to Flipkart for delivering me this wonderful product in safe and an affordable price",
		"review_date": "6 months ago"
	}, {
		"review_rating": "4",
		"mini_review": "Nice product",
		"full_review": "Superb nice phone mini compact But small problem without charger with the box is the problemOverall best phone but battery capacity is only 6hrs a day.",
		"review_date": "6 months ago"
	}, {
		"review_rating": "5",
		"mini_review": "Excellent",
		"full_review": "As I am iPhone user since 2010 and up till now using it.Almost a decade I haven\u2019t face any problem. One can trust blindly \u2764\ufe0f this time I purchase online with having doubts but  when I received my parcel just loved it.Flipkart maintained the trust. I went to the Apple store to check the originality and warranty and I satisfied and Happily...Thank you Flipkart",
		"review_date": "5 months ago"
	}, {
		"review_rating": "5",
		"mini_review": "Simply awesome",
		"full_review": "Awesome Purchase\u2026Firstly, thank you Flipkart for delivering fast and genuine product\u2026I\u2019ve been always fan of apple\u2019s products since my college days. Earlier I was using IPhone 7 and skipped other series of IPhone and jumped directly in 12 series. Just go for it without hesitation.",
		"review_date": "2 months ago"
	}, {
		"review_rating": "5",
		"mini_review": "Excellent Phone! Read My Review.",
		"full_review": "If you're in the market for a compact phone with probably the best cameras in a phone today, that does not sacrifice on performance or any of the flagship features then your decision must start and end with an iPhone. First of all Apple has created something that is a throwback to the best smartphones ever designed - the iphone 5 and 5S. While doing so Apple made sure that it did not compromise on power or performance. The 12 mini has all the features (ALL OF THEM!) of the bigger iPhone 12 - ...",
		"review_date": "6 months ago"
	}, {
		"review_rating": "4",
		"mini_review": "Nice product",
		"full_review": "As per my usage I think the battery is adequate as I don\u2019t often use my phone and at the end of the as per my usage the battery percentage remains at 40% but if you are a heavy user then you might feel the drain. The screen is small and typing might be an issue but after few minutes on you\u2019ll get used to it, the camera and the screen are awesome and the picture quality superb as per my liking. I would recommend a screen protector as minor scratches may occur, which might be caused while clean...",
		"review_date": "9 months ago"
	}]
}
  ```


## Credits
<p align="left">  
<b>Rajesh Patnala</b> &emsp; 
<a href="https://www.linkedin.com/in/rajeshpatnala/" target="blank"><img width=25 align="center" src="https://img.icons8.com/doodle/48/000000/linkedin--v2.png"/></a>  
</p>

<br/>

### Source Code Available in [Github](https://github.com/rajeshpatnala/flipkart-web-scrapping)
### For Other Projects in [Github](https://github.com/rajeshpatnala/)

## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/rajeshpatnala/flipkart-web-scrapping/issues) here by including your search query and the expected result

## Future Scope

* UI Implementation
* Optimize Code
