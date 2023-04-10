### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?

React is a frontend webframework that uses Javascript. You would use it to build interactive user interfaces and web apps. The main reason it is used is to use less code. 

- What is Babel?

Babel is used to take modern code that may not work on all browsers and implement it. You can write short compact code and babel will translate it to work on most browsers.

- What is JSX?

JSX allows you to write HTML code in JS and insert it using react. It allows you to have componets use a certain structure. 

- How is a Component created in React?

Youi would create a seperate file in and write out the fuctions you would need and return them using JSX. 

- What are some difference between state and props?

state is updated by the component itself, where props are read only by the parent

- What does "downward data flow" refer to in React?

This would mean that data is passed down from the parent componets to there childeren. 

- What is a controlled component?

one that is controlled by state

- What is an uncontrolled component?

one that maintains its own internal state. 

- What is the purpose of the `key` prop when rendering a list of components?

it is use to dermine if the componet should be rerendered. 

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

because the index can change at any point. Would be better to use something that will never change or use the uuid libary. 

- Describe useEffect.  What use cases is it used for in React components?

this is telling react that you comonet needs to do something after everytime it renders. 

- What does useRef do?  Does a change to a ref value cause a rerender of a component?

creatng a reference of the DOM element

- When would you use a ref? When wouldn't you use one?

you will only use this when you want o call a fucntion that react doesnt allow you to control

- What is a custom hook in React? When would you want to write one?

custoemr hook is a hook created by you. You would use this when you have some repeating code over many function. Like you have something that you would use repeatedly. 
