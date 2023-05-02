Download Link: https://assignmentchef.com/product/solved-comp248-assignment-2-a-program-thet-outputs-daya-of-the-week
<br>
Write a program that given a number from 1 to 7 outputs what day of the week it corresponds to (1 = Monday, 7 = Sunday) and whether it is a weekday or weekend. You may assume an integer as input but if the input is not from 1 to 7, you should output that it’s not a valid day.  Write two versions of this program:

<strong>Version 1: </strong>Use an if/else statement

<strong>Version 2:</strong> Use a Switch statement (instead of an if/else)




Here are a few sample outputs to illustrate the expected behavior of your program. <u>Note</u>: user input is highlighted in grey.

Please enter the day of the week as a number (1-7): 7 It’s Sunday! It’s the weekend!

Please enter the day of the week as a number (1-7): 5 It’s Friday! It’s a weekday!

Please enter the day of the week as a number (1-7): 9 That’s not a valid day!

Question 2

Write a program that determines the penalty for a driver who is speeding on highway 401. The program should ask the user how fast the driver was going.

If the driver is driving

<ul>

 <li>less than 10km over the speed limit (100km), the fine is $65.</li>

 <li>10-19km over the speed limit, the fine is $120 and the driver gets 2 demerit points.</li>

 <li>20-39km over the speed limit, the fine is $240 and 5 demerit points.</li>

 <li>40-59km the fine is $360 and the driver gets 7 demerit points.</li>

 <li>160km or over, the driver loses his license on the spot and is given a fine of $520.</li>

</ul>




After determining that the driver was speeding <em>and</em> if they have not yet lost their license, ask the user how many demerit points the driver originally had. When a driver has 12 demerit points they lose their license. Determine if the driver should lose their license given how fast they were driving. Output how many demerit points the driver has after the current infraction.




Here are a few sample outputs to illustrate the expected behavior of your program. <u>Note</u>: user input is highlighted in grey.

———————————————————

SpeedyFines Calculator

———————————————————




How fast was the driver going? 90 The driver was not speeding.

<table width="634">

 <tbody>

  <tr>

   <td width="1"> </td>

   <td colspan="2" width="634">———————————————————             SpeedyFines Calculator———————————————————How fast was the driver going? 113The fine is $120 and the driver gets 2 demerit points!How many demerit points did the driver have prior to being stopped? 8The driver now has 10 demerit points. </td>

  </tr>

  <tr>

   <td colspan="2" width="634">———————————————————             SpeedyFines Calculator———————————————————How fast was the driver going? 137The fine is $240 and the driver gets 5 demerit points!How many demerit points did the driver have prior to being stopped? 0The driver now has 5 demerit points. </td>

   <td width="1"> </td>

  </tr>

  <tr>

   <td width="1"></td>

   <td width="632"></td>

   <td width="1"></td>

  </tr>

 </tbody>

</table>

———————————————————             SpeedyFines Calculator

———————————————————

How fast was the driver going? 165

The fine is $520 and the driver loses his license.

<table width="634">

 <tbody>

  <tr>

   <td width="634">———————————————————             SpeedyFines Calculator———————————————————How fast was the driver going? 147The fine is $360 and the driver gets 7 demerit points!How many demerit points did the driver have prior to being stopped? 6The driver has 13 demerit points and loses his license.</td>

  </tr>

 </tbody>

</table>

<h1>Question 3</h1>

FoodieDelivery is a food delivery service that delivers meals from a number of restaurants around Montreal. They’ve decided to come up with a subscription program with the following details:




<ul>

 <li>The “<em>PayPerDelivery</em>” subscription allows you to pay per use, each delivery costs $3.00.</li>

 <li>The “<em>OccassionalFoodie</em>” subscription costs $15/month and allows you to order food 6 times a month with each additional delivery costing $2.</li>

 <li>The “<em>MontrealFoodie</em>” subscription costs $30/month and allows you to order food 3 times a week (12 times a month) with each additional delivery costing $1.50.</li>

</ul>




Write a program that helps a customer decide which subscription is best for them based on the number of food orders they make per month. The program should ask the user to enter the number of times they typically order food in a <em>month</em>. Calculate the cost of each subscription type and determine the best financial option for the user based on his input and price of the subscription plus extra deliveries. In each of the cases, compute the savings from the other subscriptions. Note, if the value of the next subscription is equal to that of the lower subscription, recommend the higher subscription (e.g. for 5 deliveries both <em>PayPerDelivery</em> and <em>OccassionalFoodie</em> the cost is $15.00 and you should recommend the <em>OccassionalFoodie</em> (see output 2)).

*You can leave more than 2 decimal places for the prices and you should not compute taxes.




Here are a few sample outputs to illustrate the expected behavior of your program. <u>Note</u>: user input is highlighted in grey.

<table width="634">

 <tbody>

  <tr>

   <td width="634">———————————————————             FoodieDelivery Subscription Calculator———————————————————Please enter the number of times a month you use food delivery services: 3The cost of Pay per delivery would be: $9.00/month **We recommend getting the Pay per delivery.** Thank you for using FoodieDelivery Subscription Calculator. Good Eats :-)!</td>

  </tr>

 </tbody>

</table>




<table width="634">

 <tbody>

  <tr>

   <td colspan="2" width="634">———————————————————             FoodieDelivery Subscription Calculator———————————————————Please enter the number of times a month you use food delivery services: 5The cost of pay per delivery would be: $15.00/monthBased on your food deliveries, the cost of the OccasionalFoodie subscription would be:$15.00/month You would save $ 0.00 from PayPerDelivery and $ 15.00 from MontrealFoodie.**We recommend getting the OccasionalFoodie subscription.**Thank you for using FoodieDelivery Subscription Calculator. Good Eats :-)!</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="0"> </td>

   <td colspan="2" width="634">———————————————————             FoodieDelivery Subscription Calculator———————————————————Please enter the number of times a month you use food delivery services: 13The cost of pay per delivery would be: $39.00/monthBased on your food deliveries, the cost of the OccasionalFoodie subscription would be:$29.00/month **We recommend getting the OccasionalFoodie subscription.** You would save $ 10.00 from PayPerDelivery. Thank you for using FoodieDelivery Subscription Calculator. Good Eats :-)!</td>

  </tr>

  <tr>

   <td width="1"> </td>

   <td colspan="2" width="634">———————————————————             FoodieDelivery Subscription Calculator———————————————————Please enter the number of times a month you use food delivery services: 20The cost of pay per delivery would be: $60.00/monthThe cost of pay OccassionalFoodie would be: $43.00/monthBased on your food ordering, the cost of the MontrealFoodie subscription would be:$42.00/month You would save $1.00 from the OccasionalFoodie subscription and $17.00 from PayPerDelivery.**We recommend getting the MontrealFoodie subscription.**Thank you for using FoodieDelivery Subscription Calculator. Good Eats :-)!</td>

  </tr>

  <tr>

   <td width="1"></td>

   <td width="633"></td>

   <td width="1"></td>

  </tr>

 </tbody>

</table>


