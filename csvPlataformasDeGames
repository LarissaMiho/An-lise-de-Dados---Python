#link da onde peguei os dados https://www.kaggle.com/garfieldliang/video-games-analysis

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from matplotlib.ticker import StrMethodFormatter

data = pd.read_csv("vgsales.csv")
datas = data.Platform.value_counts()

plt.title('Plataformas mais usadas desde 1980 até os dias de hoje')
plt.xlabel('Plataformas')
plt.ylabel('Quantidade de Jogos')

datas.plot(kind='bar',figsize=(18,10),grid=False,color='purple',rot=40)
