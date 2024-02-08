# IN Query

IN Query is used to search specific fields and returns documents that match the conditions specified. Here we are searching the `name` field for any records that match `John` and `Steve`:

```
{
    "name" : {
        $in : [
            "John-1",
            "Steve"
        ]
    }
}

```