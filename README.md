# MoonCats-on-Etheria
Build Code for a an Unofficial MoonCat 3d Model

# What's implemented yet?
There are only models for pure standing, stalking or sleeping cats. I will add more if people request it or if I’m in the mood.

# How to ...?
Change the config object at the beginning of the file. You can set pose (String), expression (String), size (String), rotation (multiples of 30) and colors.

Note that cats rotated by (multiples of 60) + 30 degrees look different from those rotated by multiples of 60 only.

```
let config = {
  pose: 'sleeping', // 'standing', 'sleeping', 'stalking
  expression: 'grumpy', // 'smiling', 'shy', 'grumpy', 'pouting'
  size: 's', // 's', 'm', 'l'
  rotation: 30, // {0, 30, 60, ..., 330}
  colors: {
    fur: 5,
    paws: 6,
    expression: 9,
    eyes: 11
  }
}
```