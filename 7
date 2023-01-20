pragma solidity ^0.8.0;

contract SmartContract {
address payable owner;
mapping(address => uint) public balances;
event Deposit(address indexed sender, uint amount);
event Withdrawal(address indexed sender, uint amount);

Copy code
constructor() public {
    owner = msg.sender;
}

function deposit() public payable {
    require(msg.value > 0, "Cannot deposit 0 or negative value.");
    balances[msg.sender] += msg.value;
    emit Deposit(msg.sender, msg.value);
}

function withdraw(uint amount) public {
    require(balances[msg.sender] >= amount, "Insufficient funds.");
    require(amount > 0, "Cannot withdraw 0 or negative value.");
    balances[msg.sender] -= amount;
    msg.sender.transfer(amount);
    emit Withdrawal(msg.sender, amount);
}

function transfer(address payable recipient, uint amount) public {
    require(balances[msg.sender] >= amount, "Insufficient funds.");
    require(amount > 0, "Cannot transfer 0 or negative value.");
    balances[msg.sender] -= amount;
    balances[recipient] += amount;
    recipient.transfer(amount);
}

function balanceOf(address account) public view returns (uint) {
    return balances[account];
}

function changeOwner(address newOwner) public {
    require(msg.sender == owner, "Only the owner can change the owner.");
    owner = newOwner;
}
}
