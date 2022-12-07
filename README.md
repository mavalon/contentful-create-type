## How to use

1. Copy `.env.sample` as `.env` and update the values.
2. Run `yarn`
3. Update `json/fields.json` with content type definitions.
4. In the project directory, you can run `yarn start`.  This creates a Contentful Content Type from JSON if the type does not already exist.

JSON format:

```
{
  "sys": {
    "id": "id"
  },
  "name": "Name",
  "description": "A description",
  "displayField": "Display field id",
  "fields": [
    {
      "id": "id",
      "name": "Name",
      "type": "Symbol",
      ...[options]
    }
    ...
    ]
}
```