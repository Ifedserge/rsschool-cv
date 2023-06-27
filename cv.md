# Siarhei Fedarau

## Front-End developer

***

### Contact information
*  **Phone:** +375 29 8518620 (viber, telegram)
*  **E-mail** isergefed@gmail.com

***

### About myself
My name is Sergey. I am 29 years old. In 2016 he graduated from Belarusian State University, but did not work in his specialty. For a long time he worked in the field of procurement and supply. But I didn't feel at ease. Recently got acquainted with frontend development and I fell in love! Now I have completed courses from "My IT School" Plus I signed up for RS-School. I want to consolidate the acquired skills, as well as learn something new.

***

### My Skills
* HTML, CSS, JS
* Git
* Superficially familiar with REACT, TS
* Figma (FrontEnd developer)

### Example of my code

``class Menu {
    constructor(){
        this.menu = null;
        this.init = this.init.bind(this);
    }
    create(){
        this.menu = document.createElement('div');
        this.menu.classList.add('menu__page');
        this.menu.innerHTML = `
            <img src='./img/menu.jpg' alt='menu'>
        `;
    }
    init(){
        this.create();
        return this.menu;
    }
}
const menu = new Menu();
const init = menu.init
export default init;``