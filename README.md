digitalWrite(u_yellow,HIGH);
digitalWrite(d_yellow,HIGH);
digitalWrite(r_yellow,HIGH);
digitalWrite(l_yellow,HIGH);
digitalWrite(u_red,LOW);
digitalWrite(l_red,LOW);
digitalWrite(r_red,LOW);
digitalWrite(d_green,LOW);
delay(5000);

//LEFT LANE GO
digitalWrite(u_yellow,LOW);
digitalWrite(d_yellow,LOW);
digitalWrite(r_yellow,LOW);
digitalWrite(l_yellow,LOW);
digitalWrite(u_red,HIGH);
digitalWrite(d_red,HIGH);
digitalWrite(r_red,HIGH);
digitalWrite(l_green,HIGH);
delay(10000);

}
