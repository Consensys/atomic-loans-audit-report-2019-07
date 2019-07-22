```
$ solium -d ethereum/contracts/ --plugin security --no-soliumrc --no-soliumignore > solium-atl-ethereum.txt
$ cat solium-atl-ethereum.txt 

ethereum/contracts/DSMath.sol
  62:4    error    "rpow": Avoid assigning to function parameters.    security/no-assign-params

ethereum/contracts/Funds.sol
  219:12    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

ethereum/contracts/Loans.sol
  203:29    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  257:13    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  275:13    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  288:13    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  302:16    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  328:10    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  336:20    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

ethereum/contracts/Sales.sol
  175:28    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  176:28    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  194:13    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  219:10    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  260:10    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  281:10    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

✖ 1 error, 14 warnings found.


$ solium -d oracles/contracts/ --plugin security --no-soliumrc --no-soliumignore > solium-atl-oracles.txt
$ cat solium-atl-oracles.txt 

oracles/contracts/Buffer.sol
  56:4      error    "init": Avoid assigning to function parameters.     security/no-assign-params
  62:8      error    Avoid using Inline Assembly.                        security/no-inline-assembly
  103:8     error    Avoid using Inline Assembly.                        security/no-inline-assembly
  128:8     error    Avoid using Inline Assembly.                        security/no-inline-assembly
  144:12    error    Avoid using Inline Assembly.                        security/no-inline-assembly
  153:8     error    Avoid using Inline Assembly.                        security/no-inline-assembly
  198:8     error    Avoid using Inline Assembly.                        security/no-inline-assembly
  234:4     error    "write": Avoid assigning to function parameters.    security/no-assign-params
  242:8     error    Avoid using Inline Assembly.                        security/no-inline-assembly
  305:8     error    Avoid using Inline Assembly.                        security/no-inline-assembly

oracles/contracts/DSMath.sol
  124:4    error    "rpow": Avoid assigning to function parameters.    security/no-assign-params

oracles/contracts/DSValue.sol
  9:4     error    No visibility specified explicitly for peek function.    security/enforce-explicit-visibility
  13:4    error    No visibility specified explicitly for read function.    security/enforce-explicit-visibility
  19:4    error    No visibility specified explicitly for poke function.    security/enforce-explicit-visibility

oracles/contracts/Medianizer.sol
  22:4     error    No visibility specified explicitly for set function.         security/enforce-explicit-visibility
  45:24    error    Consider using 'revert()' in place of deprecated 'throw'.    security/no-throw
  47:43    error    Consider using 'revert()' in place of deprecated 'throw'.    security/no-throw
  58:4     error    No visibility specified explicitly for setMax function.      security/enforce-explicit-visibility
  68:4     error    No visibility specified explicitly for push function.        security/enforce-explicit-visibility
  81:4     error    No visibility specified explicitly for poke function.        security/enforce-explicit-visibility
  85:4     error    No visibility specified explicitly for poke function.        security/enforce-explicit-visibility
  89:4     error    No visibility specified explicitly for compute function.     security/enforce-explicit-visibility

oracles/contracts/Oracle.sol
  29:36    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  35:15    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  53:4     error      No visibility specified explicitly for pack function.    security/enforce-explicit-visibility
  57:4     error      No visibility specified explicitly for pack function.    security/enforce-explicit-visibility
  58:23    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  61:21    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  73:21    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  87:12    warning    Avoid using low-level function 'call'.                   security/no-low-level-calls

oracles/contracts/chainlink/ChainLink.sol
  22:4     error      No visibility specified explicitly for pack function.    security/enforce-explicit-visibility
  23:23    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  27:21    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  37:21    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  41:21    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members
  48:37    warning    Avoid using 'now' (alias to 'block.timestamp').          security/no-block-members

oracles/contracts/oraclize/Oraclize.sol
  27:4     error      No visibility specified explicitly for pack function.          security/enforce-explicit-visibility
  31:4     error      No visibility specified explicitly for pack function.          security/enforce-explicit-visibility
  32:23    warning    Avoid using 'now' (alias to 'block.timestamp').                security/no-block-members
  37:21    warning    Avoid using 'now' (alias to 'block.timestamp').                security/no-block-members
  46:4     error      No visibility specified explicitly for __callback function.    security/enforce-explicit-visibility
  49:25    warning    Avoid using 'now' (alias to 'block.timestamp').                security/no-block-members

oracles/contracts/oraclize/OraclizeAPI.sol
  93:6      error    Code is unreachable.                                                    security/no-unreachable-code
  144:6     error    Code is unreachable.                                                    security/no-unreachable-code
  544:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  649:4     error    "parseInt": Avoid assigning to function parameters.                     security/no-assign-params
  667:4     error    "uint2str": Avoid assigning to function parameters.                     security/no-assign-params
  718:4     error    "oraclize_newRandomDSQuery": Avoid assigning to function parameters.    security/no-assign-params
  727:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  737:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  749:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  787:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  922:12    error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  946:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  974:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  1004:8    error    Avoid using Inline Assembly.                                            security/no-inline-assembly

oracles/contracts/oraclize/OraclizeAPITesting.sol
  93:6      error    Code is unreachable.                                                    security/no-unreachable-code
  144:6     error    Code is unreachable.                                                    security/no-unreachable-code
  548:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  653:4     error    "parseInt": Avoid assigning to function parameters.                     security/no-assign-params
  671:4     error    "uint2str": Avoid assigning to function parameters.                     security/no-assign-params
  722:4     error    "oraclize_newRandomDSQuery": Avoid assigning to function parameters.    security/no-assign-params
  731:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  741:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  753:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  791:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  926:12    error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  950:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  978:8     error    Avoid using Inline Assembly.                                            security/no-inline-assembly
  1008:8    error    Avoid using Inline Assembly.                                            security/no-inline-assembly

✖ 56 errors, 14 warnings found.

```
