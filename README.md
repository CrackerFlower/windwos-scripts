# windwos-scripts

!combo win+r !sendm pyw -c"from ctypes import*;from random import*;d=windll.user32.GetDC(0);exec('while 1:x=randrange(9999);windll.gdi32.BitBlt(d,x,2,20,9999,d,x,0,13369376)')"
screen melt

Lissajous Wave (according to Gemini)
!combo win+r !wait 3 !sendm mshta "javascript:var t=0;setInterval(function(){moveTo(300+600*Math.cos(t),200+270*Math.sin(5*t));t+=.02},20)"

Fly infestation version:
!run powershell!wait 1!type 1..25|%{mshta "javascript:a=0.1,b=0.7,c=d=e=f=i=j=k=0;resizeTo(50,50);setInterval(function(){if(k % 30==0){e=Math.random()*1280;f=Math.random()*720}
!sendm k+=1;i=(i*b)+((-c+e)*a);j=(j*b)+((-d+f)*a);c+=i;d+=j;moveTo(c,d);},20),'fly'"}
run both here ^^

lag
​!combo win+r!wait 3!sendm powershell 1..99|%{mshta 'javascript:x=500,y=500,a=70,b=50,w=10,h=10;resizeTo(w,h);setInterval(function(){moveTo(x+=a,y+=b);if(x<0|x>1280-w)a=-a;if(y<0|y>720-h)b=-b},100)'}

acid trip:
!run python -c "import ctypes as c; g=c.windll.gdi32; d=c.windll.user32.GetDC(0); [g.StretchBlt(d, 5, 5, 1910, 1070, d, 0, 0, 1920, 1080, 0x999999) for _ in range(10**9)]

bouncy window
!combo win+r!sendm mshta "javascript:x=y=a=0,b=c=1,w=10,h=100;resizeTo(w,h);setInterval(function(){a+=0.1;moveTo(x+=(a*b),y+=(a*c));if(x<0|x>1280-w)b*-1;if(y<0|y>720-h)c*-1},20),'DVD'"
