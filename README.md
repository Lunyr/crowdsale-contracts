# Lunyr Contracts

This is the official repository for the crowdsale of Lunyr tokens.


We use SafeMath.sol and ERC20.sol from Zeppelin (thanks!)<br>
NewToken.sol is an example of a new token that we might upgrade to.<br>

We have 1200+ lines of tests. There are two test files:<br>
1. One tests the wallet<br>
2. The other one tests the crowd-sale token contracts.<br>

Instructions<br>
-------------<br>
1. Run npm install<br>
1. Run testrpc<br>
2. Run truffle test<br>

The testrpc command we use is

testrpc --testnet --account=0x1024102410241024102410241024102410241024102410241024102410241020,10000000000000000000000000 --account=0x1024102410241024102410241024102410241024102410241024102410241021,10000000000000000000000000 --account=0x1024102410241024102410241024102410241024102410241024102410241022,10000000000000000000000000 --account=0x1024102410241024102410241024102410241024102410241024102410241023,10000000000000000000000000 --account=0x1024102410241024102410241024102410241024102410241024102410241024,10000000000000000000000000 --debug

If you don't want to run all the tests, you can just run individual ones

truffle test ./test/LunyrToken.js