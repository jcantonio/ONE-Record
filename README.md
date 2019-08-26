# ONE-Record modified schema

This repository contains modified schema specifications of ONE Record.
The modified version aims to be closer to the JSON schema specifications:

Done

- use of object and properties elements to represent objects
- use #ref when referencing other schema elements instead of types
- "type": "text" to "type": "string"
- "type": "numeric" to "type": "number"
- Use required Json Schema elements instead of required attributes

ToDo

- Use Array Json Schema elements instead of use of array like
  "OtherIdentifier": [{
  }],
- Use Date format Json Schema elements instead of use of datatime
- etc...

# ONE-Record

This repository contains the specification of ONE Record

> Please refer to the working_draft folder for the latest version

Structure of the specification

- API: API specification
- data-model: model in excel
- ontology: turtle formatted schema
- json schema: json files with schema descriptions, types and constraints (cardinality and mandatory vs optional)
- json blank values: json files wih blanked values "xxxxxxxx"

**Note**: Discussion on this specification is highly encouraged and please contact onerecord@iata.org with any comments or suggested improvements.
