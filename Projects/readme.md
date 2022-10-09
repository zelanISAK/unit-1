# Crypto Wallet

![](22ROOSE-master768.gif)  
<sub>Illustration for Glenn Harvey</sub>

# Criteria A: Planning

## Problem definition

Ms. Sato is a local trader who is interested in the emerging market of cryptocurrencies. She has started to buy and sell electronic currencies, however at the moment she is tracking all his transaction using a ledger in a spreadsheet which is starting to become burdensome and too disorganized. It is also difficult for Ms Sato to find past transactions or important statistics about the currency. Ms Sato is in need of a digital ledger that helps her track the amount of the cryptocurrency, the transactions, along with useful statistics. 

Apart for this requirements, Ms Sato is open to explore a cryptocurrency selected by the developer.

## Proposed Solution

Design statement:
I will to design and make a <ins>digital ledger</ins> for a client who is <ins>Ms. Sato</ins>, a local trader. The <ins>project</project> will be about <ins>designing a digital ledger</a> and is constructed using the software <ins>Python 3.9.13</ins>. It will take <ins>2 weeks</ins> to make and will be evaluated according to the criteria below.

Justify the tools/structure of your solution

## Rationale for Proposed Solution
JUSTIFY HOW THE CHOICE OF THIS PARTICULAR PRODUCT IS AN EFFECTIVE SOLUTION.

## Success Criteria
1. The electronic ledger is a text-based software (Runs in the Terminal).
2. The electronic ledger display the basic description of the crypotocurrency selected - Cosmos.
3. The electronic ledger allows to enter, withdraw and record transaction (including the recipient, sender, timestamp, and wallet ID of the involved stakeholders).
4. The electronic ledger categorizes transactions into either buying, selling, or transfer of Cosmos coins.
6. The electronic ledger shows important statistics such as Cash Flow, Balance Trend, and Expenses Structure.
7. The electronic ledger is secured; it requires a password for access.



# Criteria B: Design

## Test Plan
1. ~~Welcome Message + Login System - September 27 to 28~~
2. ~~Introduction to the Crypto (Format visually) - October 1~~
3. ~~Show current ledger - October 1~~
4. ~~What would you like to do? Add to ledger, Show statistics. - October 1~~
5. ~~LEDGER - October 3~~
    1. ~~Input data~~
6. ~~!!STATISTICS - October 5~~
    ~~1. Cash Flow~~
    ~~2. Balance Trend~~
    ~~3. Expense Structure~~
    ~~4. All~~
7. ~~REGISTER SYSTEM~~
8. ~~LOGIN SYSTEM~~
8. EXTRAS
    * ~~Visual Layout~~
    * Error messages
        * ~~Create a function to check if it's an int & if it fits the ranges~~
        * Create a function to check if its a string & if it's the correct spelling
        * What if its the incorrect spelling? Print (Do you mean "...") OR create an error message and go back to the input line
 

## System Diagram
![project_diagrams-System Diagram drawio](https://user-images.githubusercontent.com/113817801/194740842-3a772d67-ff86-456d-8a38-1af79ebbaff7.png)


## Flow Diagrams
![project_diagrams-Log in Flowchart drawio](https://user-images.githubusercontent.com/113817801/194741830-c2aa6430-7bc3-491f-abb9-1f54f4d03d70.png)


## Record of Tasks
| Task No | Planned Action                                                | Planned Outcome                                                                                                 | Time estimate | Target completion date | Criterion |
|---------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Create system diagram                                         | To have a clear idea of the hardware and software requirements for the proposed solution                        | 10min         | Sep 22                | B         |
| 2       | Completion of success criteria                                         | To have a good definition of what needs to be achieved and what a successful project would look like                        | 10min         | Sep 22               | A         |
| 3       | Alpha Development                                         | Create an initial draft of the code that satisfies the success criteria created.                        | 7 hours         | October 6               | C         |
| 4       | Beta-testing                                         | Test the program on actual users and uncover any issue or bugs before releasing to the client.                        | 40 minutes         | October 7               | A         |
| 5       | Beta Development                                        | Fix uncovered issues & bugs, and add features that are previously suggested                       | 6 hours         | October 9               | C         |



<br></br>


# Criteria C: Development
## Existing Tools
**Integrated Development Environment (IDE)**: PyCharm


**Libraries**
* import warnings; warnings.filterwarnings("ignore")
* random
* pathlib
* datetime
* matplotlib.pyplot
* string


**Structures**
* Functions
* Loops
    * For
    * While
* Validation: try, except ValueError
* with open ("\.csv", "a") as file
* write.(\data)
* Data Types: String, Boolean, Integer


## Sources

