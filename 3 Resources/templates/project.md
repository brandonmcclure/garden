# <% tp.file.title %>

#project

## Tasks defined for this project

```dataviewjs
const query = `
not done
path includes ${dv.current().file.path}
# you can add any number of extra Tasks instructions, for example:
group by heading
`;

dv.paragraph('```tasks\n' + query + '\n```');
```

## Related Notes

```query
tag:#project <% tp.file.title %>
```
