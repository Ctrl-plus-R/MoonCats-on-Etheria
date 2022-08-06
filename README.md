# MoonCats-on-Etheria
Build Code for a an Unofficial MoonCat 3d Model

# What's implemented yet?
There are only models for pure standing, stalking or sleeping cats. I will add more when people ask or when I am in the mood.

# Customize your cat
Change the config object at the beginning of the file. You can set pose (String), expression (String), size (String), rotation (Number, multiples of 30) and colors (Number, depending on the selected color palette).

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

# Build it
Copy the whole code into the [EtheriaBuilder](https://etheriabuilder.com/).

Try with a height of 128. before you put your cat on chain, however, you should test how far you can reduce the height to save data and gas. this depends on your config.

It's up to you which pallete you use. Smaller palletes are cheaper to build. But you may not find all the colors you need.