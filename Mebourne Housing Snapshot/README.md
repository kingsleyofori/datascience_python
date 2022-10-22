# Melbourne Housing Snapshot

### 1. Context
This is a snapshot of Melbourne's real estate dataset created by Tony Pino. The dataset used here was created in September 2017. 

This data was scraped from publicly available results posted every week from Domain.com.au. The data is believed to be cleaned by the author. The dataset includes Address, Type of Real estate, Suburb, Method of Selling, Rooms, Price, Real Estate Agent, Date of Sale and distance from C.B.D.

### 2. Queries
* What has been the pricing listing history across the years?
* What are the top 10 suburbds with highest listings?
* What are the geographical locations of the listings in Melbourne?
* What is the methods of exchange prevalent in the Melbourne market?
* Bedrooms available in the Melbourne market?
* Bathrooms available in the Melbourne markets?

### 3. Attibutes
* Rooms: Number of rooms

* Price: Price in dollars

* Method: 
    * S - property sold; 
    * SP - property sold prior; 
    * PI - property passed in; 
    * PN - sold prior not disclosed; 
    * SN - sold not disclosed; 
    * NB - no bid; 
    * VB - vendor bid; 
    * W - withdrawn prior to auction; 
    * SA - sold after auction; 
    * SS - sold after auction price not disclosed. 
    * N/A - price or highest bid not available.

* Type: 
    * br - bedroom(s); 
    * h - house,cottage,villa, semi,terrace; 
    * u - unit, duplex; 
    * t - townhouse; dev site - development site; 
    * o res - other residential.

* SellerG: Real Estate Agent

* Date: Date sold

* Distance: Distance from CBD

* Regionname: General Region (West, North West, North, North east …etc)

* Propertycount: Number of properties that exist in the suburb.

* Bedroom2 : Scraped # of Bedrooms (from different source)

* Bathroom: Number of Bathrooms

* Car: Number of carspots

* Landsize: Land Size

* BuildingArea: Building Size

* CouncilArea: Governing council for the area

### 4. Task
In the project, I used almost all the features to predict the pricing of properties in the Melbourne Market.
However, It was realised that using all the features isnt advisable and I will advise that you use fewer features.

### 5. Dataset
Get the dataset used for this project [HERE](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)
