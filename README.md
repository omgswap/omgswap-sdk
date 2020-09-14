# OMGSwap SDK

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![npm version](https://img.shields.io/npm/v/@omgswap/sdk/latest.svg)](https://www.npmjs.com/package/@omgswap/sdk/v/latest)    
    
    
                    .=,.             _i.                    
                    -nos.          .%nv`                    
                     -nvv,        _nnv'                     
                      <vvns.    .%nnv>                      
                       {vvvv,  _nvvv>                       
                        {nvvvs|nvnv}                        
                        -vvvnvvvvvv`                        
                         -nvvvvvnv'                         
                          <vnvnvv>                          
                           - - -                            
                                                            
                         ._i=i<<_,.                         
                      .=uvnvnvvvoons_.                      
                    .<vnvvvvvvnvvnvvnn,.                    
                   _vvvvvnvnvnvvnvvnvnns,                   
                  _vvvvvnvvvvvvnvvvvvvvvv,                  
                 _vvvvvnvvnvnvnvvvnvnvnvnv,                 
                .vvnvnvvvn}"----"Ivvvvvvvvs.                
                )vvvvvvnv~        ~vnvnvnvn(                
               _nvvnvnv}`          -{vvvvvvv,               
               %vvnvvvv`            -vvnvnvn(               
              :vnvvvnv'              :nvvvvvn,              
              )vvvnvv}                {vnvnvv(              
              vvvnvvn'                =vvvvvns              
             .nvvvvnv                  vnvnvvv.             
             =vvnvnv(                  )vvvvnv;             
             )vvvvvv(                  )vvnvvn(             
             )vvnvnv;                  :vvvnvv(             
             vvvvvvv`                  .nvnvvns             
             vvvnvnv                    nvvvnvs             
             vvvvvvv                    nvnvvvv             
             vvvnvnv                    nvvvnvv             
             vvvvvvv                    nvvnvvv             
             {vnvnvn.                  .nvvvvnl             
             )vvvvvv;                  =vvnvnv(             
             )vvnvnv(                  )vvvvvv(             
             =vvvvvv(                  <vvnvnv;             
             .vnvnvnv                  vvvvvvv`             
              nvvvvvv;                =vnvnvnv              
              <vvnvnvs                %vvvvvv>              
              :vnvvvvn,              _nvnvnvn`              
               {vvnvnvs              vvvvvvv}               
               -nvvvvvvs            %nvvnvnv'               
                {vnvnvvvs.        .vvvvnvvv}                
                -vvvvvnvvv=,    _>vvvnvvvnv`                
                 :nvnvvvnvnnvvIvnvvnvvvnvv'                 
                  +vvvnvvvvvvvvnvvnvvnvvv'                  
                   -nvvvnvnvnvnvvvvvnvvv'                   
                    -{vvvvvvvvvvnvnvvv}`                    
                      -{nvnvnvnvvvvv}'                      
                        -^<IvvvvI>^`                        
                                            


In-depth documentation on this SDK is available soon at [omgswap.in](https://omgswap.in/).

## Running Tests

To run the tests, follow these steps. You must have at least node v10+ and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/omgswap/omgswap-sdk.git
```

Move into the omgswap-sdk working directory

```sh
cd omgswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
