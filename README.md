import numpy as np

qovun = np.array([1,7,2,4,3])
tarvuz = np.array([[1,21,33],[4,55,66]])

qoshish = np.sum(qovun)
orta = np.mean(qovun)
kopaytma = np.prod(qovun)
qoshish2 = np.sum(tarvuz)
orta2 = np.mean(tarvuz)
kopaytma2 = np.prod(tarvuz)
print("1 massiv:",qovun)
print("2 massiv:",tarvuz)
print("massivlar yigindisi 1:",qoshish)
print("massivlar yigindisi 2:",qoshish2)
print("orta 1",orta)
print("orta 2",orta2)
print("kopaytma 1",kopaytma)
print("kopaytma 2",kopaytma2)
