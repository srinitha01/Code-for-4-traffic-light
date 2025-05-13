int ARed=1; Int Ayellow=2; ///North 
int AGreen=3;

int BRed=4; int Byellow=5; ///south 
int BGreen=6;

int CRed=7; Int Cyellow=8; /// west 
int CGreen=9;

int DRed=10; Int Dyellow=11; ////East
int DGreen=12;

void setup() { pinMode(1, OUTPUT); pinMode(2, OUTPUT); pinMode(3, OUTPUT); pinMode(4, OUTPUT); pinMode(5, OUTPUT); pinMode(6, OUTPUT); pinMode(7, OUTPUT); pinMode(8, OUTPUT); pinMode(9, OUTPUT); pinMode(10, OUTPUT); pinMode(11, OUTPUT); pinMode(12, OUTPUT); }

void loop() { digitalWrite(3, HIGH); delay (1000); digitalWrite(3,LOW); digitalWrite(2, HIGH); delay (2000); //north digitalWrite(2, LOW); digitalWrite(1,HIGH); delay (3000); digitalWrite(1,LOW);

digitalWrite(6,HIGH) delay (2000);

digitalWrite(6,LOW); digitalWrite(5,HIGH); delay (3000); //l/south digitalWrite(5,LOW); digitalWrite(4, HIGH); delay (4000); digitalWrite(4, LOW);

digitalWrite(9,HIGH); delay (3000); digitalWrite(9,LOW); digitalWrite(8,HIGH); delay (1000); //west digitalWrite(8,LOW);digitalWrite(u_yellow,HIGH);

