# Hermesfull
Smart contrat for encrypted communications

The idea is to implement a network of blockchain-smart contract nodes on existing satellites and to interconnect them so that it is a bridge between the space station and the ground networks, i.e. "5G- Cloud- Fog Computing-IoT devices of NASA and other space organizations".
The focus is on the intelligent contract that will be the key in this decentralized communication, this will provide resilience between nodes and recovery of information between nodes, consensus of encrypted information, no loss of signal, streaming almost in real time.
![](Hermes.png)

The messages sent contain the information 

The messages are cryptographically signed by the sender and then the packages are processed to the recipient

The only address is used to prevent repeat contracts and vulnerabilities 

The total amount of ether "ether is a cost that is generated in each transmitted communication package" 

It is a packet exchange an encrypted channel is opened channel packet frames are sent and the channel is closed



code solidity

"These contracts were constructed from other examples of existing contracts for the example"

pragma solidity >=0.5.0;

contract Spatial_Comunication {
    address owner = comunicacones_sender;
    
    mapping(uint256 => bool) usedNonce;
    
    constructor() public Spatial_Comunication {}
    
    function Contrucctioncomunication(ContractAddres, amount) {
        return abi.soliditySHA3 (
         ["address", "uint256"],
            ["ContractAddres", "amount"],
            
          );
            
    }
    
    function Message (Message, callback) {
        web3.eth.comunicationpersonal.sing(
            "0x" + SingMessage("hex"),
            web3.eth.defaultacount, 
            callback
            
            
            );
    }
    
    function Unique_communication(ContractAddres, amount, callback) {
        var UniqueMessage = constructorMessage(ContractAddres, amount);
        UniqueMessage(message, callback);
    }
    
   second part
   
   pragma solidity 0.5.0;


//ignature Algorithm (ECDSA)
Library ECDSA {
    function ecrecover(bytes32 hash, bytes memory signature) internal pure returns (address) {
        //length signature
        if (signature.length ! = 65) {
            
            revert ("ECDSA: signature ivalid")
            
            
            divide signature
            
            bytes32 r;
            bytes32 s;
            uint256 v;
            
            
            assembly {
                
                r := load(add(signature, 0x20))
                
                s := load(add(signature, 0x40))
                
                v :=byte(load (add(signature, 0x60)))
                
            }
            
            if ( uint256 (s) >  ) {
                revert("ECDSA: invalid signature 's' value");
                
                address signer = ecrecover(hash, v, r, s);
        require(signer != address(0), "ECDSA: invalid signature");

        return signer;
    }
        }
    }
    
   
}
   
