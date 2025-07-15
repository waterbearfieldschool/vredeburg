---
title: "Off-Grid Power"
date: 2020-06-21T08:04
thumb: "power.png"
description: "Generating and using electrical power off-grid."
tags: 
    - popular
    - sample
---

# Notes on making a charger circuit

Making a 12V solar charger with LM317 video [here](https://www.youtube.com/watch?v=xvpqFcUm-lE)

Lindsay video [here](https://www.youtube.com/watch?v=QY0WfFA3ju4)

design [here](http://imajeenyus.com/electronics/20160530_adjustable_current_source/index.shtml)

Auto cutoff [here](https://www.youtube.com/watch?v=MZ_6Wc563XE)

![](/assets/img/auto_cut.png)

Cutoff circuit diagram [here](https://www.rcpano.net/2019/10/09/12v-lead-acid-battery-charging-circuit-with-auto-cut-off-diy-pb-battery-charger/#google_vignette)


ACS712 [here](https://www.amazon.com/HiLetgo-ACS712-Current-Sensor-Module/dp/B07SPRL8DL/ref=asc_df_B07SPRL8DL?mcid=1e273d1686c83d518d00fe34c1c08249&tag=hyprod-20&linkCode=df0&hvadid=693071814664&hvpos=&hvnetw=g&hvrand=5715915006728785760&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9002061&hvtargid=pla-1953911807751&psc=1&hvocijid=5715915006728785760-B07SPRL8DL-&hvexpln=0)

LM317 datasheet [here](https://www.ti.com/lit/an/snva581/snva581.pdf?ts=1750976004509&ref_url=https%253A%252F%252Fwww.google.com%252F)

[charging circuit with lm317](https://electronics.stackexchange.com/questions/503642/lithium-ion-battery-charger-using-lm317)

[lm317 battery charging tutorial](https://www.eleccircuit.com/the-most-lead-acid-battery-charger-circuit-by-lm317/)

![](/assets/img/lm317_design.png)

Adjustible DC-DC booster circuit [here](https://www.rcpano.net/2022/10/22/adjustable-dc-to-dc-booster-circuit-5-15v-to-max-40v/#google_vignette)

This video uses lm317 for solar charging, claims better than standard equipment [https://www.youtube.com/watch?v=lOxJru8VOuU](https://www.youtube.com/watch?v=lOxJru8VOuU)

And associated circuit diagram [here](https://youtu.be/lOxJru8VOuU?t=253)

auto cutoff, a little neater [here](https://www.youtube.com/watch?v=QGTvWTN0K_Y)

best of both worlds [here](https://www.eleccircuit.com/the-most-lead-acid-battery-charger-circuit-by-lm317/)

suggesting here that lm317 already has inherent current limiting characteristic -- [discussion](https://electronics.stackexchange.com/questions/311633/lm317-sealed-lead-acid-charger)

app note on lm317 [here](https://www.ti.com/lit/ds/symlink/lm317.pdf)

circuit digest article [here](https://circuitdigest.com/microcontroller-projects/12v-battery-charger-circuit-diagram-using-lm317)

Focus on this one:

![](/assets/img/dual.png)




