function [ dtdy ] = ODE_LOTKA( t,y )

%Definición de Constantes
a = 0.4;
b = 0.4;
c = 2;
d = 0.09;

%Ecuación Difrencial
%(dx/dt = a*x -b*x*y) (dy/dt = c*x*y-d*y)
dtdy = diag([a*y - b*y*y(2), c*y*y(1)- d*y]);
end
