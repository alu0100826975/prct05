#!/src/bin/python
PI = 3.1415926535897931159979634685441852
n = int(raw_input ("Introduce el numero de intervalos."))

suma=0

for i in range(1, n+1):
  xi=(i-0.5)/float(n)
  f_xi= 4/(1+xi**2)
  b = i/float(n)
  a = b-(1/float(n))
  print ' Subintervalo: [%f, %f]   xi: %f   f_xi: %f' % (a, b, xi, f_xi)
  suma = suma + f_xi
pi = suma/n
print 'El valor de PI aproximado es %.10f' % pi
print "El valor de pi con 35 decimales es %.35f" % PI





