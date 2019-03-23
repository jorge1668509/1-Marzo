function [ t,y ] = Call_ODE_LOTKA( )
    
tspan = [0 50];

y0 = [100 8];

[t, y ]= ode23(@ODE_LOTKA,tspan,y0);

plot(t,y)
grid

legend('(dx/dt = a*x-b*x*y) (dy/dt = c*x*y-d*y)');
title('Ecuación Lotka-Volterra');
xlabel('Eje t');
ylabel('Eje y');
end
