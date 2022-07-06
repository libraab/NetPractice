
 💻--🌍--💻

------------------ N E T P R A C T I C E - T U T O R I E L ---------------------
-------------
                                            * L E V E L (1) *
-------------
<img width="1163" alt="Screenshot 2022-02-10 at 13 55 22" src="https://user-images.githubusercontent.com/81954460/153414118-4681b735-1985-4816-a76e-60fb48f8114f.png">

Step 1)- Clear all the sections that you can clear.

Step 2)- In order to comunicate with each other A1 & B1 must have the same netmask and close ip addresses (same for C1 & D1).

  So we're gonna give to A1 the ip address that comes right after (or before) B1 ip address.
  
  If the ip address that comes before doesn't work that means it is not assignable, try the ip address that comes after.

Ps: an ip addr is not assignable cause it's already taken by either the network or the broadcast.

Step 3)- Same with C1 & D1, we're gonna give to D1 the ip address that comes right after or before C1 ip address.

<img width="1163" alt="Screenshot 2022-02-10 at 13 56 17" src="https://user-images.githubusercontent.com/81954460/153414154-60510143-569a-4046-a9fb-e760aee5972c.png">

DONE ✅

-------------
                                            * L E V E L (2) *
-------------
![Screen Shot 2022-02-07 at 1 32 48 PM](https://user-images.githubusercontent.com/81954460/152797489-c95dd1fe-f3b5-4f2d-b376-8b83847d2895.png)

step 1)- Clear all the sections that you can clear (step 1 will be the same in all the levels, I highly recommend to do it that way).

Step 2)- Computer 'A' needs to comunicate with computer 'B'; so they must have the same mask and close ip addressses (same as level 1).

Step 3)- The netmasks of C & D are already the same; /30 is another way to write 255.255.255.252.

  Now we need to give them close ip adresses (such as 20.0.0.1 & 20.0.0.2).
  
  Ps : Avoid using private IP addresses (such as those starting with 10) cause it's not gonna work of course.
  
![Screen Shot 2022-02-07 at 1 53 29 PM](https://user-images.githubusercontent.com/81954460/152797521-b1a9bb6b-faa5-4318-9aee-ed46c36bb4d7.png)

DONE ✅
 
-------------
                                             * L E V E L (3) *
-------------
![Screen Shot 2022-02-07 at 1 54 35 PM](https://user-images.githubusercontent.com/81954460/152797552-ea31436f-fc32-4497-a0d4-2e4095ec24a0.png)

Step 1)- Clear all the sections that you can clear. Let's start on clean sheet.

Step 2)- Host A, B and C are in the same network (they are linked to each other by the wire, let's just assume that the switch doesn't exist), put the same mask to all 3 of them.

Step 3)- Give Host C & B close ip addresses to Host A's IP.

(if the 2 ip addresses that comes after doesn't work try the 2 that comes before).

![Screen Shot 2022-02-07 at 1 55 48 PM](https://user-images.githubusercontent.com/81954460/152797562-547f9a3e-3eb3-4a3a-99dc-0c5f27e39d51.png)

DONE ✅

-------------
                                              * L E V E L (4) *
-------------
![Capture d’écran 2022-02-08 à 16 29 04](https://user-images.githubusercontent.com/81954460/153019889-832fcfa8-3461-4a52-bd54-63e5785ce163.png)

Step 1)- ...🧹

Step 2)- Here we have a router, don't panic (it's kinda box of entrances and exits), in this level it's useless but for the next levels we're gonna have to tell what entrance and exit to take, we'll get there.

step 3)- For now we can put any netmask here except a mask over /29 (why? cause with /30 you can afford only 2 IP and we need 3).

![Screen Shot 2022-03-03 at 5 48 50 PM](https://user-images.githubusercontent.com/81954460/156613094-2d1385cf-804b-407a-baff-810052179b91.png)

The smaller the mask the larger range of IP it will give you. But let's not be greedy; /29 is already more than we need.

![Capture d’écran 2022-02-08 à 16 28 48](https://user-images.githubusercontent.com/81954460/153019922-17098961-b92c-47cd-be77-7b5daedbc579.png)

Now, give to each device an IP close to A1's IP.

![Capture d’écran 2022-02-08 à 16 27 16](https://user-images.githubusercontent.com/81954460/153019948-3ed7957c-0459-45c5-a69b-34e1cd13886c.png)

DONE ✅

-------------
                                              * L E V E L (5) *
-------------
step 1)- Start on clean sheet.

<img width="1360" alt="blank5" src="https://user-images.githubusercontent.com/81954460/153410385-88abe040-04a5-471e-b865-6f2e3873b9be.png">

step 2)- Give the same netmask to R1 & A1.

step 3)- Give the same netmask to R2 & B1.

step 4)- In the left section of the Client B routes there is the word "default". Put the same in Client A routes (in the left section of course).

step 5)- In the right section of Client B routes, put the ip of R2.

step 6)- In the right section of Client A routes, put the ip of R1.

<img width="1260" alt="second5" src="https://user-images.githubusercontent.com/81954460/153410496-19e31f73-e684-4f1f-8621-29866e2ac5f4.png">

Step 7)- Give to B1 an ip close to R1's ip and to A1 an ip close to R2's IP. (...255 and ...127 won't work cause they're already taken).

(Remember what we said about routers earlier (entrances & exits) it's like saying to the device "if you're looking for someone (left section) (default = anyone), go there (right section)". If you want the safest way and you just wanna pass, then, ALWAYS put defaut in the left section and the IP of the closest router's entrance in the right section).

<img width="1435" alt="DONE5" src="https://user-images.githubusercontent.com/81954460/153411580-964b7709-d740-43a0-aaa3-1dd0cdaf0257.png">

DONE ✅

-------------
                                                * L E V E L (6) *
-------------
step 1)- 🧹
![level6-1](https://user-images.githubusercontent.com/81954460/155979791-71465be3-a55a-4492-84cc-2fb8b4fafc3d.png)
step 2)- Put "default" in all the left section of blue boxes except for Internet (cause The internet is special 🥰).

step 3)- Netmask of A1 has to be the same of R1's mask.

step 4)- R1 must have a close ip to A1's ip.
       - Put R1's ip in the right section of client A (remember; always in the right sections of routes, put the IP of the closest router, even for the internet).
![level6-2](https://user-images.githubusercontent.com/81954460/155979807-4f7aab39-fdaa-41fa-92f6-e9ac906f6554.png)
step 5)- In the left section of Internet put the network address of A1; how? by replacing the last digits by 0 ) then add a mask of /24 (if you wonder why /24, because it's convenient).
![level6-3](https://user-images.githubusercontent.com/81954460/155979830-d6f471e2-4b3f-47bc-bd01-381e530b5bd0.png)

DONE ✅

-------------
                                                * L E V E L (7) *
-------------
step 1)- 🧹
![level7blank](https://user-images.githubusercontent.com/81954460/155979856-8c57ce08-f187-4c56-9df9-3c87a4fc4ace.png)
step 2)- If you already have "0.0.0.0/0" at the left section of the routes keep them("0.0.0.0/0" or "default" are the same).
![Screen Shot 2022-02-28 at 12 52 39 PM](https://user-images.githubusercontent.com/81954460/155979888-7a358f5d-1731-461e-ad36-b2e7846fdea4.png)
step 3)- Here we have 3 networks; R11 & A1 are linked and must be in the same network, same for R12 & R21, same for R22 & C1.

Since for each network we only have two devices we can use a mask of /30 (that give us a range of only 2 ip addresses which is enough).

By using a small range we avoid mistakes or intefering in others networks.

If we use a mask that gives you a larger range we'll have to do some math and binary shit, if you already know how to do this be my guest and get the f out of this tuto for dummies.

So put a mask /30 for everyone.

step 4)- A1 must have the ip that comes right after R11 ip.

step 5)- For R21 put the ip that comes BEFORE R12 ip. (IPs that ends up with 255 are never assignable cause they're already taken by the broadcast).

step 6)- For R22 & C1 we can put 20.0.0.1 & 20.0.0.2, it works, no need to be fancy.
![level7](https://user-images.githubusercontent.com/81954460/155988198-a6c8b9bb-7162-4ad3-9bd2-0a947693c66c.png)
step 7)- Now let's take care of the routes; put R11's ip in the right section of client A :dev.non-real.net.

step 8)- Put R22's ip in the right section client C :accounting.non-real.net.

step 9)- When you have 2 routers linked to each other, in order to connect them we have to give to each of them the ip of the other;

so put R12's ip in the right section of router R2 and put R21's ip in the right section of router R1.
![level7done](https://user-images.githubusercontent.com/81954460/155988254-3128d6f5-b55c-4109-8f34-6a3e16b683a9.png)

DONE ✅

-------------
                                               * L E V E L (8) *
-------------
Step 1)- 🧹
![level8blank](https://user-images.githubusercontent.com/81954460/155988300-f36476c1-3761-4e46-8650-4036058e8034.png)
Step 2)- The first goal tells us that client C needs to communicate with client D; that means C1, D1, R22 and R23 need to be in the same network.

Let's give them the same mask, which means 255.255.255.240. R22 & C1 masks could have the same mask aswell but /30 is enough, anyways both works; what's important is that the linked devices (follow the wire) must have the same mask.

Step 3)- Put default in all the left sections of the routers.

Step 4)- Before going to fill the IP's, let's notice that this level impose on us a specific network already put in the left section of the internet.

That means that all the devices will have to be in this network in order to have access to the internet.

The address network is 134.125.140.0 and the mask is /26.
![level8goal](https://user-images.githubusercontent.com/81954460/155988832-2d298295-ceeb-4ef5-a41f-424038965d61.png)
I start by filling the ip's for the devices on the left, then the devices on the right, if you wonder why I choose ip's ending with 17 and 18, here's why;

(the mask for the devices on the left is 255.255.255.240 and by doing the substraction (255 - 240) = 15, I know that I have a range of 15 ip's, so I try not to interfere with this range, so that means ip's from 134.125.140.1 to 134.125.140.15 are taken and the following one (134.125.140.16) is usually taken by the broadcast).

If you go on any IP calculator site and put the network address and the mask if gives you the range of assignable IP specific to this network and other informations, just to have an idea.
![Screen Shot 2022-03-03 at 6 26 21 PM](https://user-images.githubusercontent.com/81954460/156619564-24c94dcd-056a-493e-b6a1-abc525dfe50b.png)

Of course you're not allowed to use this site during evaluation, unless your evaluator is your cousin and he'll close his eyes to that.
But this link could be useful for you if you find yourself stuck during training.

![level8done](https://user-images.githubusercontent.com/81954460/155988868-7187b725-19e5-461d-a077-ac113f48e49c.png)

DONE ✅

-------------
                                               * L E V E L (9) *
-------------
Ok this level is the most tricky one. Let's try to achieve a goal at a time.
![level9-blank](https://user-images.githubusercontent.com/81954460/155989195-c28c2cc9-a9df-47d4-bc10-e4e7f5274961.png)
Goal (1) --> First goal: meson needs to communicate with ion.
- First thing first 🧹
- B1 (ion) & A1 (meson) & R11 are in the same network. Give them the same mask as R11.
- Give to B1 & A1 & R11 the following IP (20.0.0.1 & 20.0.0.2 & 20.0.0.3).
- Put "default" in the left sections of ion & meson's routes.
- Put R11's IP in the right section of ion & meson's routes.
Click on check again to see if goal 1 is achieved.
![level9-goal1](https://user-images.githubusercontent.com/81954460/155989221-672e8155-a664-468c-ae22-d1ffe9761372.png)
Goal (2) --> cation needs to communicate with gluon.
![level9-goal2blank](https://user-images.githubusercontent.com/81954460/155989262-b949938e-8ebd-4670-9a93-e738b9268faf.png)
- R23 & D1 have to have the same mask which means /18.
- In the right section of Gluon routes, we have an ip; that must be R23 ip.
- For C1 & R22 you can do as you want; but keep in mind that a small mask and close ip will spare you some headache.
![level9-goal2done](https://user-images.githubusercontent.com/81954460/155990003-2bd89684-3929-455c-9db7-97b5537b6fa5.png)
Goal 3) --> Meson needs an internet connection, follow the steps.
![Screen Shot 2022-02-28 at 2 48 30 PM](https://user-images.githubusercontent.com/81954460/155995688-cbdf2acf-7b97-4f25-8117-25457dd162ed.png)
Goal 4) --> We need to establish communication between R13 & R21
- For that they must have the same mask and close ip, so I choose 40.0.0.1 & 40.0.0.2.
- For their routes (purple boxes) they must have the ip of the other.
- Goal 5 will be acheived at the same time.
![Screen Shot 2022-02-28 at 3 00 58 PM](https://user-images.githubusercontent.com/81954460/155996330-a00fd6ed-8171-4ac2-ba74-5c97d8d2d01b.png)
Goal 6) --> Internet for cation.
- Give to internet the network that cation belongs to and a mask of 24.
![Screen Shot 2022-02-28 at 3 07 15 PM](https://user-images.githubusercontent.com/81954460/155997441-36307a38-a903-4715-a725-aaf433a3024b.png)

DONE ✅

--------------
                                               * L E V E L (10) *
--------------
step 1)- 🧽
![level10blank](https://user-images.githubusercontent.com/81954460/156001121-53560402-fa41-476f-8e35-a5315b0eb070.png)
Goal 1) --> R11, H11 and R21 must have the same mask and ip within the same range. And put R11 ip in the right section of R21 and H11 routes.
![level10-goal1](https://user-images.githubusercontent.com/81954460/156001539-dd7e2a8d-1934-4177-a874-74568199460c.png)
Goal 2) --> R23 ip is already defined by client H4 routes.
- For R22 and H31, I did the same substraction as in level 8.
- H41 mask is 255.255.255.192, calculating how namy left from 192 till 255, 255 - 192 = 62 ip.
- I start from 170.135.223.129 --> 129 + 62 = 191, and I skip the following one just in case.
![goal2:3](https://user-images.githubusercontent.com/81954460/156004556-f76d9d03-6901-43e1-bd29-09c8a3da77b5.png)
![Screen Shot 2022-02-28 at 3 23 58 PM](https://user-images.githubusercontent.com/81954460/156004621-de44ffe0-492d-496e-8ce2-6d6d33dae678.png)

DONE ✅

If you have to remember 3 rules:
-Same mask if the same subnet (mask : the smaller the better)
-Close IP (no private ones)
-Blue boxes : closest router's IP in the right & default in the left (except for the internet)

🥳 Congratulation if you passed, and congrats for finishing this big ass tutorial 🫡.
