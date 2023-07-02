# Python Assignment CA1

 *** My first official assignment done in Python ***

CA guideline :

Details of assignment. 
consider a file product.txt containing
product name file

consider a file quantity.txt containing
product quantity

consider a file purchase_prices.txt containing
product purchase price

consider a file sales_prices.txt containing
product sales price


Create these four files, quantity.txt, sale_price.txt, purchase_price.txt and product.txt

Request input for how many items (N), which is the number of expected rows of data to enter?

Request input for product, quantity and price for purchase and sale

supply the value at each input for product name, quantity and price for sale and purchase and write the inputted values to the respective files line by line using values from the below table.


#Data to write to respective files for calculation of profit.

Product
Quantity
Purchase_price
Sale_price
Mattress
220
$23
$27
Bed
Ten
$344
$424
Pillow
234
$123
$129
Door
44
$1344
$1544
Table
566
$122
$2222
Chairs
13
$1223
$1229

After creating the files:
Read the values entered in the files to calculate profit: 
  Revenue = Quantity*Sale_price 
  Cost= quantity*purchase_price

Note if revenue > $60000 then a cashback of $3000 is given so revenue is less $3000
If revenue > $20000 and <= $60000 then cashback of $150 is given and revenue less $150
But If revenue <=20000 then cashback of $0 is given

The calculated total cost and total revenue (exclude cashback from revenue where applicable) 

Profit= total revenue – total cost.

Report the product name, total revenue , total cost and profit.
Check if final profit> 0 then print a message.
If final profit =0 then print a message
If final profit < 0 then print a message  
