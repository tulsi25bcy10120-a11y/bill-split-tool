Bill Splitter Device
It is a simple tool/device which will divide the total amount among the given people.
 Features:
​Itemized Input: Allows us to enter the name and price for every thing on a bill.
​Good Calculations: It calculates the subtotal, grand total (without including tax/tip), and the cost per people.
​Error Handling: Checks basic error checking for non-numerical  inputs.
​Clear Output: Displays a clean result of the costs.
​ How to Use
​Things needed to run this program
​Python 3 installed on your system.
​Running the Script
add the txt file on your complier than run the program on your device.

Now enter the item1name in the input box
then enter the price paid for that item and so on follow this order.
When you are completed with your items enter done the program then will ask how many people want to divide this amount.



The final outcome should come like this.
 [Setup and input collection] 

 Main Calculation Logic
people_count = int(input("How many people are dividing this?: "))

subtotal = sum(item_price)
grand_total = subtotal # Assuming no tax/tip for easier calculations
per_people = grand_total / people_count

 [Output display]