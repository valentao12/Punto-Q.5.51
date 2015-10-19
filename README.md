# Punto-Q.5.51
Further Analysis
Q.5.51 Load and run the script fi le, sin_cos of Example 5.9.
% Script file: sin _ cos

Beta = linspace(-2*pi,2*pi,100); % creates a 100 element Beta array

figure(1)

subplot(2,1,1)

X1 = 5*cos(2*Beta);

Y1 = 5*sin(Beta);

plot(X1,Y1) % returns the plot of X1 vs Y1

ylabel(‘Y1’)

title(‘X1=5*cos(2*Beta) vs Y1 = 5*sin(Beta)’);

subplot(2,1,2)

X2 = sin(2*Beta+pi/3);

Y2 =sin(Beta);

plot(X2,Y2) % returns the plot of X2 vs Y2

title(‘X2 = sin(2*Beta + pi /3) vs Y2 = sin(Beta)’);

ylabel(‘Y2’), xlabel(‘Beta’)

figure(2)

plotyy(X1,Y1,X2,Y2) % returns the plots of Y1 vs X & 

 % on different scales

xlabel (‘Beta’), ylabel (‘Y1,Y2’)

title(‘X1 vs Y1 and X2 vs Y2’);

Y2 vs X
