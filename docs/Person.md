
# Type: person


represents a person, such as a researcher

URI: [nmdc:Person](https://microbiomedata/meta/Person)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[NamedThing]^-[Person&#124;id:string;name(i):string%20%3F;description(i):string%20%3F;alternate_identifiers(i):string%20*])

## Parents

 *  is_a: [NamedThing](NamedThing.md) - a databased entity or concept/class

## Referenced by class


## Attributes


### Own

 * [person➞id](person_id.md)  <sub>REQ</sub>
    * range: [String](types/String.md)

### Inherited from named thing:

 * [id](id.md)  <sub>REQ</sub>
    * Description: A unique identifier for a thing. Must be either a CURIE shorthand for a URI or a complete URI
    * range: [String](types/String.md)
    * inherited from: None
 * [name](name.md)  <sub>OPT</sub>
    * Description: A human readable label for an entity
    * range: [String](types/String.md)
    * inherited from: None
 * [description](description.md)  <sub>OPT</sub>
    * Description: a human-readable description of a thing
    * range: [String](types/String.md)
    * inherited from: None
 * [alternate identifiers](alternate_identifiers.md)  <sub>0..*</sub>
    * Description: Non-primary identifiers
    * range: [String](types/String.md)
    * inherited from: None

### Domain for slot:

 * [person➞id](person_id.md)  <sub>REQ</sub>
    * range: [String](types/String.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Comments:** | | not yet in use |
