# Commands

- `brew services start mongodb-community@5.0`
- `mongosh`
- `use practicedb`
- `db`
- `db.zoo.insertOne({name: 'Cleo', species: 'jaguar', age: 12, hobbies: ['sleeping', 'eating', 'climbing']})`
- `show collections`
- `db.zoo.find()`
- `db.zoo.deleteOne({name: 'Cleo'})` - deletes whole object in collection
- `db.zoo.remove({})` - We can also empty the collection at once, instead of one document at a time. For example, to empty our pets collection, we would type: `db.zoo.remove({})`. Because the inner curly brackets are empty, Mongo will assume that we want everything in our pets collection to be removed.
- `db.zoo.drop()` - Additionally, to remove a collection all together, we would use `db.zoo.drop()`. After running that line in the shell, our pets collection will no longer exist at all.
- `db.dropDatabase()` - And to remove the test database, we will use this line of code: `db.dropDatabase()`.
