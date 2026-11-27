# phishies

# Getting Started

## Installation and Usage

To install, run `npm i phishies` or `npm i phishies -g` to install globally.

```
var phish = require('phishies')

//phish.aquarium(height, width)
phish.aquarium(5, 5) //generates a 5x5 aquarium

//phish.aquarium_sym(height, width)
phish.aquarium_sym(5, 5) //Same as above but uses symbols instead of emojis for better compatibility
```

`phish.aquarium(h,w)` putputs an array of the following form:

```
[ '　　　　　', '　🐡　　　', '　　　🐡🐠', '🐙🐡　🦑　', '　　🦀🌿　' ]
```

# Contributing

# Credits

This project was inspired entirely by https://botsin.space/@EmojiAquarium, source code found at https://gitlab.com/JoeSondow/fishies

# License

This module is licensed under the MIT+NOSLOP license.
