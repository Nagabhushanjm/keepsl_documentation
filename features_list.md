
# List of all features available in KEEPSL 

<h2> Advanced Features </h2>

## Slippage

![imglog](img/img53.PNG  ':id=img')
<ul>
<li> <p id:p> Slippage refers to when you place a stop loss limit order by the algo, it is the difference between Price and Trigger price.</p></li></ul>

![imglog](img/img54.PNG  ':id=img')

## MTM Stop Loss

<ul><li><p id:p>If you want to define  predefined losses as per your risk management of the strategies, then you can use this feature. You can select the loss in terms of % or in terms of points. Once the criteria is met, algo will automatically exit the strategy. This will achieve you to have minimal losses as per risk and reward.</p>
</li>
</ul>

![imglog](img/img55.PNG  ':id=img')

## MTM Profit
<ul><li><p id:p>If you want to define predefined profits as per your risk management of the strategies, then you can use this feature. You can select the profit  in terms of % or in terms of points. Once the criteria is met, algo will automatically exit the strategy. This will allow you to capture the profit as per risk and reward or in case the market reverses from the current positions.

</p>
</li></ul>

![imglog](img/img56.PNG  ':id=img')


## Positional SL Time 
<ul><li><p id:p>For overnight positions, If the user desires to keep stop loss, then he can opt for stop-loss in AMO/9.18am/9.30am.
</p>
</li>
</ul>

![imglog](img/img57.PNG  ':id=img')

## MSLC 

<p id:p>If strategy has Stop-loss for more than one leg, If one leg SL is hit, Other leg stop-loss will be moved to cost. This is mainly used where we place wide stop losses when the market conditions are volatile thus preventing huge losses.
</p>


![imglog](img/img58.PNG  ':id=img')


# Exclude Days 
<p id:p>
Users can opt if the next day is a trading holiday. He can exclude strategies not to execute if tomorrow is a trading holiday.
<br>
For example, STBT strategy not to trigger in case of a trading holiday to avoid carrying over positions for multiple days.
</p>

![imglog](img/img59.PNG  ':id=img')


## Exit Strategy on Partial Execution 

<p id:p>There are cases where one leg may get Rejected because of funds or other reasons. With this option Selected - any other positions  which have succeeded in this strategy will be closed by the algo. Example: In a straddle CE succeeded but PE rejected, CE will be exited by the algo.</p>


![imglog](img/img60.PNG  ':id=img')


## Prepone on holiday
<p id:p>
Strategy will be advanced 1-day before any trading holiday. Ex:  Assume EXP - 1 strategy and WED is holiday, if you select this option strategy will be executed on TUE.
</p>

<hr><hr>