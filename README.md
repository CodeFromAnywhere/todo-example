This is a minimal example using ActionSchema Auth and ActionSchema Data to produce a fully functional full stack application where a user can manage todos.

TODO:

- Ensure logout/login/login results in the same user, always
- Ensure login token only gets access to needed stuff with scope `required` (not admin)
- Ensure website.yaml can generate in the order that is required.
- Ensure to replace website.yaml variables using `.env`
- Upsert Database: `database.yaml` -> `todo-schema.json` -> openapi url
- Upsert Auth Client: `upsertClient` -> `.env`

After I optimise for this, creating a full-stack todo app such as this can be done using a CLI.
