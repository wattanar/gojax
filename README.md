# gojax
Minimal Ajax Request for jQuery
## Usage
for none form serialize();

```javascript
gojax('get', '/api/user/all', {data:'123'})
  .done()
  .fail();
```

for form serialize();
```javascript

gojax_f('get', '/api/user/save', '#form_id')
  .done()
  .fail();
```
## API Ref.

gojax(type: **string**, url: **string**, data: **object**);
---
| type        | url           | data  |
| ------------- |:-------------:| -----:|
| required     | required | optional |
---

gojax_j(type: **string**, url: **string**, **data**: **string**);
---
| type        | url           | data  |
| ------------- |:-------------:| -----|
| required     | required |  required |
---
