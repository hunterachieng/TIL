# React <Outlet/>

React offers a new way to allow a developer to render various pages with certain contents while omitting the content on other pages.

# Example
```
import React from 'react';
import '../styles/App.css';
import Login from './login/Login';
import Products from './products/Products';
import Navbar from './sidebar/Sidebar';
import { BrowserRouter, Route, Routes } from 'react-router-dom';
import { Outlet } from 'react-router-dom';


const SidebarLayout = ()=>(
  <>
<Navbar/>
<Outlet/>
</>
)



function App() {
  return (
  
   <BrowserRouter>
       <div className="App">
     <Routes>
    <Route element={<SidebarLayout/>}>
    <Route  exact path="/products" element={<Products/>} />
    </Route>
    <Route  exact path="/" element={<Login/>} />
  </Routes>
   
    </div>
    </BrowserRouter>
   
  );
}

export default App;
```

In the above example, the uppemost function  `SidebarLayout()` specifies the navba and the outlet and in the next `App()` function,

the `SidebarLayout()` within  a `<Route>` element whose children that the routes within the imported Navbar component. 

The `<Login/>` element is not a child of the Sidebar function and it will be rendered without having a navbar attached to it.
