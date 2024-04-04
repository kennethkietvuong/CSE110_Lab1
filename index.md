# Hey there 👋, I'm Kenneth.

<div style="text-align: center;">
    <img src="images/myself.jpg" width="250" height="">
</div>

## About Me:
I'm a **third year** undergrad student majoring in ***Computer Engineering*** that is interested in both the *software and hardware application of systems*. I'm more invested and interested in learning more about the hardware side of things (dealing with all of the circuitry, components, and such) when compared to all of the theory/abstract classes that I have took so far in the side of CS.

### Hobbies
* Playing video games
* Doing small and simple arduino projects
* Going out on long walks

### Programming Rankings
Here's my ranking so far of the programming languages I've experienced so far:
1. Python/Arduino
2. C++
3. Java
4. C
5. Assembly


### Favorite Programming Quotes
> There are 2 types of people. Those who do backups and those who will do backups.

> A good programmer looks both ways before crossing a one way street...then gets hit by a car that falls out of the sky.

> Give a man a program, and he'll be frustrated for a day. Teach a man to program, and he'll be frustrated for a lifetime.

### Favorite Block of Code
My favorite block of code is the fast inverse square root from Quake! I thought that the comments were funny and ~~amusing~~ interesting  😄 . Check out the wikipedia [here](https://en.wikipedia.org/wiki/Fast_inverse_square_root){:target="_blank"}!
```c
float Q_rsqrt(float number)
{
  long i;
  float x2, y;
  const float threehalfs = 1.5F;

  x2 = number * 0.5F;
  y  = number;
  i  = * ( long * ) &y;                       // evil floating point bit level hacking
  i  = 0x5f3759df - ( i >> 1 );               // what the fuck?
  y  = * ( float * ) &i;
  y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
  // y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

  return y;
}
```

### Contact Me
Email: <k1vuong@ucsd.edu>

Github: [https://github.com/kennethkietvuong](https://github.com/kennethkietvuong){:target="_blank"}

### Random Images
I have a *bunch* of random images that are lying around on my computer. What better way to deal with these images than to share them [here](random.md)?

### Goals
- [x] Reach out to others in CSE 110
- [ ] Learn and get exposed to software engineering in CSE 110
- [ ] Pass CSE 110