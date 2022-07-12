# questSubmission

# Chapter 1 Day 1 Quests

*1.* _Explain what the Blockchain is in your own words:_
* The captial "B" Blockchain is digital information storage with added functionalities: built in history + records, hard to hack, open and accessable to everyone _(you can more directly build + interact with information here than elsewhere online. This is becuase the source information is public not just the visualized information.)_, and more robust or permanent _(if one company who is on closes up shop, even if they're big, the blockchain isn't folding with them)_. 

*2.* _Explain what a Smart Contract is:_
* A smart contract is a defined ruleset on the blockchain that can be engaged with. They are the roads that define engaging with the blockchain!

*3.* _Explain the difference between a script and a transaction:_
* A script is logic run on a computer to generate a result. A transaction is the declaration of logic on the blockchain that is run only if it passes requirements set up in its request. The difference between a script and a transaction is that a script is not necissarily run on the blockchain while a transaction must be and a script doesn't need to pass external requirements to be run (often the requirments are money related for transactions - "do you have enough currency on the blockchain to run this transaction?")

# Chapter 2 Day 1 Quests

*1.* _What are the 5 Cadence Programming Language Pillars?_
* Safety and Security, Clarity, Approachability, Developer Experience, Resource Oriented Programming

*2.* _In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful_
* **Safety and Security** - interacting with people online has a lot of moments of interacting with people you do not know and could use their almost anonimoty to take advantage of you - being able to interact with people online safer with more security will be very useful to speed up exchanges as you will not need to first go through as many hoops to prevent bad interactions. **Clarity** in this instance refers to clarity of code - which is useful to allow more auditing of code and its function. More auditing will allow more mistakes to be caught while also preventing bad-actors from writing subtle features to take advantage of others. **Approachability** is important as it relates to the translation of skills making it easier for current devolopers to engage with the new language and speed up the adoption of Cadence / Flow. **Developer Experience** refers to the activing of writing and debugging code the way the language is constructed allows for easier debugging which is likely one of the longer parts of the development process - so speeding that up could be a big win!

# Chapter 1 Day 2 Quests

<img width="1437" alt="Screen Shot 2022-07-11 at 8 00 34 PM" src="https://user-images.githubusercontent.com/48837692/178372941-e13ada6d-07dc-445e-bcfa-d50db1016c1d.png">
<img width="1420" alt="Screen Shot 2022-07-11 at 8 00 46 PM" src="https://user-images.githubusercontent.com/48837692/178372947-777a1846-f42c-4b80-be59-443e8d0503e1.png">

# Chapter 2 Day 2 Quests

*1. Explain why we wouldn't call changeGreeting in a script.*
* Originally we couldn't call _changeGreeting_ because that function was attempting to update a constant so we had to change our instantiation of greeting to be a variable (allowing us to change it throughout its life). 

*2. What does the AuthAccount mean in the prepare phase of the transaction?*
* AuthAccount here is a type that refers to the details about the account who submits the action. So in this case I think it is declaring the signer, who is sorta like the payer, is the account who authorized the transaction (who sent the transaction in the first place)

*3. What is the difference between the prepare phase and the execute phase in the transaction?* 
* Prepare refers to the steps taken when initatiting the transaction - it is the section where you can first access information / data on an account. While execute is the syntax referring to what is done in the transaction, the meat on what is being requested / done. 

*4. Add two new things inside your contract: A variable named myNumber that has type Int (set it to 0 when the contract is deployed. A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber. Add a script that reads myNumber from the contract. Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.

![Uploading Screen Shot 202<img width="790" alt="Screen Shot 2022-07-12 at 3 17 44 PM" src="https://user-images.githubusercontent.com/48837692/178566003-b2e45659-8054-4485-909e-dce3bed87701.png">
2-07-12<img width="1140" alt="Screen Shot 2022-07-12 at 3 18 17 PM" src="https://user-images.githubusercontent.com/48837692/178566004-3e6895bd-6c1e-4b1b-8398-30e1c377f8c6.png">
 at 3.17.32 PM.png…]()
