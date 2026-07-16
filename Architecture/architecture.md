# AWS Static Website Hosting Architecture

```
User
   │
   ▼
Web Browser
   │
   ▼
Amazon S3 Bucket
   │
   ▼
index.html
```

## Flow

1. User opens the website URL.
2. The browser sends a request to Amazon S3.
3. Amazon S3 returns the index.html file.
4. The browser displays the webpage.