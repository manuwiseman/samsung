cargurus

first 20 mins are like system performance issue investigation problem, sounds like it's something they met in real production scenario
So the interviewer (Chun Shi) mentioned a pariticular dealer landing page(dealer is popular) has slow performance and other seems fine.

Question 1: the performance is slow only for this website, how would you investigate
Anwser: since this doesn't happen to other websites, I don't think network connectivity or DNS could be an issue, I would firstly look into the log and check the load balancer, and see if the instance is healthy or not. If that's server health, check database

Question 2: we have some really old data from dealer, how to deal with them to improve database performance?

Question 3: ususally we will only show top 10 reviews to user, but what if some user wants to see top 100 reviews






after first 20 mins, there's a code problem, which i did kinda ok but maybe not the most optimized solution
given a list of car prices, return the N prices that's closet to the given price, and it should be sorted, e.g. 8000, 9000, 11000