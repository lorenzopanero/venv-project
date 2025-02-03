# Define the Animal class
class Animal:
    # Constructor to initialize Buddy with a given number of legs
    def __init__(self, legs):
        self.number_of_legs = legs
        print("Buddy, the Animal, has come to life in the game!")

    # Method to simulate Buddy running
    def run(self):
        print("Buddy is running with joy!")

    # Method to display the number of legs Buddy has
    def count_legs(self):
        print(f"Buddy has {self.number_of_legs} legs.")

    # Method to return the number of legs Buddy has
    def return_legs(self):
        return self.number_of_legs

buddy_instance = Animal(legs=4)

buddy_instance.run()

print(f"Buddy's number of legs: {buddy_instance.number_of_legs}")

legs_count = buddy_instance.return_legs()
print(f"Buddy's number of legs (using method): {legs_count}")
