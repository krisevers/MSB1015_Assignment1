# MSB1015 Assignment1
This project answers the question 'What are the number of proteins per species?'. SPARQL query language is used to request the information 
needed to answer the question from the Wikidata database. A HTML file is created that is readable by browser software and uses a D3js 
visualization template of a bubble plot to visualize the results.
### Contribution
Contributors are allowed if they are willing to be involved in the project and understand the goal and the future steps of the project.
### Execution
RUN Assignment_1.html IN BROWSER SOFTWARE.

## Pseudocode
- Query string is defined.
- SPARQL query is requested.
- Response is transformed to a .json object
- .json is simplified
- Create a function to visualize the response
  - Data preparation for D3js
  - Creation of D3js object as .svg

## Authors
- Egon Willighagen - provided the .html template and the sparql template.
- Kris Evers - produced the main body of the code for the sparql query and the visualization of the data.
