answer = input('Hello Please Input "Start": ')
if answer == "Start":
    print("Please wait for life")
    import random

    a = random.randint(1, 10)
    # Generate a random integer between 1-10 inclusive
    Evopoints = 0
    Evopoints += a

    if Evopoints < 10:
        print("Generating more Evopoints")
        Evopoints2 = 0
        Evopoints2 += a
        Evopoints += Evopoints2
        answer = input(
            '"Continuing" (just answer Continue for this one and after this and after that")'
        )

        if answer == "Continue":
            print("Evolving!")
            print("Please Wait")
            b = random.randint(1, 5)
            # Generate random integer 1-5 inclusive
            answer = input("Getting attribute:  ")

            if answer == "Continue":
                AtT = 0
                AtT += b
                creature_evolved = 1
                if AtT == 1:
                    Creature1 = 0
                    DMC = 856
                    Creature1 += DMC
                    print("Your Creature is now Multi cellular")
                if AtT == 2:
                    Creature1 = 0
                    RA = 612
                    Creature1 += RA
                    print("Your Creature now requires air")
                if AtT == 3:
                    Creature1 = 0
                    ME = 978
                    Creature1 += ME
                    print("Ypur creature now has an Extended membrane")
                if AtT == 4:
                    Creature1 = 0
                    MD = 265
                    Creature1 += MD
                    print("Your Creature has Developed a mouth like organelle")
                if AtT == 5:
                    Creature1 = 0
                    DE = 701
                    Creature1 = DE, creature_evolved
                    print("Your creature has developed an eye organelle")

import threading
import time


class Simulation:
    def __init__(self):
        self.running = True

    def run_simulation(self):
        while self.running:
            # Run simulation loop
            print("Simulation running...")
            time.sleep(1)  # Simulate some work
            creature_evolved = random.random() < 0.1

    def handle_user_input(self):
        while True:
            user_input = input("Waiting for Evolution...")
            if user_input == "Evolve":
                print('Your Creature is Evolving!')
            if user_input == "stop":
                self.running = False
                break
            elif user_input == "status":
                print("Simulation running..." if self.running else "Simulation stopped")


# Create simulation and start it in a separate thread
simulation = Simulation()
simulation_thread = threading.Thread(target=simulation.run_simulation)
simulation_thread.start()

# Handle user input in the main thread
simulation.handle_user_input()
if user_input == "Evolve":
    AtT = 0
    AtT += b
    print("f AtaT {AtT}")
