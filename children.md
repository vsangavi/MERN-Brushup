## {this.children.props}

For instance let us take an example of a todo component called from the App component.The props is passed to the todo component from app component.
<Todo list={this.state.list}> <p> Hello child</p></Todo>

In Todo component we are accessing like {this.props.children }this access the Hello child that we are having in the App component.

children is a special property of React components which contains any child elements defined within the component,