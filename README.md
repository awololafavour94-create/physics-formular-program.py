# PHYSICS FORMULA PROGRAM

# 1. Speed
def speed(distance, time):
    return distance / time


# 2. Acceleration
def acceleration(final_velocity, initial_velocity, time):
    return (final_velocity - initial_velocity) / time


# 3. Force
def force(mass, acceleration):
    return mass * acceleration


# 4. Kinetic Energy
def kinetic_energy(mass, velocity):
    return 0.5 * mass * velocity ** 2


# 5. Density
def density(mass, volume):
    return mass / volume


print("Speed:", speed(100, 20))
print("Acceleration:", acceleration(20, 0, 5))
print("Force:", force(10, 5))
print("Kinetic Energy:", kinetic_energy(5, 10))
print("Density:", density(20, 4))