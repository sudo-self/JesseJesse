# <a href="https://JesseJesse.com">JesseJesse.com</a>
![Oct-06-2023 00-40-18](https://github.com/sudo-self/JesseJesse/assets/119916323/2af3c8e3-df33-45e2-aa0c-f320ee551671)
<header>

    <style>
                body{
                    background-image: url('https://sudo-self.github.io/assets/HTML&CSS.png');
                    background-repeat: no-repeat;
                    background-size: 100%;
                    background-attachment: fixed;
                }
    </style> 

</head>

```s
$ git clone https://github.com/sudo-self/jessejesse.git
$ cd JesseJesse

```
## App.js
```s
import logo from './logo.svg';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          <code>JesseJesse.com</code>
        </p>
        <a
          className="App-link"
          href="https://list.jessejesse.com"
          target="_blank"
          rel="noopener noreferrer"
        >
           ☎
        </a>
      </header>
    </div>
  );
}

export default App;
...

```
## Git pull and push changes
```s
git remote -v
git remote add upstream https://github.com/sudo-self/jessejesse.git
git fetch upstream
git checkout master
git merge upstream/master
git push

```
