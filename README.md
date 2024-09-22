
function destroy() public onlyOwner {
    owner.transfer(address(this).balance);
}

function destroy() public onlyOwner {
    withdraw();
}

function destroy() public onlyOwner {
    uint256 amount = 0; // specify the amount to keep in the contract
    withdraw();
    owner.transfer(address(this).balance - amount);
}
