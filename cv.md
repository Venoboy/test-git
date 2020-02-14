# Junior Developer Resume
1. Yury Kolodich

1. Contact Info:
   * Phone: +375 29 8521702
   * Email: venomen@tut.by
   
1. Summary:  I'm actively learning front-end development. My current goal is to learn some
 modern technologies and developing techniques. I'm dependable, detail oriented, 
 ambitious and optimistic person. My aim for the next few years is to become strong senior 
 developer.
 
1. My skills:
   * CSS + HTML
   * JavaScript ES5 + ES6
   * React + Redux
   * Git
   * Photoshop
 
1. My last code example:
   ```javascript
   setChangeableField = (value, index) => {
     const newState = {...this.state};
     newState.users[index].changeableField = true;
     this.setState(newState);

     let user = this.state.users[index];

     this.setState(copyObj(this.state, copyObj(this.state.users[index], {changeableField: value})));
   };
   ```
1. My experience is some projects from courses, tasks at codewars, and my own freelance project -
some web application, which helps to get data from vk.com.