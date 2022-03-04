#define trigPin1 3
#define echoPin1 2
int Vibrator1 = A5; 
int duration1, distance1; 

void setup() {
        Serial.begin (9600); 
    
        pinMode(trigPin1, OUTPUT); 
        pinMode(echoPin1, INPUT);
        pinMode(Vibrator1, OUTPUT);
     
}

void loop() {

    digitalWrite(trigPin1, HIGH);
    delayMicroseconds(1000);
    digitalWrite(trigPin1, LOW);
    duration1 = pulseIn(echoPin1, HIGH);
    distance1 = (duration1/2) / 29.1;

  if (distance1 <= 100 && distance1 >= 70) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");
         Serial.print(distance1);
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH); 
         delay (500) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN,LOW);
         delay (5000) ;
        
        
  
        }

         else if (distance1 <= 80 && distance1 >= 50) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");  
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH);
         delay (450) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN, LOW);
         delay (450) ;
        
        
  
        }

         else if (distance1 <= 50 && distance1 >= 30) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");  
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH);
         delay (250) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN, LOW);
         delay (250) ;
        
        
  
        }
           else if (distance1 <= 30 && distance1 >= 20) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");  
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH);
         delay (150) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN, LOW);
         delay (150) ;
        
        }

            else if (distance1 <= 20 && distance1 >= 10) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");  
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH);
         delay (100) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN, LOW);
         delay (100) ;
        
        
  
        }

        else if (distance1 <= 10 && distance1 > 5) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");  
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH);
         delay (50) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN, LOW);
         delay (50) ;
        
        
  
        }

        else if (distance1 <= 5 && distance1 >= 1) 
        {
         Serial.println("object detected \n");
         Serial.print("distance= ");  
         digitalWrite(Vibrator1,LOW);
         digitalWrite(LED_BUILTIN, HIGH);
         delay (10) ;
         digitalWrite(Vibrator1,HIGH);
         //digitalWrite(LED_BUILTIN, LOW);
         delay (10) ;
        
        
  
        }
        

  else {Serial.println("object detected \n");
        Serial.print("distance= ");              
        Serial.print(distance1);        
        digitalWrite(Vibrator1,HIGH);
        digitalWrite(LED_BUILTIN, LOW);
  
}
}
