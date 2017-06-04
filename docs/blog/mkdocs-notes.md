## Mkdocs Notes for quick reference

### Code sample

```
class HelloWorld {

}
```

```sql
SELECT
Employees.EmployeeID,
Employees.Name,
Employees.Salary,
Manager.Name AS Manager
FROM
Employees
LEFT JOIN
Employees AS Manager
ON
Employees.ManagerID = Manager.EmployeeID
WHERE
Employees.EmployeeID = '087652';
```

### Adding an image

![Node](img/notes/data-structures/linked-list/node.png)

### Adding an image With defined Size

![Node](img/notes/data-structures/linked-list/node.png){: width=250px height=250px}

### Adding an image With defined Size and Centered

<center>![Node](img/notes/data-structures/linked-list/node.png){: width=150px height=150px}</center>

### Admonition Sample

!!! Title
    Note with Title but without quotes

!!! Admonition
    !!! note "Another Admonition inside"
        Note with Title but without quotes

!!! note "Title can be customised"
    Note with Title. Title can be customized for any type of Admonition

!!! summary
    Summary afasdf afasdf

!!! tldr
    this is some text

!!! tip
    this is some text

!!! important
    this is some text

!!! hint
    this is some text

!!! success
    this is some text

!!! check
    this is some text

!!! done
    this is some text

!!! warning
    this is some text

!!! caution
    this is some text

!!! attention
    this is some text

!!! failure
    this is some text

!!! fail
    this is some text

!!! missing
    this is some text

!!! danger
    this is some text

!!! error
    this is some text

!!! bug
    this is some text

!!! quote
    this is some text

!!! cite
    this is some text

### Sample To-DO list

- [x] one
- [x] two
- [ ] three
- [ ] four
    - [ ] four - a
    - [x] four - b
- [ ] Jupiter