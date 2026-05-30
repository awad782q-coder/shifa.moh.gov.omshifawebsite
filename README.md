# Awad PDF Platform

Files:

- index.html: admin page for upload and file management.
- script.js: Supabase connection, upload, QR insertion, download and delete logic.
- viewer.html: clean PDF viewer opened by QR.

Before deployment, edit these two files:

- script.js
- viewer.html

Replace:

```js
const SUPABASE_URL = "ضع رابط Supabase هنا";
const SUPABASE_ANON_KEY = "ضع مفتاح anon public هنا";
```

Use Project URL only, for example:

```js
const SUPABASE_URL = "https://xxxxxxxxxxxx.supabase.co";
```

Do not use `/rest/v1/` in the URL.
