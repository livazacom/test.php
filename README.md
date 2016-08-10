# test.php
interview testing
email to lukluk@livaza.com

## 1. Create function to parse csv to JSON that should have ID as key

example csv :
```
"ID","Name","Address1","Address2"
"KJS0001","Hendro","Jakarta","Indonesia"
"KHO0001","Yanto","solo","Indonesia"
```

expected output:

```
{
  "KJS0001":{
    "Name':"Hendro",
    "Address":["Jakarta","Indonesia"]
  },
  "KHO0001":{
    "Name":"Yanto",
    "Address":["solo","Indonesia"]
  }
}
```

```

$json = parseCSV2JSON('product.csv');
echo $json;
```
