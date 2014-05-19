Stock Watcher
=============

[wrpc-1] Weekly R Prog Contest - 1 | Deadline: 30-May-2014

Task: Write a script to get stock prices of following companies: Apple, Google, Yahoo, Twitter and Facebook 

Hints:

1. Use NASDAQ. Current stock price of Apple is 600+ USD. I got that data from here: http://finance.yahoo.com/q?s=AAPL
2. Each of these companies have their own NASDAQ code. In case of Apple its AAPL. Google and find out whats for others.
3. Doesn't matter which API or website you use. You can use 'Yahoo Finance', 'Google Finance' or whichever comfortable.
4. How it should work: 

          - when I run the code, I should get a vector of prices of these companies
          - Output can be a data.frame or table or csv or bar plot... you can be creative! 
          - You should have a separate function (you can call it anything), to which you pass the NASDAQ code and in return you get the stock price. For ex, I will call it as get_me_stock_price.. so

                    get_me_stock_price <- function (nasdaq_code){
                              # your code here
                    }

          so, if I call get_me_stock_price(AAPL), I should get price of Apple stock. 

        - There should be another function, which repeatedly calls get_me_stock_price for each of the companies.

5. Fork this repo: https://github.com/avinassh/stock_watcher/ and edit the main.R with your script. 
6. Comment your github link after deadline. Do NOT reveal your code before deadline!

All the best! :D

PS: Comments and suggestions are always welcome. If you an idea for next contest, drop me a message!
