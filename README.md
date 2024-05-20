# naive-time

Sometimes need naive time without leap seconds, 29 Feb, with all month to be 30 days. 

And yet need flexible generic time and duration representation so that can use 16/32/64/96/128 bits to represent value with different ration of instant time agains duration.

So this library abstracts time this way, and implementes borsh, serde + schemas and uom.

