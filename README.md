# Perlin noise
https://user-images.githubusercontent.com/103655830/167398934-4c8f0388-2f19-4f95-864a-785ae6b0663a.mp4

This vjass library is for working with two-dimensional perlin noise. Depends on the [LibReal2D](https://github.com/Vlod-github/Real2D/blob/master/source/LibReal2D.cjass) library.
## API
```scala
// Create noise. seed = -1 for random
Perlin per = Perlin.create(integer octaves, integer seed)

// Delete an object
per.destroy()

// Reinitialize noise
per.reinit(integer seed)

// Get the value at the point
per.get(real x, real y) // x,y in the range [0,1]

// Get an array filled with noise
Real2D map = per.fill(Real2D.create(integer length, integer width))
```
## Why is this necessary?
https://user-images.githubusercontent.com/103655830/167401797-d5e1ab79-8fdd-45ca-8da4-8d294153ef8e.mp4

https://user-images.githubusercontent.com/103655830/167401998-9329fa17-b243-4a2c-8578-c2aac26cd8fe.mp4

https://user-images.githubusercontent.com/103655830/167402098-793b9c4d-3b99-4a74-b8e7-76d5531bae8f.mp4

https://user-images.githubusercontent.com/103655830/167402120-13760a24-36b7-4875-b5e8-457e15999feb.mp4
