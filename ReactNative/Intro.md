## REACT NATIVE

Before diving into the codes and concepts let us understand about the need of react native.Feel free to walk through little bit of history and about android and ios development.React Native was created and maintained by facebook team.We can see lots of real time React Native apps like instagram,facebook,pininterest etc...
WE know that developing both android and ios apps are like two sides of a coin.Because both uses its own formats and languages.

---

To make our work easier there comes our hero React Native .In React Native we can write a single code and its is converted to both android and ios implicitly ,we no need a seperate developer team to develop a single project in both android and ios.We can have the same result with React Native as we get with Native android and ios applications.

---

Error boundaries:
Whenever we face a compile time error the react dom unmounts the entire component and shows the error.Instead of that we can catch the errors and represent a fallback UI using two methods.\
They are:\
getDerivedStateFromError
componentDidCatch

getDerivedStateFromError:It is a static method which renders a fallback UI after the error is thrown.

componentDidCatch:It logs the error information.

Recap:
Errorboundaries are react componet which handles the javascript errors in its child coponent and represents it as a fall back UI and log those errors.