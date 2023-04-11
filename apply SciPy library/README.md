### Results:
#### 1. Total number of iterarions:
1. BFGS: 35
2. Conjugate Gradient: 38
3. Newton-CG: 275
4. Gradient Descent: 11826
5. Pure Newton's Method: 6

#### 2. Comparison of number of iterarions:
1. BFGS: second smallest, similar to Conjugate Gradient
2. Conjugate Gradient: third smallest, similar to BFGS
3. Newton-CG: fourth smallest
4. Gradient Descent: largest
5. Pure Newton's Method: takes smallest number of iterarions to reach optimal solution among these 5 algorithms

####  3. Function value of last point:
1. BFGS: 0.000000
2. Conjugate Gradient: 0.000000
3. Newton-CG: 0.000000
4. Gradient Descent: 6.351963040237013e-11, doesn't reach the optimal solution
5. Pure Newton's Method: 0.0

#### 4. Step length:
1. BFGS: large in the begining, and become smaller at each iteration
2. Conjugate Gradient: large in the begining, and become smaller in each iteration, converges slower then BFGS
3. Newton-CG: large in the begining, and become smaller in each iteration, converges slower then Conjugate Gradient
4. Gradient Descent: No obvious pattern, sometimes become larger and sometimes become smaller
5. Pure Newton's Method: No obvious pattern, sometimes become larger and sometimes become smaller

#### 5. Position of initial step:
1. BFGS: [-1.01994107,  2.24409936]
2. Conjugate Gradient: [-1.45588717,  2.13552001]
3. Newton-CG: [-1.6134919 ,  2.09626603]
4. Gradient Descent: [-1.45813184,  2.13496094]
5. Pure Newton's Method: [-1.9925187 ,  3.97007481]

#### 6. Position of last step:
1. BFGS: [0.99999575, 0.99999152]
2. Conjugate Gradient: [0.99999983, 0.99999969]
3. Newton-CG: [0.99997225, 0.9999444 ]
4. Gradient Descent: [0.99999203 0.99998405]
5. Pure Newton's Method: [1. 1.]
