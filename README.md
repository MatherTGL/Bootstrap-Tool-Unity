# Bootstrap-Tool-Unity

A simple tool that you can apply in your project to load MonoBehaviour classes. It is very easy to use and can be suitable for simple projects. You just need to implement an interface for MonoBehaviour and return the type of loading of this class you need (Object Importance and number of instances).

The tool sorts objects from super important and single, to ordinary in importance and multiple. It also has a separate load for UI objects, which is loaded last when all dependencies are present.

# The tool is currently in development and testing for future improvements.