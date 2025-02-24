# webkert


1. Az eszközök telepítéséhez:
Visual Studio Code: https://code.visualstudio.com/download
Node v20.11.1 (LTS): https://nodejs.org/en/blog/release/v20.11.1
NVM: 
https://github.com/nvm-sh/nvm
GitHub - nvm-sh/nvm: Node Version Manager - POSIX-compliant bash script to manage multiple active no

2. open terminal
3. npm install - g @angular/cli
4. ng new webKertApp
5. cd webKertApp
6. ng serve

## app.component.ts
```ts
import { Component } from '@angular/core';
import { RouterOutlet } from '@angular/router';

@Component({
  selector: 'app-root',
  imports: [RouterOutlet],
  templateUrl: './app.component.html',
  styleUrl: './app.component.css'
})
export class AppComponent {
  title : string;
  date : number;

  constructor(){
    this.title = "Webshop";
    this.date = 2025;
  }

  addTitleAndDate(title: any, date : any) {
    console.log(title + date);
  }
}
```
7. Exensions: sass - https://marketplace.visualstudio.com/items?itemName=syler.sass-indented

## styles.sass
```css
/* You can add global styles to this file, and also import other style files */


html
    background-color: red
```
