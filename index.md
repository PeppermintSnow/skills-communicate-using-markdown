# Hello

![Logo of Excel For Efficiency!](https://github.com/PeppermintSnow/ExcelForEfficiency/blob/website/images/head/logo.png?raw=true)

``` javascript
const matcha = {energyValue: 75, energyDelay: 30}

class Person {
  constructor(energy) {
    this.energy = energy;
  }

  drink(item) {
    setTimeout(item.energyDelay);
    this.energy += item.energyValue;    
  }
}

const me = new Person(Math.random() * 100);
const replenishEnergy = () => {
  if (me.energy < 50) {
    me.drink(matcha);
  }
}

```
