# Day07
Q2. https://github.com/rvsp/typescript-oops/blob/master/Practice/class-circle.md

Ans-

                class Circle{

                  constructor(radius){
                    this.radius=radius;
                    }

                    getRadius(){
                      return this.radius;
                      }

                     setRadius(newRadius){
                         this.radius=newRadius;
                    }
                }

                  let radius=1.0;
                  let color="red";

                   let c1=new Circle(parseFloat(radius));
                   console.log("First Radius:- "+c1.getRadius());
                   c1.setRadius(2.0);

                   console.log("Changed Radius:- "+c1.getRadius());
                   
           o/p- First Radius:- 1
                Changed Radius:- 2
                

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
