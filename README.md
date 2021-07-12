
created a database name as Techtest and then import the sql file. and place the src folder in your server root folder to access the file. 

All credentials and setting will be done in config file.

I have declare an object in Order class. Just pass the cart id and user id in the constructor and get the desire result.

case1:  cart_id = 1 and user_id = 1 where it found the user as employee and allocate the 30% discount on non grocies product.

case 2: cart_id = 2 and user_id = 2 where it found the user as affiliated suer and allocate the 10% discount on non grocies product.

case 3: cart_id = 3 and user_id = 3 
 
 Here 2 cases occur. if an entry exists into order table of 3 years ago then it will allocate 5% discount else it will allocate 0. You can change the order date and can see the difference.
 
