class Car():
    """Creating a car (class)"""

    def __init__(self, model, year, engine, price, mileage, wheels):
        """Using the __init__ method, we set the properties (attributes) of our car"""
        self.model = model
        self.year = year
        self.engine = engine
        self.price = price
        self.mileage = mileage
        self.wheels = 4
        print("Vehicle created:")

    def description_car(self):
        """Display the description of the car"""
        description = "1) Model:" + " " + self.model + "\n" + "2) Year:" + " " + str(self.year) + "\n" + \
                      "3) Engine capacity:" + " " + self.engine + "\n" + "4) Price (dollars):" + " " + str(self.price) + " " + "\n" + \
                      "5) Mileage (thousand km):" + " " + str(self.mileage) + "\n" + "6) Number of wheels:" + " " + str(self.wheels)
        print(description)

    def purpose_car(self):
        """Using the purpose_car method, we determine what our car will do"""
        print("Car " + self.model + " works as a taxi\n")

vehicle = Car("Skoda", 2020, "V4", 15000, 100, "")
vehicle.description_car()
vehicle.purpose_car()

class Truck(Car):
    """Creating a truck (class)"""

    def __init__(self, model, year, engine, price, mileage, wheels):
        """Using the __init__ method, we set the properties (attributes) of our truck"""
        super().__init__(model, year, engine, price, mileage, wheels)

    def purpose_truck(self):
        """Using the purpose_truck method, we determine what our truck will do"""
        print("Car " + self.model + " works as a mining truck\n")

truck = Truck("MAN", 2000, "V8", 30000, 200, "")
truck.wheels = 8
truck.description_car()
truck.purpose_truck()
