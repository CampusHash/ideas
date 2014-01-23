FB Meta
=========

_Difficulty_: __Easy__

Display information about a facebook page using open graph.

From [Campushash](http://graph.facebook.com/campushash) the following information can be accessed

``` {
   "about": "CampusHash is a platform that connects college campuses with the industry. We provide a smarter, better way to startups for hiring.",
   "category": "Company",
   "category_list": [
      {
         "id": "2200",
         "name": "Company"
      }
   ],
   "company_overview": "CampusHash connects college campuses across the country with developers from the industry, and startups. We provide a smarter, better way for companies to hire interns and new recruits through events like hackathons in colleges. ",
   "founded": "Sanket Saurav, Rohit Tirkey",
   "is_published": true,
   "location": {
      "street": "1352, 15th Cross, Kumaraswamy Layout, Stage 1",
      "city": "Bangalore",
      "state": "",
      "country": "India",
      "zip": "560078",
      "latitude": 12.9833,
      "longitude": 77.5833
   },
   "phone": "+91-9031318727",
   "products": "1. InternHacks\n2. SprintTalks\n3. Campus Affiliate Program",
   "talking_about_count": 29,
   "username": "CampusHash",
   "website": "http://www.campushash.com",
   "were_here_count": 0,
   "id": "509110849101172",
   "name": "CampusHash",
   "link": "http://www.facebook.com/CampusHash",
   "likes": 2059,
   "cover": {
      "cover_id": 653215141357408,
      "source": "http://m.ak.fbcdn.net/sphotos-g.ak/hphotos-ak-ash3/s720x720/1014186_653215141357408_1208269919_n.jpg",
      "offset_y": 0,
      "offset_x": 10
   }
}
```
Parse it to display information and fetch coverpic. Store search results in the database for future access.

## Implementation ##

* Backend: [Google App Engine with Python](https://developers.google.com/appengine/docs/python/gettingstartedpython27/introduction)

* Frontend: Vanilla/CH-strap