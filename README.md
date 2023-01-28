libsol a usefull solidity usecases library
--------------------------------------------------

checkout the packages from npmjs
``` https://www.npmjs.com/package/libsol ```
run the following command in cli in your project location

``` npm i libsol ```

1. Greater number from Array of Multiple Numbers
---------------------------------------------------------------

import GreaterNumber library 

``` import "libsol/libraries/GreaterNumber.sol"; ```

using this library into your preoject fil

``` using GreaterNumber for uint; ```

Use the function where you need 
Will get maxNumber from given _ArrayOfNumbers parameter

``` uint MaxNumber = GreaterNumber.maxNumber(uint[] calldata _ArrayOfNumbers); ```