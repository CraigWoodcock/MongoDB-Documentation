# Delete All Records:

in intelliShell in Studio 3T, we can run this command to remove all records from the collection:

 - As there is no condition, it will remove all.

```
db.student.remove(
    
    {
                
    }
    
)


```

## Delete Many:

By setting conditions, we can delete all records that match the conditions:
 - Here we delete all records where the name matches our criteria.

```
db.student.remove(
    
    {
            "name" : "John-1"         
    }
    
)

```

    