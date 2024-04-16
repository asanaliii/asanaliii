// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloWorld {
  uint public voteCount;
  function vote() public
  {
    voteCount = voteCount + 1;
  }
  function getVoteCount() public view returns (uint){
    return voteCount;
  }
}
