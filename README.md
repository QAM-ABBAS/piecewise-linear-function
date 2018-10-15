# piecewise-linear-function
this simple code is used to provide piecewise linear function using matlab
>> x1=0:0.2:5;
y1=4*x1;
>> plot(x1,y1)
>> x2=5:0.2:10;
y2=20*ones(size(x2));
plot(x2,y2)
>> x3=10:0.2:15;
y3=2*x3+40;
plot(x3,y3)
>> x4=15:20;
y4=4*x4-50;
>> plot(x4,y4)
>> x=[x1  x2 x3 x4];
y=[y1  y2 y3 y4];
>> plot(x,y,'b','linewidth',3)
>> 
