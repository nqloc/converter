> Web tool for converting JSON to XML and and vice versa 
>
> [Live Demo](https://nqloc.github.io/tools/converter/)  [Codepen](https://codepen.io/nqloc/pen/povzrRV)

---

1. [JSON to XML](#json-to-xml)
2. [XML to JSON](#xml-to-json)

## JSON to XML
### Input
```
{
    "employees": {
        "employee": [
            {
                "firstName": "John",
                "lastName": "Doe"
            },
            {
                "firstName": "Anna",
                "lastName": "Smith"
            },
            {
                "firstName": "Peter",
                "lastName": "Jones"
            }
        ]
    }
}
```
### Output
```
<employees>
    <firstName>John</firstName>
    <lastName>Doe</lastName>
</employees>
<employees>
    <firstName>Anna</firstName>
    <lastName>Smith</lastName>
</employees>
<employees>
    <firstName>Peter</firstName>
    <lastName>Jones</lastName>
</employees>
```

## XML to JSON
### Input
```
<employees>
    <firstName>John</firstName>
    <lastName>Doe</lastName>
</employees>
<employees>
    <firstName>Anna</firstName>
    <lastName>Smith</lastName>
</employees>
<employees>
    <firstName>Peter</firstName>
    <lastName>Jones</lastName>
</employees>
```
### Output
```
{
    "employees": {
        "employee": [
            {
                "firstName": "John",
                "lastName": "Doe"
            },
            {
                "firstName": "Anna",
                "lastName": "Smith"
            },
            {
                "firstName": "Peter",
                "lastName": "Jones"
            }
        ]
    }
}
```

# Like my stuff?

Would you like to buy me a coffee or send me a tip?
While it's not expected, I would really appreciate it.

[![Paypal](https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png)](https://paypal.me) <a href="https://www.buymeacoffee.com/QGs0BZ3" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
