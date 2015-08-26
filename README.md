```json
{
  "peerDependencies": {
  	"commonform-renderer": "1.x"
  }
}
```

All packages that peer-depend on this package expect the following arguments:

1. A Common Form

2. An `Object` map (from `String` to `String`) of fill-in-the-blank values

3. An `Object` of optional rendering parameters

Such packages return a rendering of the provided Common Form in some format or another, such as Markdown or HTML.

Compliant renderers do _not_ guarantee their arguments won't be modified.
