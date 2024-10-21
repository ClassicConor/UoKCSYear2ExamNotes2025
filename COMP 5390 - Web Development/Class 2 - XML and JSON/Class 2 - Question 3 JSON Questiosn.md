# Web Development - Class 2 - Question 3: JSON

## Read the specification for the JSON format at [www.json.org](www.json.org). Which of the followings are not valid JSON documents? Explain why.

```json
a) "Hello"
b) Hello
c) 35
d) true
e) Null
f) ["Hello"]
g) {name: "Smith"}
h) ["age", 20]
i) {"age": 20}
j) ["Hello": "world"]
k) {"Hello", "world"}
l) {"Hello": ["World", "!"]}
m) ["Hello": { "name": "Smith"}, {"age": 20}]
n) ["Hello", { "name": "Smith"}, {"age": 20}]
o) {0: {name: "Smith"}}
```

List which aren't valid for JSON documents:

- b (You need to include the item within quotation marks)
- e (Null needs to be lower case)
- g (name needs to be in quotation marks)
- j (JSON arrays cannot hold key-value pairs. These need to be within a {curly bracket})
- k (needs to use : instead of ,)
- m (square brackets cannot contain a key-value pair. Must replace [] with {}, or replace the : with ,)
- o (must have the number 0 and name within double quotes)
