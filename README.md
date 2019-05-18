# Orgasm
[![npm version](https://badge.fury.io/js/orgasm.svg)](https://badge.fury.io/js/orgasm)

### ⚡️Official API Documentation ⛈

## Installation

```
npm i orgasm
```

### Usage
```
'use strict';

const {
    validation: {
        getIsValidAddress,
    },
    formatting: {
        getAmountNumber
    }
} = require( 'orgasm' );



const amount = '2.232323666';

const amountNumber = getAmountNumber( amount );
// amountNumber is 2.23232367


const address = '3J98t1WpEZ73CNmQviecrnyiWrnqRhWNLy';

const isValidAddress = getIsValidAddress( address );
// isValidAddress is true
```

