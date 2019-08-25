# The official editor for [Code in the Dark](https://github.com/codeinthedark/codeinthedark.github.io)
*Read more about the Code in the Dark competition [here](https://github.com/codeinthedark/codeinthedark.github.io)*

![image](https://cloud.githubusercontent.com/assets/688415/11479175/f3aedfbe-9790-11e5-9ad9-ce930fe5a3a8.png)

## How to Use
* Add round-layouts in `assets/rounds/`.
* Add html-files in `assets/instructions` with information about the extra assets and their dimensions.
* Add any extra assets (e.g. images) that are required to build the page in the `assets/` folder.

Here's how to install the dependencies:
```bash
$ npm ci
```

To build the editor, run:
```bash
$ npm run build
```

To start the competition, run:
```bash
$ npm start
```

To start new round:  
`Alt/Option` + `Shift` + `num`, where `num` — round`s num  

**OR**  

Run `startRound(num)` in browser console, where `num` — round`s num

## Developing
```bash
$ npm run dev
```

## Contributing
Contributions to the editor welcome. If you've fixed a bug or implemented a cool new feature that you would like to share, please feel free to open a pull request here.
