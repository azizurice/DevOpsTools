# MongoDB
MongoDB is a document database built on a scale-out(horizontal) architecture that has become popular with developers of all kinds who are building scalable applications using agile methodologies. It stores data as BSON documents which is a binary representation of JSON.  The BSON encoding extends JSON with additional types such as int, long, date, floating point, and decimal128. This makes it much easier for applications using MongoDB to reliably process, sort, and compare data.


```json
{
"_id":
ObjectId("5ad88534e3632e1a35a58d00"),
"name": {
"first": "John",
"last": "Doe" },
"address": [
{ "location": "work",
"address": {
"street": "16 Hatfields",
"city": "London",
"postal_code": "SE1 8DJ"},
"geo": { "type": "Point", "coord": [
51.5065752,-0.109081]}},
],
"phone": [
{ "location": "work",
"number": "+44-1234567890"},
],
"dob": ISODate("1977-04-01T05:00:00Z"),
"retirement_fund":
NumberDecimal("1292815.75")
}
```
[MongoDB Architecture](https://info-mongodb-com.s3.us-east-1.amazonaws.com/MongoDB_Architecture_Guide.pdf)
