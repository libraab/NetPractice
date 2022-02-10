
 💻--🌍--💻

[![jaeskim's 42Project Score](https://badge42.herokuapp.com/api/project/abouhlel/NetPractice)](https://github.com/JaeSeoKim/badge42)


-------------
                                                    * L E V E L (1) 
-------------
![Screen Shot 2022-02-07 at 2 30 05 PM](https://user-images.githubusercontent.com/81954460/152797260-895d5333-167b-4917-9a82-47ded5d110ed.png)

Step 1)- Clear all the sections that you can clear.

Step 2)- In order to comunicate with each other A1 & B1 must have the same netmask and close IP addresses (same for C1 & D1).

  So we're gonna give to A1 the IP address that comes right after (or before) B1 IP address.
  
  If the address before doesn't work that means it is not assignable, try the ip address that comes after.

Ps: an IP address is not assignable cause it's already taken by either the network or the broadcast.

Step 3)- Same with C1 & D1, we're gonna give to D1 the IP address that comes right after or before C1 IP address.

![level 1 done](https://user-images.githubusercontent.com/81954460/152797024-ceefb220-99a3-429c-adaa-74bf70ced06b.png)
DONE
-------------
                                                       * L E V E L (2)
-------------
![Screen Shot 2022-02-07 at 1 32 48 PM](https://user-images.githubusercontent.com/81954460/152797489-c95dd1fe-f3b5-4f2d-b376-8b83847d2895.png)

step 1)- Clear all the sections that you can clear (step 1 will be the same in all the levels, I highly recommend to do it that way).

Step 2)- Computer 'A' needs to comunicate with computer 'B'; so they must have the same mask and close IP addressses (same as level 1).

Step 3)- The netmasks of Computer C & D are already the same; 30 is another way to write 255.255.255.252.

  Now we need to give them close IP adresses (such as 20.0.0.1 & 20.0.0.2).
  
  Ps : Doesn't work with IP starting with 10 (cause they're private addr).
  
 ![Screen Shot 2022-02-07 at 1 53 29 PM](https://user-images.githubusercontent.com/81954460/152797521-b1a9bb6b-faa5-4318-9aee-ed46c36bb4d7.png)
 DONE
-------------
                                                     * L E V E L (3)
-------------
![Screen Shot 2022-02-07 at 1 54 35 PM](https://user-images.githubusercontent.com/81954460/152797552-ea31436f-fc32-4497-a0d4-2e4095ec24a0.png)

Step 1)- Clear all the sections that you can clear.

Step 2)- Host A, B and C are in the same network (they are linked to each other), give them all the same mask.

Step 3)- Give Host C & B close IP addresses to Host A IP address.

(if the 2 IP addresses that comes after doesn't work try the 2 that comes before).

![Screen Shot 2022-02-07 at 1 55 48 PM](https://user-images.githubusercontent.com/81954460/152797562-547f9a3e-3eb3-4a3a-99dc-0c5f27e39d51.png)
DONE
-------------
                                                   * L E V E L (4)
-------------
![Capture d’écran 2022-02-08 à 16 29 04](https://user-images.githubusercontent.com/81954460/153019889-832fcfa8-3461-4a52-bd54-63e5785ce163.png)

Step 1)- Clear all the sections that you can clear.

Step 2)- Here we have a router, don't panic (it's kinda box of entrances and exits), in this level it's useless but for the next levels we're gonna have to tell what entrance and exit to take.

For now, give to each item an IP close to A1 IP.

![Capture d’écran 2022-02-08 à 16 28 48](https://user-images.githubusercontent.com/81954460/153019922-17098961-b92c-47cd-be77-7b5daedbc579.png)

step 3)- We can put any netmask here except a mask over /29 (why? cause with /30 for example you can only afford 2 IP addresses).

The smaller the mask the larger range of IP it will give you but let's not be greedy and let's put /29.

![Capture d’écran 2022-02-08 à 16 27 16](https://user-images.githubusercontent.com/81954460/153019948-3ed7957c-0459-45c5-a69b-34e1cd13886c.png)
DONE
-------------
                                                       * L E V E L (5)
-------------
step 1)- Clear all the sections that you can clear.

step 2)- Give the same netmask to R1 & A1.

step 3)- Give the same netmask to R2 & B1.

step 4)- In the left section of the machine B routes there is the word "default". Put the same in machine A routes (in the left section of course).

step 5)- In the right section of machine B routes, put the IP of R2.

step 6)- In the right section of machine A routes, put the IP of R1.

(It's like telling the computer "if you don't find what you're looking for, by default go there, and look for it").
DONE
-------------
                                                     * L E V E L (6)
-------------
step 1)- Clear all the sections that you can clear.

step 2)- Put "default" in all the left section of blue boxes except for Internet (cause The internet is special).

step 3)- Netmask of A1 has to be the same of R1's netmask.

step 4)- R1 has to have a close IP address to A1's IP. R1's IP must be in the right section of client A.

step 5)- In the left section of Internet put the network address of A1; how? by replacing the last digits by 0) then add a netmask of /24 (if you wonder why /24, because it's convenient.
DONE
-------------
                                                     * L E V E L (7)
-------------
step 1)- Clear all the sections that you can clear.

step 2)- If you already have "0.0.0.0/0" at the left section of the routes keep them("0.0.0.0/0" or "default" are the same).

step 3)- Here we have 3 networks; R11 & A1 are linked and must be in the same network, same for R12 & R21, same for R22 & C1.

Since for each network we only have two devices we can use a netmask of /30 (that give us a range of only 2 IP addresses which is enough).

By using a small range we avoid mistakes or intefering in others networks.

If we use a netmask that gives you a larger range we'll have to do some math and binary shit, if you know how to do this be my guest and get out of this tuto cause you don't need it.

So put a netmask /30 for everyone.

step 4)- A1 must have the IP that comes right after R11 IP.

step 5)- Put for R21 the IP that comes BEFORE R12 IP. (IPs that ends up with 255 are never assignable).

step 6)- For R22 & C1 we can put 20.0.0.1 & 20.0.0.2

step 7)- Now let's take care of the routes; put R11's IP in the right section of client A:dev.non-real.net.

step 8)- Put R22's IP in the right section client C:accounting.non-real.net.

step 9)- When you have 2 routers linked to each other, in order to connect them we have to give to each of them the IP of the other;

so put R12's IP in the right section of router R2 and put R21's IP in the right section of router R1.
DONE
-------------
                                                  * L E V E L (8)
-------------
step 1)- Clear all the sections that you can clear.

-------------
                                                  * L E V E L (9)
-------------
Ok this level is the most tricky one. Let's try to achieve a goal at a time.

Goal (1) --> First goal: meson needs to communicate with ion.
- Clear all the sections that you can clear.
- B1 (ion) & A1 (meson) & R11 are in the same network. Give them the same mask as R11.
- Give to B1 & A1 & R11 the following IP (20.0.0.1 & 20.0.0.2 & 20.0.0.3).
- Put "default" in the left sections of ion & meson's routes.
- Put R11's IP in the right section of ion & meson's routes.
Click on check again to see if goal 1 is achieved.

Goal (2) --> cation needs to communicate with gluon.
- 
step 3)- 
DONE
--------------
                                                  * L E V E L (10)
--------------
step 1)- clear all the sections that you can clear.
DONE
