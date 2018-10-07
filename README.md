# Recsys: 
Comparison and Analysis of  three recommendation algorithms in E-commerce based on user click event.

Language: Python

# Models:
* 1. Item-to-item collaborative filtering model (item CF model).
* 2. Latent semantic indexing topic model (topic model).
* 3. Popularity model.

# Database: download dataset here: http://recsys.yoochoose.net/challenge.html
CLICKS DATASET FILE DESCRIPTION
------------------------------------------------------------------------------------------------------------------
1. yoochoose-clicks.dat
* Session ID - in one session there are one or many clicks. Could be represented as an integer number.
* Timestamp - in one session there are one or many clicks. Could be represented as an integer number.
* Item ID - the unique identifier of the item that has been clicked. Could be represented as an integer number
* Category - the context of the click. The value "S" indicates a special offer, "0" indicates  a missing value, a number between 1 to 12 indicates a real category identifier, any other number indicates a brand. E.g. if an item has been clicked in the context of a promotion or special offer then the value will be "S", if the context was a brand i.e BOSCH, then the value will be an 8-10 digits number. If the item has been clicked under regular category, i.e. sport, then the value will be a number between 1 to 12

BUYS DATSET FILE DESCRIPTION
------------------------------------------------------------------------------------------------------------------
2. yoochoose-buys.dat
* Session ID - the id of the session. In one session there are one or many buying events. Could be represented as an integer number.
* Timestamp - the time when the buy occurred. Format of YYYY-MM-DDThh:mm:ss.SSSZ
* Item ID – the unique identifier of item that has been bought. Could be represented as an integer number.
* Price – the price of the item. Could be represented as an integer number.
* Quantity – the quantity in this buying.  Could be represented as an integer number.

TEST DATASET FILE DESCRIPTION
------------------------------------------------------------------------------------------------------------------
3. yoochoose-test.dat

* The file yoochoose-test.dat comprising only clicks of users over items.
This file served as a test file in the RecSys challenge 2015. 
The structure is identical to the file yoochoose-clicks.dat but you will not find the
corresponding buying events to these sessions in the yoochoose-buys.dat file.


