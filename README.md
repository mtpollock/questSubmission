# questSubmission

# Chapter 1 Day 1 Quests

*1.* _Explain what the Blockchain is in your own words:_
* The captial "B" Blockchain is digital information storage with added functionalities: built in history + records, hard to hack, open and accessable to everyone _(you can more directly build + interact with information here than elsewhere online. This is becuase the source information is public not just the visualized information.)_, and more robust or permanent _(if one company who is on closes up shop, even if they're big, the blockchain isn't folding with them)_. 

*2.* _Explain what a Smart Contract is:_
* A smart contract is a defined ruleset on the blockchain that can be engaged with. They are the roads that define engaging with the blockchain!

*3.* _Explain the difference between a script and a transaction:_
* A script in blockchain is also run on the blockchain to get information. A script is logic run on a computer to generate a result. A transaction is the declaration of logic on the blockchain that is run only if it passes requirements set up in its request. The difference between a script and a transaction is that a script is not necissarily run on the blockchain while a transaction must be and a script doesn't need to pass external requirements to be run (often the requirments are money related for transactions - "do you have enough currency on the blockchain to run this transaction?")

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

*4. Add two new things inside your contract: A variable named myNumber that has type Int (set it to 0 when the contract is deployed. A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber. Add a script that reads myNumber from the contract. Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.*
<img width="732" alt="Screen Shot 2022-07-12 at 3 19 57 PM" src="https://user-images.githubusercontent.com/48837692/178566211-2d09f7a1-3529-4219-a6ac-b49a83b120fb.png">
<img width="800" alt="Screen Shot 2022-07-12 at 3 20 03 PM" src="https://user-images.githubusercontent.com/48837692/178566230-1f787c0e-c8ec-4fbf-abc3-b8b1c80798fe.png">
<img width="1153" alt="Screen Shot 2022-07-12 at 3 20 10 PM" src="https://user-images.githubusercontent.com/48837692/178566251-e63591be-2b37-43a3-aae3-e310217c0b09.png">

# Chapter 2 Day 3 Quests

*1. In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.*
<img width="518" alt="Screen Shot 2022-07-12 at 10 15 13 PM" src="https://user-images.githubusercontent.com/48837692/178627552-e594c205-8d23-4ead-ba08-c164bc79618a.png">

*2. In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!*
<img width="1183" alt="Screen Shot 2022-07-12 at 10 24 01 PM" src="https://user-images.githubusercontent.com/48837692/178628465-2e3cf570-f4db-4e57-aa05-f7aaa3de686f.png">

*3. Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).*
<img width="802" alt="Screen Shot 2022-07-12 at 10 31 50 PM" src="https://user-images.githubusercontent.com/48837692/178629270-a6fb8657-4540-4f5c-ba9c-a7bfcaab428a.png">

*4. Using this picture below, explain...
  What the error message means
  Why we're getting this error
  How to fix it!
<img width="1361" alt="wrongcode" src="https://user-images.githubusercontent.com/48837692/178748414-635f9108-77aa-45f4-8376-ec0a8c10e64d.png">

The error message is saying the type of the returned object does not match the stated type in the function. We are getting this error as dictionaries return a value as an optional! there are 2 ways that I know how to fix this error - 1. request an optional in the original function. Change the function to ask for a **String?** or 2. to unwrapped the optional in the return statement to convert it to a string by ***return thing[0x03]!***

# Chapter 2 Day 4 Quests

*1. Deploy a new contract that has a Struct of your choosing inside of it (must be different than Profile).*
*2.Create a dictionary or array that contains the Struct you defined.*
*3.Create a function to add to that array/dictionary.*

answers to Q 1+2+3 are in the contract below. 

```
pub contract BookReviews {
  
  pub var books: {String: Book}

  pub struct Book {
    pub let title: String
    pub let author: String
    pub let description: String
    pub let reviewer: String
    pub let review: String
    pub let rating: UFix64

    init(title: String, author: String, description: String, reviewer: String, review: String, rating: UFix64 ) {
      self.title = title
      self.author = author
      self.description = description
      self.reviewer = reviewer
      self.review = review
      self.rating = rating
    }
  }

  pub fun addBook(title: String, author: String, description: String, reviewer: String, review: String, rating: UFix64){
    let newBook = Book(title: title, author: author, description: description, reviewer: reviewer, review: review, rating: rating)
    self.books[title] = newBook
  }

  init() {
    self.books = {}
  }
}
```

*4. Add a transaction to call that function in step 3.*

```
import BookReviews from 0x02

transaction(title: String, author: String, description: String, reviewer: String, review: String, rating: UFix64) {

    prepare(signer: AuthAccount) {}

    execute {
        BookReviews.addBook(title: title, author: author, description: description, reviewer: reviewer, review: review, rating: rating)
        log("We're done.")
    }
}
```

*5. Add a script to read the Struct you defined.*

```
import BookReviews from 0x02

pub fun main(): BookReviews.Book {
    return BookReviews.books["Dune"]!
}
```

# Chapter 3 Day 1 Quests

*1. In words, list 3 reasons why structs are different from resources.*
Structs are different then resources because a struct can be copied, a struct can be created outside of a contract and they can be created but not engaged with (and also created and forgotten! making them possible to lose).

*2. Describe a situation where a resource might be better to use than a struct.*
a resource may be a good thing to use if you, as a game designer, are wanting to give a golden-key to a user that allows them to not need to pay for anything in store for as long as the product exists. A Resource does a good job of creating that and managing that objects existance without creating a security hole where it gets copied + moved around without you knowing. 

*3. What is the keyword to make a new resource?*
Create

*4. Can a resource be created in a script or transaction (assuming there isn't a public function to create one)?*
No a resource as I understand it cannot be created in a script or transaction but only in a contract. 

*5. What is the type of the resource below?*
```
pub resource Jacob {

}
```
I think the resource is of type **@Jacob**

*6. Let's play the "I Spy" game from when we were kids. I Spy 4 things wrong with this code. Please fix them.*
pub contract Test {
```
pub resource Jacob {
        pub let rocks: Bool
        init() {
            self.rocks = true
        }
    }

    pub fun createJacob(): @Jacob { // there is 1 here
        let myJacob <- create Jacob() // there are 2 here
        return <- myJacob // there is 1 here
    }
}
```

The issues that I found was a missing **@** character, an = instead of a **<-**, a missing **create** and a missing **<-** in the return statement. 
