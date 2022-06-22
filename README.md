# Day07

Q3. Write a “person” class to hold all the details.

Ans-

        class Person{

          constructor(firstname,lastname,profession,city)
          {
            this.firstname=firstname;
            this.lastname=lastname;
            this.profession=profession;
            this.city=city;
          }

            getFirstName(){
                return  this.firstname;
            }
            getLastName(){ 
                return this.lastname;
            }

            getProfession(){
                return this.profession;
            }

            getCity(){
                return  this.city;
            }

        }
          let p1=new Person("Anuja","Mukkawar","Engineer","Latur");

            console.log("First Name: "+p1.getFirstName()+" \n"+"Last Name: "+p1.getLastName()+" \n"+"Profession: "+p1.getProfession()+" \n"+"City: "+p1.getCity());
