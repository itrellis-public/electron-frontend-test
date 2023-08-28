
## Test
### This does not have to be a pretty presentation

A very basic implementation for everything below is fine. Do not spend time trying to make the views pretty. This project is not judging CSS / third party componenet library usage.

* Create an electron applicaton that will use react and typescript for rendering.
    * You can use a boilerplate project if you want
* [Install three.js](https://threejs.org/docs/index.html#manual/en/introduction/Installation)
    * Yes, there is a library you can use for threejs and react. For the purposes of this test this will not be an option
* [Intstall plotly](https://plotly.com/javascript/react/#quick-start)
* Create a basic app component that will contain a header and a body.
* Create 2 views
    * Data View
    * ThreeJS View
* Create a header component that will live inside the app componenet and will contain two links to your views.
    * Use react router
* Data View
    * Use the data.json file found to plot the data on a plotly graph. A simple bar or line graph will do. Plot the lowest, average, and highest income.
* ThreeJS View
    * Create a component that will render a [threejs example](https://threejs.org/examples/#webgl_shadowmesh). You can pick any example. The goal here will be to show an understanding of how a react component and its hooks will be used to properly mount and dismount a threejs example.
* Submit Project