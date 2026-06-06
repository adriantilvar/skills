# {RootComponent}

A short description of the component and its purpose in the system.

It is responsible for:
- Responsibility A
- Responsibility B
- Responsibility C

The responsibilities must represent high-level functionality, not technical details.

---

## Anatomy

```txt
{RootComponent}
├─ {SubcomponentA}
├─ {SubcomponentB}
│  ├─ {NestedSubcomponentB1}
│  └─ {NestedSubcomponentB2}
└─ {SubcomponentC}
```

---

## {RootComponent}

A short description of the component's purpose and responsibility/ownership boundary. End with 'Renders a `<component>`' or 'Does not render HTML'.

### Props

| Prop | Type | Default |
| ---- | ---- | ------- |
| ...  | ...  | ...     |

Include only props specific to this component. Do **NOT** include default props like `className` or `children`. If there are no special props, omit this section.

### Types (include only when present in prop types)

```ts
type ExamplePropType = {};
```

Include this section only when there are props with a special type associated with their values. If there are no special types, omit this section.

### Notes

- Additional behavioral notes
- Composition constraints
- Ownership boundaries
- Special relationships with other components (beyond composition)

Include this section only if there is info that is not common knowledge or intuitive (e.g. that the component can consume a context). It could also be constraints, assumptions, or limitations that are not straightforward.

---

## {SubcomponentA}

...

---

## Plugins (omit if there are no plugins)

## {PluginName}

A description of the plugin and its purpose. End with 'Renders a `<component>`' or 'Does not render HTML'.

It provides functionality for:
- Functionality A
- Functionality B

### Props

| Prop | Type | Default |
| ---- | ---- | ------- |
| ...  | ...  | ...     |

### Types

```ts
type ExamplePluginProps = {};
```

### Notes

- Assumptions
- Constraints
- Limitations

If the notes don't provide any value beyond the API and the description, omit this section.
