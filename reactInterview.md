React has two main components first is smart component(containers) and second is
dumb(presentation component). Containers are very similar to components, the
only difference is that containers are aware of application state. If part of
your webpage is only used for displaying data (dumb) then make it a component.

Container == controller of MVC
Component == view of MVC

Redux == Global app state store management, reducer == VueX mutations

getDerivedStateFromError()
getDerivedStateFromProps()
getSnapshotBeforeUpdate()

render()
shouldComponentUpdate()
componentDidCatch()
componentDidUpdate()
componentWillUnmount()

React.PureComponent == functional stateless component, renders the same output for the same state and props.

const element = React.createElement('h1', {className: 'foo'}, 'hello world')
