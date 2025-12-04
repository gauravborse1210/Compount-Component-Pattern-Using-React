# Compound Component Counter

This project demonstrates the Compound Component Pattern in React by building a flexible counter component. 

Instead of passing multiple props to a single component, the counter is broken into smaller child components that work together through React Context. 

The Counter component manages state with useState and provides count, increase, and decrease functions via CounterContext. 

Child components consume this context: Counter.Count displays the current value, Counter.Label renders a label, and Counter.

Increase and Counter.Decrease provide buttons to modify the count. 

These child components are attached as properties of the main Counter component, allowing developers to compose the counter in a declarative way inside App. 

This approach makes the counter more flexible, customizable, and easier to extend compared to a monolithic component that relies on many props.
