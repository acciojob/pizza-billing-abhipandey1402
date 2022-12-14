# Pizza Bill Generator:

In a pizza cafe there are two types of pizzas, regular and deluxe, and both come in their veg and non-veg variants with a base price. You can ask to add extra cheese or toppings if you want on your regular pizza. Deluxe Pizza comes with extra cheese and toppings by default. Also, if you want a takeaway you have to pay for the paper bag that comes with it. In the end you need to generate a bill for the customers.

Veg pizza base price = 300\
Non-veg pizza base price = 400\
Extra Cheese Price = 80\
Extra Toppings For Veg Pizza = 70\
Extra Toppings For Non-veg Pizza = 120\
Paper bag Price = 20

You are given three classes in your driver code. Main.java, Pizza.java and DeluxePizza.java. Your DeluxePizza class should extends Pizza class and it shouldn’t have any extra methods in DeluxePizza class, i.e. make sure it’s constructor takes care of extra cheese and toppings. You have to complete the skeleton code in order to make your app work.

**Bill Structure Example:**

Example 1:\
Base Price Of The Pizza: 300\
Extra Cheese Added: 80\
Extra Toppings Added: 70\
Paperbag Added: 20\
Total Price: 470

Example 2:\
Base Price Of The Pizza: 400\
Extra Cheese Added: 80\
Extra Toppings Added: 120\
Total Price: 600

**Note:**\
The customer might ask for extra cheese or toppings by invoking your method multiple times, but you have to make sure you don’t add it in the bill multiple times.\
Make sure you add extra cheese before the extra toppings if a customer asks for both and it reflect the same in the billing.\
In the billing make sure the string for bill you generate has all components in a different line. (Don’t forget to add “\n” after each line of billing)
