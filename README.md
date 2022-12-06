# javascriptpractice

//Using class operator with constructor 

class emplyoee { 
   constructor ("name",age,"designation","height",weight,"behaviour) { 
      this.name=name;
      this.age=age;
      this.designation=designation;
      this.height=height;
      this.weight=weight; 
      this.behaviour;
      }
      const object=new employee("NagendraAnnam",26,"TestEngineer",6,80,"Verygood"); 
      console.log(object.name);  // NagendraAnnam 
      console.log(object.age);  //26 
      console.log(object.designation); // TestEngineer  
      console.log(object.employee) ; // Printing all the Data format 
      
      
// Now Using the only Class operator 

Class employee= {
  this.name=name; 
  this.age=age;
  this.role=role;
  this.behaviour=behaviour; 
  } 
  getDetails () { 
     return "Name: ${this.name}, Age:${this.age=age},role:${this.role},behaviour:${this.behaviour}"; 
     }
     
     const object2=new employee("NagendraAnnam",26,"TestEngineer","veryGood"); 
     console.log(object2.getDetails());   // printing the all data format.  \
     
     
     
     
     // functions using with constructor 
 
     function subject ( ) { 
        this.subject1=subject1;
        this.subject2=subject2; 
        this.subject3=subject3; 
        this.subject4=subject4;
        }
        // creating the multiple objects and values and using with constructor .  
        const object3=new subject("Javascript","API_Testing","Cypress_Tool","Manual_Testing"); 
        console.log("object3.subject) ;  // if it is printing all the data format 
        console.log("object3.subject3) ;   // if it is printing only one statment like subject.  
        
        
         const object4=new subject("Javascript1","API_Testing1","Cypress_Tool1","Manual_Testing1"); 
        console.log("object4.subject) ;  // if it is printing all the data format 
        console.log("object4.subject3) ;   // if it is printing only one statment like subject.  
        
     
     // Using only constructors 
     
     Constructor person  { 
        Name:"Nagendra_Annam",
        Age:26,
        designation:"Test_Engineer",
        behaviour:"Good"
        }
        const name1=person.Name; 
        console.log(name1); 
        const age=person.Age; 
        console.log(age); 
        const desig=person.designation; 
        console.log(desig); 
        const behav=person.behaviour; 
        console.log(behav) ; 
        
        
       //Another way extracting the elements 
       
       const {Name:name1,Age:age,designation:desig,behaviour:behav}=person; 
       console.log(name1); //Nagendra_Annam
       console.log(age); //26
       console.log(desig); //Test_Engineer
       console.log(behav); //Good
        
        
       // A function operates with another function  
       
       function person { 
        name:"Nagendr_Annam" , 
        age:26, 
        behaviour:Very_good"
        fullDetails:function ( ) { 
          retunr this.name+" "+this.age+" "+this.behaviour; 
         }
         } 
         function innerfunc( ) { 
            return this.name+" "+this.age; 
            } 
            } 
            innerfunc () 
            let var1=new person( ); 
            console.log(var1.fullDetails()); 
            
           
          //Call and Apply & bind method
          
         const person= { 
           fullName:function ( ) { 
             return this.firstName+" "+this.lastName; 
             } 
             } 
             const person1={ 
                firstName:"Nagendra",
                lastName:"Annam"
                } 
                const person2={ 
                firstName:"Rajendra",
                lastName:"penumalli"
                }
                console.log(person.fullName.call(person1));  // Printing all the statments '
                
                
                // call method using with arguments also.  
                
                  const person= { 
           fullName:function (city,age) { 
             return this.firstName+" "+this.lastName+" "+city+" " +age ;
          } 
             } 
             const person1={ 
                firstName:"Nagendra",
                lastName:"Annam"
                } 
                const person2={ 
                firstName:"Rajendra",
                lastName:"penumalli"
                }
                console.log(person.fullName.call(person1,"bangalore",26) //printing all the statments.  
                
                
                
                // Arrow functions  
                
                let sum=add(a,b)=>{
                 let res1=a+b;
                 return res1; 
                 } 
                 let result=sum(10,23); 
                 console.log(result) ; 
                 
                 
                
                
                
               
            
                
                
     

