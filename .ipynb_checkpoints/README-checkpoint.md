# week20_solidity
In this project, test Ethreum is transferred to various account addresses via equal distribution, percentage distribution and vested equity.

## Tools/ Technologies
- Solidity (v0.5.0)
- Ganache
- Metamask
- Remix IDE
- Gitbash
- GitHub
- Windows 10 64-bit

## Notebooks created
- AssociateProfitSplitter
- TieredProfitSplitter
- DeferredEquityPlan

## Account used to send Ether
- 0xB44F86125615Cd27d1af4962acCa9801D6afBBf1

### Associate profit splitter:
Ethereum is equally divided among three employees. The following are the recipient account addresses. As seen on the screenshots, each of the addresses got incremented by 1 Ether.
- employee_one= 0x943C6A0937518E5ffF5c736f285CF90b0829C58c
- employee_two= 0xa4e7f477170cA7794Ca5c68C55E1F7f31e7a4bD4
- employee_three= 0x6e3Cf25b2ceb9FcbA13714beb27716C80EAa9171

### Tiered profit splitter:
Based on the employee's position, a percentage of Ether is earned. The following are the recipient account addresses. As seen on the screenshots, the addresses received 6, 2.5, 1.5 Ethers respectively.
- employee_one= 0xcF463435c028c07a3AB28C8ee7e8691b1abe0661
- employee_two= 0xc5C1ac206785981721744046531339DaDe2Ade83
- employee_three= 0x96D169f078Fca3bdB2D7FbB1842644876edFBc4e

### Deferred Equity plan:
Thousand shares are distributed to the employee equally over a period of 4 years. This code did not work when tried with `fastforward` function.
- employee address= 0x7A9E165E1F653Ab0194d6575C9Af599f222b2173

## Problems faced
- The 'DeferredEquityPlan' got deployed onto the blockchain, however, the shares did not get distributed.

## Contributors
- Satheesh Narasimman

## People who helped
- Michael Tang, Bootcamp tutor

## References
- https://ucb.bootcampcontent.com/UCB-Coding-Bootcamp/ucb-sfc-fin-pt-08-2020-u-c/tree/master/01-Lessons/20-Solidity/4/Activities