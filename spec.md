The main part of the specification is the `Checklist` type. It is as follows:

```js
{
	// The name of the checklist
	"name": "My List",
	"items": [
		// ListItems for individual items or Checklists for sublists go here
	]
}
```

The `ListItem` typed is defined this way:

```js
{
	"name": "My Item",
	"completed": false
}
```

The JSON object stored into Local Storage looks like this:

```js
[
	// Checklists go here
	{
		"name": "list name here",
		"items": [
			// Checklists or ListItems go here
		]
	}
	// More Checklists can go here
]
```
