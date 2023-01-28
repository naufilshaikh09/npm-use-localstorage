# useLocalStorage - React Hook
useLocalStorage is a custom hook to get and set localstorage value.

## Installation 
```bash
# Using npm
npm i npm-use-localstorage
```

## Usage
useLocalStorage return two value. <br/>
1. First is localStorage value.
2. Second is function which helps to update localStorage value.

```bash
# Import from npm-use-localstorage
import useLocalStorage from "npm-use-localstorage";
 
# In the hook you need to pass two parameter(key, value) 
const [isUserLoggedIn, getSetLocalStorage] = useLocalStorage("isLoggedIn", "true");

# If you want to get localstorage value then just pass key
const [isUserLoggedIn] = useLocalStorage("isLoggedIn");

#If you want to set localstorage value then use second paramter which is function
getSetLocalStorage("isLoggedIn", "false");

```
