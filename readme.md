# nodejs and mongodb

- connect mongodb
- load static data and insert it to database
- fetch data : db.collection("collectionname").find()
- find & limit data : db.collection("collectionname").find(query, limit, ...)
- find one: db.collection('collectionname').findOne
- insert data : db.collection("collectionName").insertOne(newItem) || insertMany([arrayOfitem])
- update date : db.collection("collection_name").findOneAndReplace(itemId, newItem)
- remove item : db.collection("collectionName").deleteOne(itemId)
- [aggration] `https://www.mongodb.com/docs/manual/aggregation/`
