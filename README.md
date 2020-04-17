int led1 = D6; 

int led2 = D7;

void setup()
{

	pinMode(led1, OUTPUT);
	pinMode(led2, OUTPUT);

}


void loop()
{
    //My first name is MADHU
    
    //To flash M ( - - )
    // line ( - )
     digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 3 seconds...
	delay(3000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000);
	
	
	// line ( - )
	digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 3 seconds...
	delay(3000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000);
	
	
	
	//To flash A ( . - )
	// dot ( . )
    digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 1 second...
	delay(1000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000); 
    
    
    // line ( - )
	digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 3 seconds...
	delay(3000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000);
	
	
	
	//To flash D ( - . .)
	// line ( - )
	digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 3 seconds...
	delay(3000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000);
	
	
	// dot ( . )
    digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 1 second...
	delay(1000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000); 
	
	
	// dot ( . )
    digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 1 second...
	delay(1000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000); 
	
	
	
	//To flash U( . . - )
	// dot ( . )
    digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 1 second...
	delay(1000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000); 
	
	
	// dot ( . )
    digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 1 second...
	delay(1000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000);
	
	
	// line ( - )
	digitalWrite(led1, HIGH);
	digitalWrite(led2, HIGH);

	// We'll leave it on for 3 seconds...
	delay(3000);

	// Then we'll turn it off...
	digitalWrite(led1, LOW);
	digitalWrite(led2, LOW);

	// Wait 1 second...
	delay(1000);
	
	
    
	// And repeat!
}
