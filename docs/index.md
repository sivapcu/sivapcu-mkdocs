## TO-DO

### Design Patterns

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
    - [ ] Siva
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley

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

### Admonition Sample

!!! note "Siva"
    this is some text

!!! summary
    this is some text

!!! tldr ""
    this is some text

!!! tip "Siva"
    this is some text

!!! important
    this is some text

!!! hint
    this is some text

!!! success "Siva"
    this is some text

!!! check
    this is some text

!!! done
    this is some text

!!! warning "Siva"
    this is some text

!!! caution
    this is some text

!!! attention
    this is some text

!!! failure "Siva"
    this is some text

!!! fail
    this is some text

!!! missing
    this is some text

!!! danger "Siva"
    this is some text

!!! error
    this is some text

!!! bug
    this is some text

!!! quote
    this is some text

!!! cite
    this is some text