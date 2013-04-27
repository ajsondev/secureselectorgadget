## Secure SelectorGadget

Loading non-SSL SelectorGadget into SSL websites doesn't work - this is the solution.  It's hosted at [Heroku](http://selectorgadget.herokuapp.com/).

### Usage:

Copy 'n' paste this as a bookmarklet: [SecureSelectorGadget]("javascript:(function()%7Bvar s%3Ddocument.createElement(%27div%27)%3Bs.innerHTML%3D%27Loading...%27%3Bs.style.color%3D%27black%27%3Bs.style.padding%3D%2720px%27%3Bs.style.position%3D%27fixed%27%3Bs.style.zIndex%3D%279999%27%3Bs.style.fontSize%3D%273.0em%27%3Bs.style.border%3D%272px solid black%27%3Bs.style.right%3D%2740px%27%3Bs.style.top%3D%2740px%27%3Bs.setAttribute(%27class%27,%27selector_gadget_loading%27)%3Bs.style.background%3D%27white%27%3Bdocument.body.appendChild(s)%3Bs%3Ddocument.createElement(%27script%27)%3Bs.setAttribute(%27type%27,%27text/javascript%27)%3Bs.setAttribute(%27src%27,%27https://selectorgadget.herokuapp.com/js/selectorgadget.js%27)%3Bdocument.body.appendChild(s)%3B%7D)()%3B")