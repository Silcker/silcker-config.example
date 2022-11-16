```yml
package: 
  build: "npm run build"
  start: "npm run start"
type: deploy
volumes: 
  path: local

```

| Package | key  | description    |
| :---:   | :---: | :---: |
|         | build   | Command to build the project   |
|         | start   | Command to start the project   |

| Type | value  | value purpose    |
| :---:   | :---: | :---: |
|         | deploy   | Deploys given project with config settings   |
|         | docker   | Generates docker config with config settings   |

| Volumes | key  | description    |
| :---:   | :---: | :---: |
|         | path   | Path to target directory  |
