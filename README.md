# five.js

A library to overcomplicate `5`.

[![Build Status](https://travis-ci.org/jackdcrawford/five.svg?branch=master)](https://travis-ci.org/jackdcrawford/five)
[![Code Climate](https://codeclimate.com/github/jackdcrawford/five.png)](https://codeclimate.com/github/jackdcrawford/five)
[![Test Coverage](https://codeclimate.com/github/jackdcrawford/five/coverage.png)](https://codeclimate.com/github/jackdcrawford/five)

<img src="https://cldup.com/kwFz0lhg1u.png" width="300" alt="logo" />

DONATE: [Give us five](https://www.paypal.me/fivejs/5/)

> *Seriously, we'll be printing stickers and mailing to all contributors of the project. All remaining money will be passed on to a charity.*

### Usage
##### Require the module
```javascript
var five = require('five');
```

##### In the browser
```html
<script type="text/javascript" src="./five.js"></script>
```

##### Basic 5
```javascript
five(); // 5
```

##### Addition
```javascript
five() + five(); // 10
```

##### Multiplication
```javascript
five() * five(); // 25
```

##### Division
```javascript
five() / five(); // 1
```

##### Different sorts of 5
```javascript
five.upHigh() // ⁵
five.downLow() // ₅
five.tooSlow() // 5, with a ~500 millisecond delay
five.roman() // V
five.morseCode() // .....
five.negative() // -5
five.loud() // FIVE
five.loud('piglatin') // IVEFAY
five.smooth() // S
five.mdFive() // 30056e1cab7a61d256fc8edd970d14f5
```

##### 5 goes multilingual
```javascript
five.arabic() // خمسة
five.azerbaijani() // beş
five.basque() // bost
five.belarusian() // пяць
five.bosnian() // pet
five.bulgarian() // пет
five.catalan() // cinc
five.chinese() // 五
five.choctaw() // tahlapi
five.croatian() // pet
five.czech() // pět
five.dothraki() // mek
five.dovah() // hen
five.dutch() // vijf
five.elvish() // lempe
five.english() // Five
five.estonian() // viis
five.finnish() // viisi
five.french() // cinq
five.german() // fünf
five.greek() // πέντε
five.hebrew() // חמש
five.hindi() // पांच
five.hungarian() // öt
five.icelandic() // fimm
five.indonesian() // lima
five.irish() // cúig
five.italian() // cinque
five.japanese() // 五
five.kannada() // ಐದು
five.klingon() // vagh
five.korean() // 오
five.latin() // quinque
five.latvian() // pieci
five.lithuanian() // penki
five.mongolian() // таван
five.norwegian() // fem
five.persian() // پنج
five.piglatin() // ivefay
five.polish() // pięć
five.portuguese() // cinco
five.romanian() // cinci
five.russian() // пять
five.serbian() // pet
five.slovakian() // päť
five.slovenian() // pet
five.spanish() // cinco
five.swedish() // fem
five.tamil() // ஐந்து
five.telugu() // ఐదు
five.thai() // ห้า
five.turkish() // beş
five.ukrainian() // п’ять
five.welsh() // pump
```

##### Different radices
```javascript
five.binary(); // 101
five.octal(); // 5
five.hex(); // 5
five.base(4); // 11
five.base(3); // 12
```

##### Assertion
```javascript
five.isFive(10); // false
```

##### Filter, Map and Reduce
```javascript
five.filter([5, true, 5]); // [5, 5]
five.map([1, 2, 3]); // [5, 5, 5]
five.reduce([1, 2, 3]); // 5
```

##### Novelty
```javascript
five.fab(); // ['Juwan Howard','Ray Jackson','Jimmy King','Jalen Rose','Chris Webber']
five.jackson(); // ['Jackie','Tito','Jermaine','Marlon','Michael']
five.luniz(); // ‘I Got 5 on It’
```

##### Rotation
```javascript
five.rot("five.js"); //"knaj.ox"
```

##### Asynchronous Usage
```javascript
five.async(function(err, five) {
	// five === 5
});

five.promise().then(function (five) {
  // five === 5
})
```

##### Unicode
```javascript
five.oclock(); // '🕔'
```

### Development
##### The code
All of the logic & heavy lifting is achieved in one self-contained file:
```
./five.js
```

##### Tests
```
npm test
```
### License
MIT
