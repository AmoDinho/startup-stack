# startup-stack

In 2018 I've been teaching myself Product Design, Front-Engineering and Data Science. One of the core outcomes I was seeking was a pathway to set up infrasturce for a startup to solve their business problem using technology. All business problems are different, but due to trying to start a componay in 2018, your offering as a company needs to be spectacular while solely making things people love. 

We will use a fictious business use cases to build out parts of our infrastructre, which will span a serverless backend api, a front-end for the web, how to structure data science experiments, the backend for your Model and the design system for your company to be used across your brand and front-end.  

TO-DO:
 - [ ] Make a diagram
 - [ ] Use Lunar Tour as the Example
 - [ ] Create examples of each stack

The vision:

```
Back-End (App)
Lib
   schema
     types
     Resolvers
          queries
          mutations
dynamo
    globalFunctions
handler.js
serverless.yml
webpack

Back-End (ML Layer)
Model
  Weights
  model.py
Server.py

Or SageMaker similar platform

Data Science
Juypter Notebook
Anaconda Env
Data Warehouse

Front-end
Vue
components
   App.vue
   Login
   ItemList
   Item
   ItemDetail 
Or React


Design System
   Colors
   Typography
    Tone & Style
   Components
      Buttons
      Modals
      Nav

Design system in Figma/Sketch/PS and Design System Package

```
