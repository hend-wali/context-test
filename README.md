useContext takes the context object (created by React.createContext) as an argument and returns the current context value for that context. If the context provider is higher up in the component tree, useContext will get the value provided by the nearest MyContext.Provider ancestor.

This pattern is especially useful for avoiding prop drilling (passing props through many layers of components) and making shared state or functionality accessible to deeply nested components
#   c o n t e x t - t e s t  
 