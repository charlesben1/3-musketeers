# cash

Cash is a currency converter written in JavaScript that enables the user to switch between 32 currencies.

## How do I install?

In order to use cash you first have to have Node.js installed and to go to to cash directory.
```sh
❯ cd cash
❯ npm install
```

## How do I use it ?

To make the converter work you need to launch the [index.js](https://github.com/charlesben1/3-musketeers/tree/master/cash/bin) and put the currencies that you want to work with.

In  [currencies.json](https://github.com/charlesben1/3-musketeers/tree/master/cash/lib) you'll find what currencies are usable and the syntax to follow

The first option is to get the amount of currency1 to currency2 the command is then:

```sh
❯ node bin/index.js <amount> <currency1> <currency2>
```


You can check the other options using:
```sh
❯ node bin/index.js --help
```

## License

This software is not under any license
