Total Time: 12 Hours

<h2>Summary</h2>
A horizontal spinner battle bot that also happens to use AC plasma flames as its special weapon. It has high torque motors and a small body made of PLA.

![image](https://github.com/user-attachments/assets/9ab81ab9-d3c6-40a0-ba9d-09f0a6d16b83)


<h2>Main Features</h2>
The body is thick PLA-walled while still being lightweight. The wheels will be coated to increase grip, with screws (NOT GLUE) to hold it together! Also because we need to maintain and disassemble it constantly. Instead of going with the common N20 motors, I decided to go with stronger, larger motors to move the relatively large weight of the bot. I went with a 2200KV A2212 Brushless Motor due to it's low cost as well as good specs. It'll work great as the "offhand". And finally, the main deal. I went with a 15-20KV AC transformer module to be able to make large arcs, or plasma fire. 

<h2>June 16th</h2>
I thought of a general guiding design today and worked on the parts list. I just get an overview of what I'm thinking. This design will probably change over time. Overall, just generally diagramming and creating a good view over as well as picking parts.

![2025-06-20 22-52](https://github.com/user-attachments/assets/a1c5aadd-d878-4a9b-8744-af58bcdfe70a)
Time Spent: ~1 Hour

<h2>June 17th</h2>
Today I made a ton of progress!

First, I sketched out an idea of what I wanted the battlebot to look like, just so I could have a reference. I know it looks a little messy, but it helps to get a visualization in my head so I can get to actually designing the thing.
![2025-06-17 18-44](https://github.com/user-attachments/assets/62db8e53-1df1-4ce7-9622-772ee240605a)

After that, I worked on the wiring diagram. It was a little tough due to all the different voltages and connectors and the complicated wiring overall, but I got it. (It didn't help that aliexpress parts can be quite vague). It has strong high torque motor for the wheels as well as a budget brushless motor for the spinner. The transformer is going to be the main showpiece though, which is controlled by a relay. I went with a relay over a MOSFET due to the low likelyhood of it failing which is a big deal with a battlebot.

![CleanShot 2025-06-17 at 18 45 26](https://github.com/user-attachments/assets/08987e5e-d7e8-4cd7-bfce-2de6313aa0fc)

I also made the initial CAD. The base, the wheels, and the offhand weapon were all roughly designed today. Since the horizontal spinner is easily moddable, I can replace it right after it gets worn out which is great. I can scale it to be stronger but less durable, weaker, but longer lasting, and whatever configuration I want! 
![CleanShot 2025-06-17 at 21 32 10](https://github.com/user-attachments/assets/f835d504-9d7a-43be-b627-e2dff5624704)

Time Spent: ~5 Hours

<h2>June 18th</h2>
I spent a lot of time polishing and finishing up the final design for the battle bot. I was thinking about adding bare 8 gauge copper wire to make it easy to change the arc length but I decided that stripping thinner wire and tinning it would be a much cheaper option. It better to just use random stranded copper wire and encase it with solder after testing what distance makes the best arc. I added the top lid as well as routing on the inside for the wires to go in order to minimize any messiness. It's really taking shape now which is nice. I added a graphic of an atom for extra pizzaz. I'm going to paint it so it stands out as well.

![CleanShot 2025-06-18 at 18 31 20](https://github.com/user-attachments/assets/ee4039d5-b43d-4c38-99ba-9a323fc0d5de)![CleanShot 2025-06-18 at 18 33 31](https://github.com/user-attachments/assets/09480184-ef49-4c8d-9037-c19027891ab4)

After careful consideration, I felt that the original horizontal spinner weapon would wear quickly and do little damage, so I designed a couple more weapons. The spinner just gave me a feeling that if I touched it it wouldn't hurt.
![CleanShot 2025-06-18 at 18 55 50](https://github.com/user-attachments/assets/e0a6138e-08f3-4d7b-8594-115dcdf9824d)


I ended up going with the one that you can currently see on the battlebot due to a good balance between many spikes and being sturdy. I learned from a peer that you want enough spikes but not too much because it has to build speed in between each hit.

I also finished uploading, the BOM, and the README which is good because it's starting to solidify now. I also tried my absolute best to BOM-optimize which was really hard with the transmitter and reciever. However, I got it down as low as possible in this scenario and it should last. I'm a bit scared of the Li-Po batteries lasting but I can always replace them so it'll be fine.

After some constructive criticism from peers, I decided to move the wheels inward so they would be more protected. It was a problem that the wheels could snap off if not closer to the inside.
![CleanShot 2025-06-18 at 21 02 55](https://github.com/user-attachments/assets/574d3df3-d768-4c26-9aa1-5335f85ce530)
I also decided to swap PETG for PLA due to superior impact resistance although I'd have to sacrifice some heat resistance as well.
I then changed the weapon a bit to be stronger yet still fulfill its purpose of guarding the plasma arcs by adding heavy hitters as well as making it thicker. Adding two larger hitters is a good change as it increases the probability of doing real damge.

A project I was working on previously was requested to have the wiring diagram updated with the images of the complicated parts to make it clearer, so I quickly decided to do the same for this project as well. This will definitely be better to look at the exact pins and where to put them. ![image](https://github.com/user-attachments/assets/5b7879b0-f4c6-4e0e-a0ba-518b791f2e2b)

This is the final build. Overall, I'm really proud of all the work I put in as my first battlebot and I hope to surprise family and friends with my plasma fire!


![CleanShot 2025-06-18 at 21 14 24](https://github.com/user-attachments/assets/acc2ad7a-5891-42f9-bffc-6b50132fe27a)

Time Spent: ~6 Hours


