# AND Query

AND query is used to query multiple conditons, here we search for documents where the name and email match:

```
{
    $and : [
        {
            "name" : "Sangheeta"
        },
        {
            "email" : "sangheeta@gmail.com"
        }
    ]
}
```

