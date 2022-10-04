# jacuzz
// SPDX-License-Identifier: MIT
pragma solidity ^0.5.0;

contract Group4 {

    struct Bintainternational {
        string name;
        uint age;
        string class;
        string homeaddress;
        string sex;
        uint height;
        string genotype;
 }

 Bintainternational[] public biodata;

 function student(string memory _name, uint _age, string memory _class, string memory _homeaddress, 
 string memory _sex, uint _height, string memory _genotype) public {

     biodata.push(Bintainternational(_name, _age, _class, _homeaddress, _sex, _height, _genotype));

 }

}
