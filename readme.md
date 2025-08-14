# Bible API
Getting bible verse data as json.

#### Get Verse Content:

```http
  GET /{book-number}/{chapter-number}/{verse-number}.json
```
##### Example:
```http
  GET /45/6/6.json
```

#### Get Verse Content by Language:

```http
  GET /{language}/{book-number}/{chapter-number}/{verse-number}.json
```
##### Example:

```http
  GET /45/6/6.json
```

#### Supported Languages

• malayalam
