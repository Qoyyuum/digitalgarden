---
{"dg-publish":true,"permalink":"/digital-garden/e-commerce/snipcart/"}
---

[Snipart](https://www.snipcart.com) is a fantastic way of adding eCommerce functionality to a static website. It is a popular choice to be added to most [Jamstack](https://jamstack.wtf), allowing developers to focus more on Frontend and less on Backend.

## Business Model

The business model behind it is also very simple. They charge 2% per transaction on top of payment gateway fees or CAD13 (that's Canadian Dollars) for monthly sales under CAD629. So I guess if I were to calculate their business model for businesses that make less than that and assuming without the fixed CAD13:

```math
# January
january_sales = 200
snipcart_percentage_charge = 2/100

snipcart_january_profit = january_sales * snipcart_percentage_charge

# February
february_sales = 600
snipcart_percentage_charge = 2/100

snipcart_february_profit = february_sales * snipcart_percentage_charge

# March 
march_sales = 629
snipcart_percentage_charge = 2/100

snipcart_march_profit = march_sales * snipcart_percentage_charge
```

I guess if they need to make enough money to cover hosting server costs, this business model makes sense to cover a minimum charge of CAD13 per month. 

