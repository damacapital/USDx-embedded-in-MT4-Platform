# USDx-embedded-in-MT4-Platform

Welcome to the USDx-embedded-in-MT4-Platform wiki!

USDx, also known as U.S. Dollar Index, is an index (or measure) of the value of the United States dollar relative to a basket of foreign currencies, often referred to as a basket of U.S. trade partners' currencies. The Index goes up when the U.S. dollar gains "strength" (value) when compared to other currencies. (please refer to wiki for more details, https://en.wikipedia.org/wiki/U.S._Dollar_Index)

The movement of U.S. Dollar, as the most powerful and traded currency, is highly correlated to the movement of Gold, and USD-pair currencies. MT4 is the most used trading platform. As a financial investors or traders, it is essential to have a USDx tool that can be embedded into MT4 to enhance the efficiencies of your trading and profitabilities of your performance.

This MT4 indicator is made with visualized candle sticks (bullish with red color, bearish with white color) and multiple simple moving average (10,20,40). Source code is provided. Code can be easily edited too.

Formula of USDX:
USDX = 50.14348112 x (EURUSD)^(-0.576) x (USDJPY)^(0.136) x (GBPUSD)^(-0.119) x (USDCAD)^(0.042) x (USDSEK)^(0.042) x (USDCHF)^(0.036)

Installation:
1. Your must signup a MT4 account with any forex broker;
2. Your forex broker must provide the following currency pairs: EURUSD, USDJPY, GBPUSD, USDCAD, USDSEK, USDCHF
(USDSEK can be replaced with USDNOK)
3. Open your MT4 Platform, select "File" > "Open Data Folder" > "MQL4" > "Indicators" 
4. Drag the "USDX.mq4" file into "Indicators" folder in the 3 step
5. Select "View" > "Navigator", under "Indicators" list, select "USDX", right click and select "Modify"
6. In the MetaEditor, select "USDX.mq4", click "Compile" or F7(keyboard shortcut) 
7. Close your MT4 platform
8. Reopen your MT4 platform
9. Select "View" > "Navigator", under "Indicators" list, select "USDX"
10. Drag "USDX" indicator to any Chart Window
11. Enjoy! 
