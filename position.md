> Positions

## Option Premium Range 
<ul><li><p id:p>Options Premium Range: Now you can specify MIN and MAX values, so that strike will be selected only if premium is above minimum and strike which is closer to MAX value. This way you don't end up taking trades where the premium is lower than your expectation.</p></li>
<li><p id:p>This is available at a position level.</p></li>
</ul>



# Expiry Type
<p id:p>Weekly expiry is the current week expiry</p>
<b>For example</b>
<p id:p>Present day is 19 Sept 22 , then current week expiry will choose the next thu expiry that is 22 Sept 22.</p>

![imglog](img/img61.PNG ':id=img')


## Monthly expiry is the current month expiry 

<b>For example</b>
<p id:p>Present day is 19 Sept 22 , then current month expiry will choose the last thursday of the month that is 29 Sept 22.</p>

![imglog](img/img62.PNG ':id=img')


## Weekly expiry

<p id:p>Weekly expiry in the future  option will let you choose next week expiries in the same month apart from current week. Select 1,2,3 and 4 from the dropdown to select the week you want to trade in.</p>
<b>For example</b>
<p id:p>Present day is 05 Oct 22 , then current week expiry is  06 Oct 22  and weekly expiry in future will be 13 Oct  22.</p>

![imglog](img/img63.PNG ':id=img')

![imglog](img/img64.PNG ':id=img')

<hr>

# Strike Type

<ul>
<b>At The Money/ In The Money/ Out of The Money. </b>
<li><p id:p>ATM is the strike nearest to the spot price.</p></li>
<li><p id:p>OTM is away from spot ie 17650CE, 17700 CE etc on CALL side and 17550 PE, 17500 PE etc on PUT side.</p></li>
<li><p id:p>For example if nifty spot price is 17622, then 17600CE and 17600 PE are ATM strikes.</p></li>

<b>Premium Based</b><br>
<b>Delta Based</b>

![imglog](img/img65.PNG ':id=img')
</ul>
<hr>

## Premium Based
<p id:p>
If you want to sell based on the premium price of the strike, choose strike type as premium based and enter the desired value.
</p>

![imglog](img/img66.PNG ':id=img')

<hr>

## Options DELTA Based

<p id:p>
If you want to sell or buy based on the DELTA of the strike, choose strike type as OPTIONS DELTA and enter the desired value of delta.</p>

<b>Exit based on  Contract Expiry</b>

<p id:p>Exit day will be dynamically calculated based on the contract you are trading. If your contract expiry is in the future 2 weeks it will exit based on that contract date.</p>

<b>LIMIT Order</b>
<p id:p>If an entry is LIMIT, exit will be LIMIT as well. If the order is not filled in 10 seconds, the order will be converted to market automatically.</p>


# Creating Positions
<ul>
<li><p id:p>Users can create multiple positions by filling all the below details. </P></li>
<li><p id:p>Action type is whether you want to buy or sell an instrument.</p></li>
<li><p id:p>Segment you can choose between options and futures.</p></li>
<li><p id:p>Instrument you can choose between Bank Nifty, Nifty and Stock options.</p></li>
 <li><p id:p>Expiry Type can be weekly, monthly, monthly plus, monthly expiry in future and weekly expiry in futures.</p></li>
<li> <p id:p>Strike types can be At The Money (ATM), In The Money (ITM), Out of The Money, Premium based and Options Delta based.</p></li>
<li><p id:p>Option type can be CALL or PUT.</p></li>
<li><p id:p>Lots- Enter the number of lots you want to trade.</p></li>
<li><p id:p>If your strategy is condition based, select it otherwise need not select.</p></li>
<li><p id:p>Entry days can be monday, tuesday, wednesday, thursday, friday, weekly expiry day and day before weekly expiry. Select based holiday calendar in NSE.</p></li>


![imglog](img/img67.PNG ':id=img')

<li> <p id:p>Entry time  and Exit time are between 0917 AM to 0328 PM.</p></li>
<li><p id:p>Exit days can be Weekly Expiry Day, Days before Weekly Expiry, Same Day and Next Day.</p></li>
<li><p id:p>Stop Loss- User can define the stop losses in terms of points or %.</p></li>
<li><p id:p>Take Profit- User can decide how many points of profit he wants to book in terms of points or %.</p></li>
<li><p id:p>Leg order type- User can decide whether the order he is executing is limit order or market order.</p></li>
<li><p id:p>Re-Entry/Re-Execute- If the user wants to re enter the leg which has already hit the stop loss can do it by clicking this feature.</p></li>
<li><p id:p>Wait and Trade - If the user wants to enter a particular strike, but its price is not at the desired level of the user. Users can wait for the strike to come to desired level.</p></li>

![imglog](img/img68.PNG ':id=img')

</ul>
<hr>
<hr>

