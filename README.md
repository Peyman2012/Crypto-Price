# Crypto-Price
Library needed to get bitcoin price:

    pip install pycoingecko

Getting the price from a special api:

     cg = CoinGeckoAPI()
     
Two currency codes that are used in the ids code for the names of the currencies and vs_currencies for the names of the money.

    data = cg.get_price(ids='bitcoin,ethereum',vs_currencies = "usd,eur") #Get dollar and euro bitcoin prices
