## Hi there 👋
### _This is Aayush Vijay._

```node
app.get('/aayushvijay', (req, res) => {
    var url = "github.com/aayushvijay";
    request(url, (error, response, body) => {
        if (!error && response.statusCode == 200) {
            res.send("Hi there!");
        }
    });
});
```
#
### Glad to see you here.

