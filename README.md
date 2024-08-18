# waterclass FreshWater:
    def __init__(self):
        self.ice = False
        self.lemon = False

    def add_ice(self):
        self.ice = True
        print("Added ice to the water.")

    def add_lemon(self):
        self.lemon = True
        print("Added a slice of lemon to the water.")

    def serve(self):
        ice_status = "with ice" if self.ice else "without ice"
        lemon_status = "with lemon" if self.lemon else "without lemon"
        print(f"Serving fresh water {ice_status} and {lemon_status}. Enjoy your drink!")


# Example usage:
my_water = FreshWater()

my_water.add_ice()
my_water.add_lemon()
my_water.serve()
