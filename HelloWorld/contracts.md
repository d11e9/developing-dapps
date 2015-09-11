#Contracts

lets get stuck in

    contract HelloWorld {
        address creator;
        
        function HelloWorld() {
            creator = msg.sender;    
        }
    }