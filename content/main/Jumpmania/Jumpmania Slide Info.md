---
title: Jumpmania Slide Info
tags: 
aliases:
---
### Details on sliding in jumpmania.

The slide has two main functions:
- Stick to walls/ceilings
- Maintain your momentum
	- The slide has less friction than moving in the air and much less than moving on the ground.

There is no need to release the slide button between slides unless you deliberately want to be running on the ground instead of sliding, as the slide has zero effect on air movement.

When you start a slide, all of your velocity *parallel* to the slide direction (based on the surface you are sliding on) is maintained. Any velocity not parallel to the slide direction is ignored and discarded. If you are *already sliding* and reach a slope in your path, as long as the change in angle is 45 degrees or less, you will maintain 100% of your speed. 

*Example of maximizing velocity retention into slide, from tutorial level:*

![[Pasted image 20251117214901.png|500]]

In addition to this, the slide applies a small speed boost, calculated by:
- If you begin a slide while dashing, there is a minimum slide speed which is applied. If your speed parallel to the surface is greater than this, this boost is effectively ignored.
- If you start a slide while *not* dashing, you instead receive a multiplier to your speed (or an addition of 80 speed if you are going slow enough that that is greater than the multiplier.) This multiplier ranges from 1.25 to 1.1, getting smaller as you go faster. It is at 1.25x at 600 speed or less (a bit faster than dashing), and linearly reduces until it reaches 1.1x at 2000 speed.

So to go fast with sliding, you need to optimize:
- The speed you carry into the slides.
- The number of slides you start.
- Reducing time spent in the air.
The main way to start additional slides without dashing is jumping, for example you are sliding across flat ground, are about to reach a 45 degree slope, you can jump onto that slope instead of sliding into it, and you will receive the multiplier. If you are going fast enough, this multiplier will overcome any speed lost from being in the air and not receiving 100% speed preservation due to slamming into the slope.

*Example of jumping to start an additional slide, from tutorial level:*

![[Pasted image 20251117215022.png|500]]