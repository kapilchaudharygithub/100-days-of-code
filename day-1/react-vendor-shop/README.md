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