## What are the two common operations that we will set in the handler?
handler.get() method which is used for getting property of a value.
handler.set() method which is used for setting property for a value.


## What do you have to make sure you are doing with every Get to insure the value does not become undefined?
By using const and let instead of var for defining variables in our application and also check if the property existing by applying condition obj.prop !== undefined to compare against undefined directly.


## What are some of the benefits of the proxy object that we are using in our structure for applications?
The proxy object is used to prevent from throwing error if the setting value of property does not satisfy a specific condition and it validate for correct property.
