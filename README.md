# Code-Louisville-Quality-Project-Teresa-Hawkins

 #3.  UNIT TEST PROJECT:
To run the project do the following: Clone github.com/deartc/Quality-Project-Teresa-Hawkins. The extensions used were C# and Net. The NuGets used were xunit.

Requirements of classes completion:

On the Vehicle class, add unit tests and refactor where necessary.
On the SemiTruck class, implement all methods and write unit tests.
Add 3rd class, Car, implement it, and add unit tests for it.
Cargo class(Started but did not include git hub link)
Unit tests requirements:

parameterless constructor -object of type Vehicle,

Vehicle, -public properties to the provided values.

parameterless AddGas method fills the gas tank to 100% of its capacity

AddGas method with a parameter adds the supplied amount of gas to the gas tank.

AddGas GasOverfillException – how much add and what the capacity was.

GasLevel -a 0%, 25%, 50%, 75%, and 100%.. (theory test)

Drive method: without gas returns the status string “Cannot drive, out of gas.”

drive a car - flat tire returns the status string “Cannot drive due to flat tire.”.

Drive the car 10 miles. GasLevel MilesRemaining mileage correct.

Drive the car 100 miles. GasLevel MilesRemaining mileage correct.

Out of gas. GasLevel MilesRemaining mileage correct.

ChangeTireAsync will throw a NoTireToChangeException

ChangeTireAsync can successfully be used to change a flat tire

GotFlatTire method Refactor GotFlatTire can be both true and false.

SemiTruck object which is also a Vehicle and has 18 wheels.

Cargo property -CargoItems which is empty, but not null.

LoadCargo: correctly adds the passed object to the Cargo.

UnloadCargo Positive Test: remove from the Cargo and return cargo

CargoIUnloadCargo Negative Test: Verify that attempting to unload a CargoItem that does not appear in the Cargo throws a System.ArgumentException.

GetCargoItemsByName Positive Test: item that exist returns all items wit exactly that name.

GetCargoItemsByName Negative Test: does not exist returns an empty list.

GetCargoItemsByPartialDescription Positive Test: contain that Description.

GetCargoItemsByPartialDescription Negative Test does not exist returns an empty list.

GetTotalNumberOfItems: sum of all quantities of all items in the Cargo List.

Car instances are also Vehicles and have 4 tires.

IsValidModelForMakeAsync test:

WasModelMadeInYearAsync Negative Test: before 1995 System.ArgumentException.

WasModelMadeInYearAsync Positive Tests: Make that does not exist at all returns false

Make Honda, Model Camry returns false (regardless of year).

Make Subaru, Model WRX returns true for year 2020.

Make Subaru, Model WRX returns false for year 2000.

AddPassengers test: reduces the fuel economy of the car by .2 per passenger.

RemovePassengers test: Car with 5 passengers that gets 21 MPG.

RemovePassengers 2 passengers and gets 20.6 MPG.

RemovePassengers 0 passengers and gets 21 MPG

RemovePassengers 0 passengers and gets 21 MPG.

Methods- vehicle

Methods- semitruck

Method- car 40 Class/Method Cargo

QA Testing Course 1 - Project Requirements

To run the project do the following: Clone github.com/deartc/Quality-Project-Teresa-Hawkins.  The following Microsoft Offic# Code-Louisville-Quality-Project-Teresa-Hawkins
e Suite programs were used:  Word,  Sway, Vizio, and Power Bi.

Purpose: 
Verizon churn rate is one of the lowest in their market segment.  One of the main reasons is their websites try to engage their customers. This project examines the website  to see if it appeals to seniors or has flaws that might make this sector less likely to not renew their service.   A website  test plan is executed and uses Sway.   A Sway presention  also details a Power Bi visual analysis of churn rates and examines  the quality assurance of the website in relation to churn rate retention.   


#1: Test Plan
I completed a test plan on the Verizon site.  I have attached the test plan detailing steps I took.

https://sway.office.com/zBIxDmNBKuwC0Xrn
	

	
#2: Manual Test Execution
I am presenting the results of my manual test execution.   I have attached the following presentation detailing the manual
test execution.

https://sway.office.com/LT6UTiOlBFiSN9I8?ref=Link

I used power bi to visually display the Verizon churn  rate and how focusing on this Verizon webpage test might affect this churn rate.  The power bi link is :


[VerizonChurnReport.pdf](https://github.com/deartc/Quality-Project-Teresa-Hawkins/files/9611038/VerizonChurnReport.pdf)


 

#3: Unit Test Creation:
1. On the Vehicle class, add unit tests  and refactor where necessary.
2. On the SemiTruck class, I will implement all methods and write unit tests 
3. Add 3rd class, Car, implement it, and add unit tests for it. the first steps of the code are included here: https://github.com/deartc/CarSection.git




