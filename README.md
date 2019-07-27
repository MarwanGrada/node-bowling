
# node-bowling


# install

    npm install bowling

# test

    npm test

# usage

    var bowl = require('bowling')


    var aCompleteGame = ['81','9-','9/','71','9-','X','90','70','x','7-'],
        result

    result = bowl(aCompleteGame)

    console.log(result)

    /*
    [
      {outcome: '81', cumulative: 9, score: 9},
      {outcome: '9-', cumulative: 18, score: 9},
      {outcome: '9/', cumulative: 35, score: 17},
      {outcome: '71', cumulative: 43, score: 8},
      {outcome: '9-', cumulative: 52, score: 9},
      {outcome: 'X', cumulative: 71, score: 19},
      {outcome: '9-', cumulative: 80, score: 9},
      {outcome: '7-', cumulative: 87, score: 7},
      {outcome: 'X', cumulative: 104, score: 17},
      {outcome: '7-', cumulative: 111, score: 7}
    ]
    */


# notes

- miss: `0` or `-`
- strike: `x` or `X`
- foul: `f` or `F`
