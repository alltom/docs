# Object Names and Tags

We've identified two attributes that are generally useful, so we've given them special syntax. These attributes are `name` and `tag`.

## Name Selector ( `@` )

The name selector is used to select a specific named object from the Eve DB. Named objects are just objects with a `name` attribute specified. In the example program,`[@"my party"]` is shorthand for `[name: "my party"]`.

## Tag Selector ( `#` )

The tag selector is used for selecting a group of similar objects, i.e. objects with the same tag attribute. In the above example, we used `[#friend]`, which is shorthand for `[tag: "friend"]`.