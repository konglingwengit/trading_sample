# trading_sample
I've built an webpage which uses coinmarketcap api to compare prices of different exchange on btc &amp; eth &amp; provide real time opportunity


**Are there any sub-optimal choices( or short cuts taken due to limited time ) in your implementation?**
Yes I could have built flask API & let python scripts to do use api of coin market cap & then analyze results & then put them inside database every few seconds.
That way we could ahve handled multiple users at the same time with multiple coins.

**Is any part of it over-designed? ( It is fine to over-design to showcase your skills as long as you are clear about it)**
I was building flask api then I visit coin marketcap grab their API.

**If you have to scale your solution to 100 users/second traffic what changes would you make, if any?**
with these feature it can handle upto 1000 users at the same time cause each user is using coinmarket cap api from it's own ip.
the limit is only few exchanges & 2 coins. But If we have to do this for 1000 coins then I'll build api on aws or on flask.

**What are some other enhancements you would have made, if you had more time to do this implementation**

I could have build 1000 coins checker on multple exchanges with database in backend.
