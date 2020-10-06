# Snapshot report for `test/number-literal-case.js`

The actual snapshot is saved in `number-literal-case.js.snap`.

Generated by [AVA](https://avajs.dev).

## number-literal-case - #1

> Snapshot 1

    `␊
    Input:␊
      1 | console.log(BigInt(0B10 + 1.2E+3) + 0XdeEd_Beefn)␊
    ␊
    Output:␊
      1 | console.log(BigInt(0b10 + 1.2e+3) + 0xDEED_BEEFn)␊
    ␊
    Error 1/3:␊
    > 1 | console.log(BigInt(0B10 + 1.2E+3) + 0XdeEd_Beefn)␊
        |                    ^^^^ Invalid number literal casing.␊
    Error 2/3:␊
    > 1 | console.log(BigInt(0B10 + 1.2E+3) + 0XdeEd_Beefn)␊
        |                           ^^^^^^ Invalid number literal casing.␊
    Error 3/3:␊
    > 1 | console.log(BigInt(0B10 + 1.2E+3) + 0XdeEd_Beefn)␊
        |                                     ^^^^^^^^^^^^ Invalid number literal casing.␊
    `