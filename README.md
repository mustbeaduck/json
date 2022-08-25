<p> a fork of golang encoding/json </p>

<p> <b>why?</b> - cuz i didnt find a way to set <i>useNumber</i> for default <i>json.Unmarshal()</i> and i dont feel like creating <i>json.Decoder</i> instance</p>

<p> basically made <i>json.Unmarhsal()</i> to leave JSON numbers as <i>string</i> instead of parsing it to <i>float64</i> </p>

<p>in case i ever forget how to use it - just import this instead of default encode/json</p>

```go
    import "github.com/mustbeaduck/json"
```
