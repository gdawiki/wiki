# Scroll Speed Bug
---

Not to be confused with [Float Inaccuracy](Float-Inaccuracy) or [X position limit](X-Position-Limit).

Scroll Speed Bug is a side-effect from [float inaccuracy](Float-Inaccuracy) which causes the player to "scroll" (move) faster/slower than usual. 
Until 2.2 scroll speed bug happened on specific coordinates, speed, and TPS. After the update, TPS had been locked to 240 and now it's only related to current player velocity.

Scroll Speed Bug by itself is not an individual bug, but rather a side-effect. Nonetheless, this term has been generally accepted by the community.

This bug is closely related to [X position limit](X-Position-Limit) since it also affects movement on far coordinates.

## Effects
Scroll Speed Bug may make some cube jumps on far coordinates possible or impossible. 
Such as a quadruple spike jump on 1x speed is impossible in the first few hours of gameplay but may become possible in certain positions.

This bug may also make some wave gaps impossible due to wave not having diagonal movement anymore.