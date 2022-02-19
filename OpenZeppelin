// SPDX-License-Identifier: MIT
pragma solidity ^0.8.6;

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/extensions/ERC721Enumerable.sol";

contract NftExample is ERC721Enumerable {

    constructor() ERC721("NFT-Example", "NEX") public {}

    function mintNft(address receiver,uint newNftTokenId) public {

        _mint(receiver, newNftTokenId);
    }
}
