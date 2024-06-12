### Insert

1. **insertOne( )** : to insert single data/document to a collection
	 ``` 
	db.collection_name.insertOne(
		{
			name: "Hisham",
			age: 20,
			DOB: "28-08-2003"
		}
	)
	 ```
2. **insertMany( )** : to insert multiple data/document to a collection
	 ``` 
	db.collection_name.insertMany([
		{
			name: "Hisham",
			age: 20,
			DOB: "28-08-2003"
		},
		{
			name: "Hanan",
			age: 16,
			DOB: "20-12-2007",
			class: "X"
		},
		{
			name: "Haniya",
			age: 11,
			DOB: "23-10-2012",
			hobby: "Drawing"
		}
	])
	 ```


## Read / Find

1. **find( )** : 
	 * Returns Cursor
	 ``` 
	/*outputs cursor of only matching documents*/
	db.collection_name.find({name: "Hisham"}) 
	 ```

2. **findOne( )** : 