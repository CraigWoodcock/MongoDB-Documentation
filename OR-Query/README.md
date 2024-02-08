# OR Query

OR Query is used to search documents and returns records where either one of the conditions returns a match. Here we search for all documents where the name OR the email address match:

```
{
    $or : [
        {
            "name" : "john"
        },
        {
            "email" : "sangheeta@gmail.com"
        }
    ]
}
```