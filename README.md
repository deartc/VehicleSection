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

Method- car
40 Class/Method Cargo








