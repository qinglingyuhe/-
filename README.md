# -
自己从别的地方搬过来的，纯碎玩玩，不做任何商用


import numpy as np
import matplotlib.pyplot as plt
T = np.linspace(0 , 2 * np.pi, 102)
plt.axes(polar = True)
plt.plot(T, 1. - np.sin(T),color='red')
plt.show()

import numpy as np
import matplotlib.pyplot as plt
t = np.arange(0,4,0.1)
plt.plot(t,t,t,t+2,t,t**2)


