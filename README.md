# My First README

Repo explaining README.md 
## Welcome to Tic-Tac-Toe Beta

## Steps to Install on local computer
1. Go to [repo](https://github.com/SEI-ATL/tic-tac-toe.git) on Github https://github.com/SEI-ATL/tic-tac-toe
2. `fork` and `clone` repo
3. Clone to local machine
```text
git clone https://github.com/SEI-ATL/tic-tac-toe.git
```
4. Go to `tic-tac-toe` directory
5. Open `index.html` in browser
```text
open index.html
```
```html
<div class="grid"> <!--background-->
    <div class="row"> <!--lines going across the grid -->
      <div class="box" id="box-1"></div> <!--boxes within each row -->
      <div class="box" id="box-2"></div>
      <div class="box" id="box-3"></div>
    </div>
  <div class="row">
    <div class="box" id="box-4"></div>
    <div class="box" id="box-5"></div>
    <div class="box" id="box-6"></div>
  </div>
  <div class="row">
    <div class="box" id="box-7"></div> 
    <div class="box" id="box-8"></div>
    <div class="box" id="box-9"></div>
  </div>
  ```
```css
h1 {
  color: purple;
}
.grid {
  display: table;
  position: center;
}
.box:hover {
  background-color: lightgray;
} 
```

```javaScript
box3.addEventListener('click', () => { 
    box3.textContent = player;
    if(player === 'X') {
        
        player = 'O';
    }  else {
        
        player = 'X';
    }
});
```
