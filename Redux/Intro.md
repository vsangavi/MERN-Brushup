## Redux

As we all know that redux is the state management Library .Let us know little bit deep about redux her in this introduction.I will first say the overall performance of what redux does and then to each concepts specific

---

Basically without redux state management is really a tedious one for the medium and large applications ,because we use lots of states and live inputs from the users so for handling those things in a traditional way could be little tricky and confusing as days passes .to overcome this here comes Redux .In normal class or a functional Component states and props handling can be little higher like shifting the states if a child component has to pass something to the parents and so on .In redux we have a common store and all our states are put there if a state is changed ,it gets changed in that store therby changes every subsvribed part of that state.Sounds easy right!.

---

Now we can understand the key concepts in redux later lets implement them.

1. Action
2. Reducer
3. Store\

Action:
Actions are the events or changes that happens in our application. Is that simple ?yeah of course \

Reducers:
Reducers are a callback functions which has two arguments one is the state and other is the actions. \

Store:
AS name defines it Store stores our app states global.
