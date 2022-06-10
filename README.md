# Value Updater in Python

A project which uses Redis caching, and a Database that provides the current quantity for a specific SKU at a specified location.

## Instructions
Upload a CSV file of your choosing, or you can use any of the csv files in the test-resources directory.


There are 3 columns in the CSV:
* Location: a string of a 4-digit location number, which can stand for a store number or distribution center.
* Quantity: this is the quantity adjusted. Can be a postiive or negative integer. No floating point because each item cannot be divided into pieces. Therefore, it is in integers.
* SKU: the identifier for the item being sold. Integer value.

