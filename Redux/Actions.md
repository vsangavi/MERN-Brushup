## Actions

Actions are simply can be said as the changes or yhe events that is occuring in the applications\
Every actions must have a type and payload is optional,we can have the detailed description in the payload for the action.\
There are some convection to name the type of the actions but it is not compulsory to use it is only for easy identification .We are free to use what ever we want.

The actions basically look like :\
Example:\
{type:"COUNT/INCREMENT"}\
NOTE:The name is upto your convinent but as mentioned in the documentation you can specify like above ie:- a domain name and the function that could be better for usage .Having your action name in Capitalized can be very easy for accessing when our app grows.\
There are various ways in which we can create the actions.Like we can directly pass in our dispatch (UH! Bare with me !I will say about it in a seperate module) or we can have a seperate file in which we have our actions as a constants and then we can export it or we can have a function which returns a object of type.\
You can kindly refer this article for entire knowledge 
(https://daveceddia.com/redux-tutorial/)
