[Requirements]
1. User should be able to book tickets
2. User should be able to see a list of supported regions NCR, mumbai etc and each region will have multiple theatres
3. User can select seats while making a booking
4. Only movies no other events supported 
5. No addons 
6. Movies are being played at theatres. Each theatre can have multiple screens, each playing diff movie at the same time 
7. User should be able to cancel the booking 
8. User should be able to book a show.(A show is a movie at a particular time at a particular audi/screen )
9. User should be able to see all movies in a particular region 
10. User should be able to see all shows of a movie in a region 
11. In one booking a user can book upto to 10 seats 
12. No 2 people should be able to book the same seats 
13. Seats should be blocked for 10 minutes before the payment is made 
14. Price is a function of -> Theatre + seat type + time + movie 
15. Only online payments managed by 3rd party, We store reference id, payment gateway etc 
16. Payment can have different modes UPI, card, etc 
17. Refund provided in case of cancellation 
18. BMS stores the actual data (not an aggregator)
19. Movie would have features Dolby sound, 2D, 3D etc language IMax 
20. Features are at a show level as well 
21. Audi would also support features 
22. Each screen has multiple seats of different types (seat type would be a class )
23. Support partial payment 
24. Every movie has cast, runtime etc