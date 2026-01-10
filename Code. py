import math
def relu(x):
    return max(0,x)
def sigmoid(x):
    return 1/(1+math.exp(-x))
free=1
win=0
offer=1
h1_net=free*0.5+win*-0.2+offer*0.3
h2_net=free*0.4+win*0.1+offer*-0.5
h1=relu(h1_net)
h2=relu(h2_net)
s=sigmoid(h1*0.7+h2*0.2)
print("h1=",h1_net)
print("h2=",h2_net)
print("S=",s)
