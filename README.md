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
"ID","Name","Address1","Address2","Skill"
"KJS0001","Hendro","jakartA","Indonesia","Nodejs,PHP"
"KHO0001","Yanto","soLo","Indonesia","Photosope,Corel"
```

expected output:

```
{
  "KJS0001":{
    "Name':"Lukluk",
    "Address":{
        "city":"Jakarta",
        "country":"Indonesia"
    },
    "skill":["Nodejs","PHP"]
  },
  "KHO0001":{
    "Name":"Yanto",
    "Address":{
        "city":"Solo",
        "country":"Indonesia"
    },
    "skill":["Photosope","Corel"]
  }
}
```

```

$json = parseCSV2JSON('product.csv');
echo $json;
```
