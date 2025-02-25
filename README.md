

# Christmas Star PCB Project 🎄

## Overview
This is a Christmas-themed star PCB with two major groups of LEDs:

- **Group 1**: 3 LEDs for each of the 6 subgroups (star main led brsnches).
- **Group 2**: 2 LEDs for each of the 5 subgroups.(star edges)

The initial idea was to create a snowflake, but due to size and routing constraints, the project evolved into a star design instead.

## The Story Behind the Design
At first, I wanted to create a snowflake design. I had the idea ready and even prepared the schematic, but when it came to fitting the 28 NeoPixels onto the small PCB, things didn’t go as planned. The size constraints made it impossible to route everything properly, so I had to make the tough decision to switch to a star design.

After this, I had to spend about 5-6 hours manually routing the PCB because the autorouter kept failing. The problem was that whenever I tried to add manual routing in easyeda std after auto routig then run auto again everything used to get messed up, my earlier manual routing work would disappear. It was super frustrating, but I learned a lot through trial and error.

Additionally, I had to make several changes to the Bill of Materials (BOM) because some of the parts I needed were unavailable. This led me to switch from EasyEDA Pro to STF for routing. It wasn’t easy, but I eventually got it all working.

the wokwwi simulation curently has a simple code as the one i wrte as the advancedversion has errors once i fix it for appearking disappearing lights il update it
## Tools Used
- **EasyEDA Pro**: For creating the schematic and doing the initial PCB layout.
- **STF**: For continued routing and adjustments after I switched.
- **Manual Routing**: To make sure everything fit and worked.

## Challenges Faced
- **Design Constraints**: The NeoPixels wouldn’t fit in the original snowflake design, so I had to pivot to a star.
- **Routing Failures**: The autorouter didn’t work well, so I had to manually route everything, which was time-consuming. that too in easy eda std so time didnt get recorded
- **Part Availability**: I had to adjust the BOM multiple times due to parts being unavailable.

## Links
the wokwii fie for cdeto be flashed-https://wokwi.com/projects/421112349242722305
- [Schematic Image](link-to-image)![Screenshot 2025-01-23 235928](https://github.com/user-attachments/assets/b403be45-2205-40b8-a603-0d3627c855b3)


- [PCB Image](link-to-image)![Screenshot 2025-01-25 231714](https://github.com/user-attachments/assets/38688f33-56b9-4158-908f-eaa0531cb309)
- [Routing Image](link-to-image)![Screenshot 2025-01-29 143815](https://github.com/user-attachments/assets/461f8641-0a42-432a-847e-3cd77e070e4b)

![Screenshot 2025-01-29 212148](https://github.com/user-attachments/assets/e39042f4-fc50-407f-899b-02c97b95cf79)
