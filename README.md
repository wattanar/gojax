# gojax
Minimal Ajax Request for jQuery

# Setup

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>gojax example</title>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
	<link rel="stylesheet" href="gojax.min.js">
</head>
<body>
  <!-- Content -->
</body>
</html>
```

## Usage

for none form serialize();

```javascript
gojax('get', '/api/user/all', {data:'123'})
  .done()
  .fail();
```

for form serialize();
```javascript

gojax_f('post', '/api/user/save', '#form_id')
  .done()
  .fail();
```

## API Ref.

gojax(type: **string**, url: **string**, data: **object**);

| type        | url           | data  |
| ------------- |:-------------:| -----|
| required     | required | optional |


gojax_f(type: **string**, url: **string**, data: **string**);

| type        | url           | data  |
| ------------- |:-------------:| -----|
| required     | required |  required |

