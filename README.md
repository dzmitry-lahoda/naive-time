# naive-time

Sometimes need naive time without leap seconds and these year with 29 Feb, and months are 30 days. 

And yet need flexible time and duration representation so that can use 16/32/64/96/128 bits to represent value with different ration of instant time agains duration.

So this liberary abstracts time this way, and implementes borsh, serde + schemas and uom.
