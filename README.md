This code was created at 1993 by marry couple of entusiasts.

class Abetov{

	constructor(name, hobby, birthday)
    {	
 	      this.name = name;    
          this.hobby = hobby;    
          this.birthday = birthday;          
    }  
    introduction(){  
    return `hello, my name is ${this.name} Abetov. My giftedness is ${this.hobby}.`
    } 
}

let Alex = new Abetov("Alex", "frontend", 4.5.93)
