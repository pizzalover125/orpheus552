---
title: "orpheus552"
author: "pizzalover125"
description: "A tiny, but better devboard. "
created_at: "2025-07-31"
---
Hours Spent: 3

## 7/31/25
I wanted to speedrun yet another devboard. So I did just that! This is an improvement upon Orpheus85, which had far less functionality and was even a bit more expensive. I went with the CH552, a far faster chip than last time. It also has full USB implementation. I began with the schematic. I copied the USB-C circutry from last time and just pasted it in. For power, I just used this cheap generic AP2112K-3.3. For the boot button, I was originally planning to make users use a screwdriver, but it turned out I had more space with 5 pins on each side, so I just used an SMD button, which took me forever to find for some reason. Here is the final product:
<img width="1014" height="541" alt="image" src="https://github.com/user-attachments/assets/28874022-f2dc-4ac4-8e71-55e0ee23964f" />

Ok then I went on to the PCB. I was originally going with a much smaller design with far smaller tolerances. However, I just routed some stuff and then made the space I had bigger. I also added ground planes. This is the final product (it looks pretty janky but it is 25 min till the deadline lol).
<img width="359" height="423" alt="image" src="https://github.com/user-attachments/assets/efe687c0-7efb-4f0e-80d6-fa19091d678d" />
