# SDE
An iPython notebook to numerically solve stochastic differential equations (SDEs) using an explicit order 1.0 strong scheme.

This numerically solves a SDE written in Ito form as dX = mu*X*dt + sigma*X*dB_t - this is known as a geometric brownian motion. This has particular use in mathematical finance for simulating stock prices which follow a Black-Scholes model.

However, one could easily adapt this to any SDE of their choice by simpily changing the functions a(x,t) and b(x,t).
