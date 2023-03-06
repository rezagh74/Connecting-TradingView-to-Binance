# Trade
Trade
⚠️ Now you need to do the following steps in tradingview .

1️⃣ A file containing the Pinescript code will be sent to you 
put the code at the bottom of your script (Tradingview) 

2️⃣ Link your strategies variable to the submitted code 
 If you are not able to do this part, you can get help from the following group 
 https://t.me/pinescript_gp 

3️⃣ And then register an alert in TradingView for your script

4️⃣ Now put the following link in the webhook section of the alert settings

 https://bitnotif.com/pinescript/get.php 

If your tradingview account is free and the webhook isn't active, you can message the admin
Admin :  https://t.me/zaringit



User = '299360676' // Do not change this section
Password = 'OSL8Ehhz' // Do not change this section
Exchange = 'NotSet AlertinTelegram' // Do not change this section

Just_Alert = true
if Just_Alert
    Symbol    = str.tostring(syminfo.ticker)// String
    Timeframe = str.tostring(timeframe.period)// String
    Type = "Just_Alert"
    Text1 = "Crssed MA 50 , 200" // String
    Text2 = "Text2"// String
    Text3 = "Text3"// String
    Text4 = "Text4"// String
    Text5 = "Text5"// String
    Text6 = "Text6"// String
    Text7 = "Text7"// String
    Text8 = "Text8"// String
    Text9 = "Text9"// String
    Text10= "Text10"// String
    alert('{"User":"'+User+'","Password":"'+Password+'","Symbol":"'+Symbol+'","Type":"'+Type+'","Timeframe":"'+Timeframe+'","Text1":"'+Text1+'","Text2":"'+Text2+'","Text3":"'+Text3+'","Text4":"'+Text4+'","Text5":"'+Text5+'","Text6":"'+Text6+'","Text7":"'+Text7+'","Text8":"'+Text8+'","Text9":"'+Text9+'","Text10":"'+Text10+'"}', alert.freq_once_per_bar)
//

