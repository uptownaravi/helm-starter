# helm starter chart
## This is a sample helm starter chart which can be used as a template while doing helm create

## starter chart is created from the sample nginx helm chart

### usage


- Clone this repository

- Create a environment variable $XDG_DATA_HOME which points to a folder of your choice and move sample-starter-chart folder from the cloned repository to $XDG_DATA_HOME/helm/starters path.

- Starter charts needs to be available in the path so that the helm create command can refer this template

- Run the command to create a new chart from the template

  `
  $ helm create myapp --starter sample-starter-chart
  `

- This creates a myapp chart replacing the <CHARTNAME> values in the starter chart template.

