# Swagger-Multi-File
Split a large OpenAPI (swagger) document into multiple files

### Clone the repository and start using it

```
* npm install
* npm run start
* Open http://localhost:3000/api/docs/
```

### Creating Swagger API documentation from multiple yaml files

1. Add `yaml` files for `defenitions` in swagger/definitions/index.yaml
2. Add `yaml` files for `paths` in swagger/paths/index.yaml
3. Create single json file using `swagger-cli` command. `npm run doc:generate`
4. Serve the html content using `swagger-ui-express` via express api (refer `app.ts`)
