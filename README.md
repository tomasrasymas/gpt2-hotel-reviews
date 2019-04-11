# gpt2-hotel-reviews

This repo contains experiments for generating hotel reviews using GPT-2 model trained on Google Colab using hotel reviews dataset from Kaggle.

* GPT-2 training - https://github.com/nshepperd/gpt-2
* Google Colab - https://colab.research.google.com/notebooks/welcome.ipynb
* Dataset - https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe

## Results
After training model on reviews dataset for 5 hours on single GPU I obtained some interesting results.

```
>>> generate_unconditional_samples.py --top_k=40 --length=40

======================================== SAMPLE 1 ========================================

 The location is excellent Staff were very helpful and friendly and the staff were friendly and welcoming
 Cleanliness and convenience of location
 The decor is beautiful
 Room was spacious and very comfortable Quiet
======================================== SAMPLE 2 ========================================
 The hotel was beautiful and the location was great to go to The breakfast was the best and very tasty The staff were so kind and friendly and very helpful We love the location and would always stay here for
======================================== SAMPLE 3 ========================================
 This property is very good and very convenient for both in terms of parking and tube transfers We got it on the morning we were leaving and were able to walk to Hyde Park for breakfast at The Hilton Westminster
======================================== SAMPLE 4 ========================================
 Also there was a problem with the plug sockets in the room and I had to bring several plugs from 1 person to the room to charge it This was a shame because this is a major problem they solved
======================================== SAMPLE 5 ========================================
 The room the bathroom and the bath The location for us is central and easy to get to all major attractions
 The staff was excellent and I wish that I had been there longer and also in a
======================================== SAMPLE 6 ========================================
 Was my second time here so not much so very bad
 The only negative thing was that our room wasn t properly cleaned so we had to go to reception and be told we had used our toiletries
======================================== SAMPLE 7 ========================================
 Excellent location to get around Milan Staff were welcoming and helpful Room and bathroom very clean and comfortable
 Friendly and helpful staff great hotel with a great location near the Duomo Excellent staff service in all levels
======================================== SAMPLE 8 ========================================

 We loved this hotel We loved that the bed was really comfortable and the shower was great Location in the City was superb The room service menu was outstanding Room service had everything you wanted
 Excellent location
======================================== SAMPLE 9 ========================================
 and it was close enough to city centre
 Really nice staff room was amazing
 The stuff were very friendly and helpful
 Beautiful hotel and rooms super nice staff
 Staff friendly and helpful
 Great
======================================== SAMPLE 10 ========================================

 Staff really helpful room very clean and spacious and quite even though we didn t change anything
 Bed was comfortable room was clean and comfortable
 It was clean and friendly location is perfect for people
```
