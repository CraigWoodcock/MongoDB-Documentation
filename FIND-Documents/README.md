# FIND Documents

we can use intelliShell in Studio 3T to query the database,
the following command will return all entries where the name matches the criteria we specify.

```
db.student.find(

    
    {
            "name" : "John-1"
    }

)

```