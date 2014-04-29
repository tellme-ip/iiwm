Integrated Industrial Workplace Model
=====================================

The following example illustrates the general idea (using the JSON binding):

```
{
  "category": { // category can be “tool”, “place”, etc.
    "id": { // a unique identifier within this model, e.g., “hammer7849”
      "type": "something", // e.g., “hammer”
      "place": "room42", // specifying location (the id of a place in this model)
      "property1": "value", // further specifying the hammer, e.g., which marker
      "property2": [ "value1", "value2", "value3" ],
      "property3": { "property4": "value4" },
      … // more properties, invent a new property name for a specific category
         // and you get to decide what it means
    }
  },
  … // more categories, invent a new category name and you get to decide its contents
}
```

The JSON-LD and XML bindings are intended to closely reflect the JSON binding.

See the `example` directory for examples of all three bindings.

To extend the model, you may edit the example directly (if you have access), edit your own fork and create a pull request, or create an issue describing what it is that you would like to be added or changed.
