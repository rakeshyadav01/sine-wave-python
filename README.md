import matplotlib.pyplot as plt
import numpy as np

# Data for plotting
x = np.linspace(0, 10, 100)
y = np.sin(x)

# Create the plot
plt.plot(x, y, label='Sine Wave')

# Adding labels and title
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Sine Wave Example')

# Show legend
plt.legend()

# Show the plot
plt.show()
