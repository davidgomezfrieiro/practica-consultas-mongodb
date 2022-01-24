 1 - db.restaurants.find({cuisine: "American"})
 2 - db.restaurants.find({borough: "Queens"})
 3 - db.restaurants.find({name: "Cafe Espanol})
 4 - db.restaurants.find({name: /Cafe/})
 5 - db.restaurants.find({"address.building": "41})
 6 - db.restaurants.find({$or: [ {"address.building": "41"}, {"address.building": "66"} ]})
 -----------------------------
 7 - db.movies.find({"year": {$lt: 1927}})
 8 - 
 9 - 
 10 - db.movies.find({genres: {$all: [ "Short", "Romance", "Animation"]}})
