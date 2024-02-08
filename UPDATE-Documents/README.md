# UPDATE Documents

## UPDATE ONE

using intelliShell in Studio 3T - we can run the `updateOne()` command to update a single document. Here we update the name and email address:

```

db.student.updateOne(
    {
        "name" : "John-1"
    },
    {
        $set : {
            "name" : "John",
            "email" : "john-1@gmail.com"
        }
    }
)
```

## UPDATE MANY

we can run the `updateMany()` command to update multiple Documents. Here we update the name and email address of ALL documents that match the name field:

```
db.student.updateMany(
    {
        "name" : "John-1"
    },
    {
        $set : {
            "name" : "John-2",
            "email" : "john-2@gmail.com"
        }
    }
)

```

