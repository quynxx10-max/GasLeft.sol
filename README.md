# GasLeft.sol
GasLeft.sol
pragma solidity ^0.8.20;
contract GasLeft {
    function getGas() public view returns(uint){
        return gasleft();
    }
}
