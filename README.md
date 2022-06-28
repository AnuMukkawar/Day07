# Day07
Q2. https://github.com/rvsp/typescript-oops/blob/master/Practice/class-circle.md

Ans-

                        class Circle{

                          constructor(radius,color){
                            this.radius=radius;
                            this.color=color;
                            }

                            getRadius(){
                              return this.radius;
                              }

                             setRadius(newRadius){
                                 this.radius=newRadius;
                            }

                            getColor(){
                              return this.color;
                              }

                             setColor(newColor){
                                 this.color=newColor;
                            }

                            getArea(radius){
                              return Math.PI*radius*radius
                              }

                            getCircumference(radius)
                            {
                              return 2*Math.PI*radius;
                              }
                        }

                          let radius=5.0;
                          let color="red";

                           let c1=new Circle(parseFloat(radius),color);
                           console.log("First Radius:- "+c1.getRadius());
                           c1.setRadius(2.0);

                           console.log("Changed Radius:- "+c1.getRadius());

                           console.log("First Color:- "+c1.getColor());
                           c1.setColor("Blue");

                           console.log("Changed Color:- "+c1.getColor());

                           console.log(c1);

                           console.log("Area of circle is- "+c1.getArea(radius).toFixed(2));

                           console.log("Circumference of circle is- "+c1.getCircumference(radius).toFixed(2));


o/p-
First Radius:- 5
Changed Radius:- 2
First Color:- red
Changed Color:- Blue
Circle { radius: 2, color: 'Blue' }
Area of circle is- 78.54
Circumference of circle is- 31.42


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
            
            
            
Q4. write a class to calculate uber price.

Ans-

              class UberPrice{

                  constructor(distance,price)
                  {
                    this.distance=distance;
                    this.price=price;
                  }

                 getDistance(){
                      return this.distance;
                    }

                 setPrice(newPrice){
                      this.price=newPrice;
                    }

                 getPrice(){
                      return this.price;
                    }
                }
                //distance is in km
                let distance=userInput;
                let price;

                let u=new UberPrice(parseInt(distance),price);
                console.log("Distance is: "+u.getDistance()+"km");
                 if(parseInt(distance)===1)
                {
                    price=10;
                  }else{
                          price=parseInt(distance)*10;
                    };

                u.setPrice(price);
                console.log("Price will be: Rs."+u.getPrice());

  
  i/p- 25
  o/p- Distance is: 25km
  Price will be: Rs.250
