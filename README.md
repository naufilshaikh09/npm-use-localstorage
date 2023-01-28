# useLocalStorage - React Hook
useLocalStorage is custom hook to get and set localstorage.

## Installation 
```bash
# Using npm
npm i npm-use-localstorage
```

## Usage
```bash
# Import from npm-use-localstorage
import useLocalStorage from "npm-use-localstorage";
 
# In the hook you need to pass two parameter(key, value) 
const [isUserLoggedIn, getSetLocalStorage] = useLocalStorage("isLoggedIn", "true");
```
