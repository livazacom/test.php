# test.php

Buat you you dan you yang mau solve problem,

buat kamu yang bosen kerja biasa,

buat kamu yang penasaran kalao ada bug,

buat kamu yang mau beda,

join team software engineer Livaza

*entah kamu spesialis PHP Backend atau Frontend , gak masalah

--

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
