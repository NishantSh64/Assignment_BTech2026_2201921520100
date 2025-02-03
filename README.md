# Assignment_BTech2026_2201921520100
Problem Statement for 28 January:
            Create a program to model a Library system using Object-Oriented principles like classes, objects, inheritance, and polymorphism.
            
            The system should have the following components:
            
            Book class, which should include:
            
            title: Name of the book
            author: Author of the book
            isbn: ISBN number of the book
            Library class, which should contain:
            
            A list of books
            A method to add a book to the library
            A method to display all books in the library
            Main class, which will:
            
            Create a library object
            Add books to the library
            Display all the books in the library
Problem Statement for 29 January: Library Management System
            Design a simple Library Management System using OOP concepts. The system should have the following functionalities:
            
            A Book class with attributes: bookId, title, author, and isAvailable.
            A Member class with attributes: memberId, name, and a method to borrow/return books.
            A Library class that manages books and members, allowing book borrowing and returning.
Problem Statement for 30 January:  Online Shopping System
            Create an Online Shopping System using OOP concepts. The system should support the following:

            A Product class with attributes: productId, name, price, and stockQuantity.
            A Customer class with attributes: customerId, name, and cart (list of products).
            A Shop class that manages product inventory and handles customer orders.
Problem 31 January: Online Food Ordering System
            Create an Online Food Ordering System that allows customers to order food from a restaurant.
            
            Requirements:
            Add food items to the menu.
            Place and manage orders.
            Track the status of each order (e.g., Pending, In Progress, Delivered).
            Calculate the total bill.
            Classes to Implement:
            FoodItem: Represents a food item with itemId, name, price, and category.
            Order: Contains details like orderId, list of FoodItems, status, and totalAmount.
            Customer: Holds customer information such as customerId, name, and order history.
            Restaurant: Manages the menu and orders, with methods to add food items, place orders, and update order status.
            Key OOP Concepts:
            Abstraction to hide complex order management.
            Encapsulation to secure customer and order details.
            Inheritance if different types of food items exist (e.g., Beverage, Main Course).
Problem 1 Feb: Banking System
            Design a Banking System using OOP concepts to manage customer accounts and transactions.
            
            Requirements:
            Create new bank accounts (Savings and Current accounts).
            Perform transactions like deposit, withdrawal, and balance inquiry.
            Apply interest to savings accounts.
            Track transaction history for each account.
            Classes to Implement:
            Account: Base class with attributes like accountNumber, accountHolderName, and balance.
            SavingsAccount & CurrentAccount: Inherit from Account, with SavingsAccount having an interestRate and interest calculation method.
            Transaction: Represents a transaction with transactionId, amount, type (deposit/withdrawal), and date.
            Bank: Manages accounts and transactions with methods to create accounts, process transactions, and view transaction history.
            Key OOP Concepts:
            Inheritance to differentiate between SavingsAccount and CurrentAccount.
            Encapsulation to protect sensitive data like account balance.
            Polymorphism for handling different types of transactions.
            
Problem 2 Feb: Design a Vehicle Rental System using OOP principles. The system should manage different types of vehicles and rental operations.

            🚗 1. Vehicle (Base Class)
            Attributes:
            
            vehicleId (int)
            brand (String)
            model (String)
            rentalPricePerDay (double)
            Methods:
            
            calculateRentalCost(int days) – calculates the rental cost for the given number of days.
            displayDetails() – displays the vehicle's details.
            🚙 2. Car (Subclass of Vehicle)
            Attributes:
            
            numberOfSeats (int)
            Methods:
            
            Override calculateRentalCost() to add an additional charge of ₹500 if rented for more than 5 days.
            🏍️ 3. Bike (Subclass of Vehicle)
            Attributes:
            
            hasHelmet (boolean)
            Methods:
            
            Override calculateRentalCost() to give a 10% discount if rented for more than 7 days.
            🚀 4. RentalSystem Class
            Attributes:
            
            vehicles (List of Vehicle objects)
            Methods:
            
            addVehicle(Vehicle vehicle) – adds a new vehicle to the system.
            rentVehicle(int vehicleId, int days) – calculates the total rental cost based on the vehicle type.
            displayAllVehicles() – displays all available vehicles.
Problem 3 Feb: Design a Hotel Booking System using OOP principles. The system should manage room bookings, availability, and pricing.

            🏨 1. Room (Base Class)
            Attributes:
            
            roomNumber (int)
            roomType (String) // Example: Single, Double, Suite
            pricePerNight (double)
            isBooked (boolean)
            Methods:
            
            bookRoom() – marks the room as booked.
            vacateRoom() – marks the room as available.
            displayDetails() – displays the room's details.
            👤 2. Guest Class
            Attributes:
            
            guestId (int)
            name (String)
            bookedRoom (Room object)
            Methods:
            
            bookRoom(Room room) – allows the guest to book an available room.
            checkout() – allows the guest to vacate the room.
            displayBookingDetails() – shows the details of the booked room.
            📋 3. Hotel Class
            Attributes:
            
            hotelName (String)
            rooms (List of Room objects)
            guests (List of Guest objects)
            Methods:
            
            addRoom(Room room) – adds a new room to the hotel.
            registerGuest(Guest guest) – registers a new guest.
            displayAvailableRooms() – displays all available rooms.
