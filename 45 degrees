import numpy as np
import matplotlib.pyplot as plt

# Initial conditions
v0 = 20  # Initial velocity (m/s)
theta_deg = 45  # Launch angle (degrees)
g = 9.8  # Gravitational acceleration (m/s^2)
theta = np.radians(theta_deg)

# Time array
t_max = 2 * v0 * np.sin(theta) / g  # Flight time
t = np.arange(0, t_max, 0.01)

# Trajectory calculation
x = v0 * np.cos(theta) * t
y = v0 * np.sin(theta) * t - 0.5 * g * t**2

# Plot
plt.plot(x, y, label=f"θ={theta_deg}°")
plt.xlabel("Distance (m)")
plt.ylabel("Height (m)")
plt.title("Parabolic motion trajectory")
plt.legend()
plt.grid()
plt.show()
