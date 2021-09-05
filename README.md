# Simple Numerical Simulation using Fourth-order Runge-Kutta & Euler Method
A simplest possible numerical simulator ;)

```python
def f(x):
    # Do what you want for v=dx/dt !
    return v

sim = NumSim(func=f, dt=dt, method="RK4")

x = x_0  # initial vector

for t in range(steps):
    x = sim.step(x)
    print(x)  # Boooon!!!!
```

![image](https://user-images.githubusercontent.com/1684732/132111605-887ea12f-24d1-436e-b424-7bd8a6015e78.png)

# NBViewer
https://kokes.github.io/nbviewer.js/viewer.html#aHR0cHM6Ly9naXRodWIuY29tL3Vnby1uYW1hLWt1bi9zaW1wbGVfbnVtc2ltL2Jsb2IvbWFpbi9OdW1lcmljYWxTaW11bGF0aW9uLmlweW5i
