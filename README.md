# OOP-Lab-4
## World simulation!
Main entities:
- Humans:Can reproduce, the more humans -> more reproduction<br />
        Can kill each other in wars, the bigger the "evilness" attribute of the humans the more they kill each other<br />
        Can produce food and consume it when soil fertility = 0, if there is no food produced all the humans die<br />
        Have an impact on the environment, the more humans -> the faster the world temperature increases (global warming), this also decreases the world humidity <br />
        Can make the world's soil more fertile<br />
        Die when the water amount of the world = 100% or 0%<br />
        Have a set of world requirements that the world needs to adhere to for them to live<br />
- Sharks: Slow reproduction<br />
        Can kill each other but do so less often than humans<br />
        Die when the water amount of the world = 0%<br />
        Have a set of world requirements that the world needs to adhere to for them to live<br />
- Rats : The fastest reproduction<br />
        Can kill each other but do so rarely (less often than sharks/humans)<br />
        By eating crops they decrease the soil fertility<br />
        Die when the water amount of the world = 100% or 0%<br />
        Have a set of world requirements that the world needs to adhere to for them to live<br />
- Weapons : Produced by humans, the more humans->the bigger the weapon amount<br />
        Is used by humans in their "wars", the more weapons->the more they kill each other<br />
        Have a destruction level, just one weapon with a high enough destruction level can eliminate the entire human population!<br />
- Tsunami's : Have a destruction level and a duration<br />
        The bigger the destruction level and duration -> the more they increase the total water amount in the world and the world humidity <br />
        Each year they have a chance of 1/12 of happening<br />
- Earthquake's : Have a destruction level and a duration<br />
        The bigger the destruction level and duration -> the more they decrease fertility of the world's soil and increase the world's temperature <br />
        Each year they have a chance of 1/12 of happening<br />
        Just like in real life, earthquakes have a chance of producting tsunami's. So after an earthquake the probability of a tsunami happening immediately after it decreases
        from 1/12 to 1/8<br />
  
  Polymorphism can be seen in the following: the classes Humans, Sharks and Rats all override certain methods from the abstract class Organisms. We can 
  also see method overloading in the classes Natural Calamities, Earthquakes and Tsunami's. <br />
  Further information can be seen in this image of the simulation hierarchy
  ![Screenshot from 2022-10-17 21-24-42](https://user-images.githubusercontent.com/113375838/196381757-185e79b6-c5b9-4c17-96c1-74c2ec44eb1b.png)


        
      
        
        
