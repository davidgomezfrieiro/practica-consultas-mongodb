 1 - db.restaurants.find({cuisine: "American"})
 2 - db.restaurants.find({borough: "Queens"})
 3 - db.restaurants.find({name: "Cafe Espanol})
 4 - db.restaurants.find({name: /Cafe/})
 5 - db.restaurants.find({"address.building": "41})
 6 - db.restaurants.find({$or: [ {"address.building": "41"}, {"address.building": "66"} ]})
 -----------------------------
 7 - db.movies.find({"year": {$lt: 1917}})
 8 - db.movies.find({}, {title: 1, _id: 0})
 9 - db.movies.find({ year: { $lt: 1912 } }, { title: 1, _id: 0 });
 10 - db.movies.find({genres: {$all: [ "Short", "Romance", "Animation"]}})
 11 - db.movies.find({rated: {$exists: true}})
 12 - db.movies.find({rated: {$eq: "G",  $exists: true}})
 13 - db.movies.remove({"imdb.rating": {$lt: 5}})
