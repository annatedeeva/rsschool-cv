# Anna Tedeeva


## Contacts:
* Location: Izhevsk, Russia
* Phone: +7 9120230787
* Email: 7mylene@gmail.com
* GitHub: annatedeeva
* Discord: stezi (@annatedeeva)

## About Me:
Experience in sales. I am constantly learning and discovering new things. I am currently studying Frontend development and design.

## Skills:
* HTML
* CSS/SASS
* JavaScript(Basic)
* PHP (Basic)
* GitHub
* Scrum
* OOP 

## Code example:
KATA from CODEWARS: You were camping with your friends far away from home, but when it's time to go back, you realize that your fuel is running out and the nearest pump is 50 miles away! You know that on average, your car runs on about 25 miles per gallon. There are 2 gallons left.
Considering these factors, write a function that tells you if it is possible to get to the pump or not.
Function should return true if it is possible and false if not.
```javascript
const zeroFuel = (distanceToPump, mpg, fuelLeft) => {
  let poss = mpg - distanceToPump/fuelLeft;
  if (poss >= 0) {
    return true; 
  } else {
    return false;
  }
};
```