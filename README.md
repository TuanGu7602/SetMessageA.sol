# SetMessageA.sol
SetMessageA.sol8
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SetMessageA {
    string public message;
    function setA() public { message = "A"; }
}
