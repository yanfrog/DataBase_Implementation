# View wiz code mode
Group_HW.db
Create by DB Browser for SQLite
Relations -->
  1.USER : PID（身分證字號）, Fname, Lname, Age, Phone, Email, Cd_account（集保帳戶）
  2.ACCOUNT : AccountID（集保帳號）, BankName, Cost（成本）, Balance（市值）, Remain（帳戶餘額）, Open_Date
  3.STOCK : StockID, StockName, Exchange（上市、上櫃、興櫃）, Category_code（產業類別碼）, Category（產業別）, Reference（參考價）, ShareCapital（資本額）, Total_Shares（發行量）, MarketCapital（市值）, Chairman, DayTrade
  4.TRADE : TradeID, AccountID, Action（買、賣）, StockID, Price, Quantities, Date, Time
  5.DIVIDENT : StockID, Year, Divident
