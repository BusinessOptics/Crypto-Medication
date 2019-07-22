# Crypto-Medication

*An initial interview task*

The goal of this task is to show how much volatility there would be if you could pay for basic medicines in Bitcoin. The spec is left a little open ended. You have limited resources to work with but they are enough to complete the task. The goal of this task is to get a feeling for your programming and problem solving ability, but it is very basic and should not take more than a few hours. 

If you are in doubt of a detail of the spec just use your best judgement and let me know what you decided with the submission. 

On the front-end side of the problem, please do not worry too much about design, obviously better looking things are nicer but there is no need to worry about pixel pushing. What is important is that the UX shows consideration of what the problem is trying to solve.

The spec
--------

The South African government is considering allowing for medication to be bought using Bitcoin (don't worry this is not true). They want a tool that will allow consumers to understand how their payments historically would have changed over time if they had been paying for their medication in bitcoin. 

The app needs to provide a search input where users can enter the name of their medication, then it needs to (through hitting a number of different services) show what the effective full-pack price of their medication would have been in Bitcoin, assuming the medication's Rand price remained stable at the current price:
  * Today
  * 1 Day ago
  * 1 week ago
  * 1 Month ago
  * 1 Year ago
  * 5 years ago

It should also help the user interpret the consequences of this in some way (just some simple stats that make sense to the user).

You can make some simplifications about how actual currency exchange works, what we are looking for here is something high level and indicative, not something that deals with the technicalities of currency trades.

It is expected that you will be building a web app for this task, not a command line app.

Some pointers on resources
--------------------------

OpenUp hosts a Medical Price Registry, which you can find here:

https://mpr.code4sa.org/

https://github.com/Code4SA/medicine-price-registry

OpenExchangeRates has a free plan, which allows you to get the historic prices of currency pairs. It is very limited but has enough information for you to work things out. I have registered a free account, which you can use. The API KEY is b68bc89b827546d29e2027018ab17d97. You can find the documentation for the API at:

https://docs.openexchangerates.org/

The currency code for South African Rands is ZAR, for Bitcoin it is BTC. The plan only has 1000 hits a month, which really should be fine, but if it runs out just register another account on the free plan.

You may also use anythign else, as long as we can run it.

Technologies and Submission Criteria
------------------------------------

You can choose between using Python or Node for this on the backend. You may use any libraries you want.

I run an Ubuntu machine, and I would like to be able to run the service by running a single script (it does not have to be a production deployment).

Please let me know if you hit any blocking issues.
