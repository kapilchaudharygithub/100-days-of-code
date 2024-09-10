# Topics Learned in Day-1

## 1. Creation and export of components.
```
const Demo = () => {
    return (
        <div>
            <p>Demo component</p>
            <input type="text" placeholder='Enter data'/>
        </div>
    );
};

export default Demo;
```

## 2. Importing and  Using of Components
```
import Demo from "./components/Demo"

const App=()=>{
  return (
    <>
     <h1>Hello</h1>
     <Demo/>
    </>
  )
}

export default App

```


## 3. Moving to the basic structure of Project
- Created 4 components inside components folder with basic demo code.
1. Header.jsx
```
const Header = () => {
    return (
        <div>
            <ul>
                <li>Home</li>
                <li>Others</li>
            </ul>
            
        </div>
    );
};

export default Header;
```
2. Contact.jsx
```
const Contact = () => {
    return (
        <div>
            <input type="text" />
            <button>Submit</button>
            
        </div>
    );
};

export default Contact;
```
3. Hero.jsx 
```

const Hero = () => {
    return (
        <div>
            <img src="https://cdn.fs.teachablecdn.com/uCoqmkHsS5OW2rTgbQIo"  />
        </div>
    );
};

export default Hero;
```
4. Footer.jsx
```
const Footer = () => {
    return (
        <div>
            <p>All Rights Reserved</p>
            
        </div>
    );
};

export default Footer;
```

- App.jsx
```
import Contact from './components/Contact';
import Footer from './components/Footer';
import Header from './components/Header';
import Hero from './components/Hero';
const App=()=>{
  return (
    <div>
     <Header/>
     <Hero/>
     <Contact/>
     <Footer/>
    </div>
  )
}

export default App;
```
