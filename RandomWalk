#
# 1차원 랜덤워크 몬테카를로 시뮬레이션
#

import numpy as np
import matplotlib.pyplot as plt

for i in range(3):
  position_list = []
  position = 0
  position_list.append(position)

  for j in range(10000):
    position = position + np.random.randint(-1,2)
    position_list.append(position)

  ind = np.arange(len(position_list))
  plt.plot(ind, position_list)

plt.ylim(-200,200)
plt.show()
