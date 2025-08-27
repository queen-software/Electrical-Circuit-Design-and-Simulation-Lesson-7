# Electrical-Circuit-Design-and-Simulation-Lesson-7
## Uno 7segment ekran
void setup() {
    for(int i = 2;i <=9; i++){
    pinMode(i ,OUTPUT);
  }

}

void loop() {
  for(int i = 2;i <=9; i++){
    digitalWrite(i ,HIGH);
  }

}
düzelticem
### bu kodu 
      // C++ code
    //
    int a =2;
    int b = 3;
    int c = 4;
    int d = 5;
    int e = 6;
    int f = 7;
    int g = 8;
    int dp = 9;
    
    
    void setup()
    {
      pinMode(a, OUTPUT);
      pinMode(b, OUTPUT);
      pinMode(c, OUTPUT);
      pinMode(d, OUTPUT);
      pinMode(e, OUTPUT);
      pinMode(f, OUTPUT);
      pinMode(g, OUTPUT);
      pinMode(dp, OUTPUT);
    
    
    }
    
    void loop(){
      sifir();
      delay(1000);
      bir();
      delay(1000);
      iki();
     
    }
    void bir(){
      digitalWrite(b,HIGH);
      digitalWrite(c,HIGH);
    }
    void iki(){
      digitalWrite(a,HIGH);
      digitalWrite(b,HIGH);
      digitalWrite(g,HIGH);
      digitalWrite(e,HIGH);
      digitalWrite(d,HIGH);
    }
    void uc(){
       digitalWrite(c,HIGH);
      digitalWrite(b,HIGH);
      digitalWrite(g,HIGH);
      digitalWrite(g,HIGH);
      digitalWrite(d,HIGH);
    }
    
    void dort();
    {
      
    }
    
    void bes();
    {
      digitalWrite(a,HIGH);
      digitalWrite(f,HIGH);
      digitalWrite(g,HIGH);
      digitalWrite(c,HIGH);
      digitalWrite(d,HIGH);
    }
    void alti(){
      bes();
      digitalWrite(e,HIGH);
      
    }
    void yedi(){
      bir();
      digitalWrite(a,HIGH);
    }
    void sekiz(){
      alti();
      digitalWrite(b,HIGH);
    }
    void dokuz() {
    bes();
      digitalWrite(b,HIGH);
      
    }
    void sifir(){
    yedi();
      digitalWrite(d,HIGH);
      digitalWrite(e,HIGH);
      digitalWrite(f,HIGH);
      
    }

