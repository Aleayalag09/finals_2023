abs(x) = sqrt(x*x)

sign(x) = x/abs(x)

inv_abs(x)=1/sqrt(x*x)

sign(x) = inv_abs(x) * x

sign(x) = -1 for x < 0
sign(x) = 1 for x > 0

max(a,b) = 0.5*(1+sign(a-b))* a + 0.5*(1-sign(a-b)) * b
