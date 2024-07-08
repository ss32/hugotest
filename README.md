# buildlogs

Static site generation using [Hugo](https://gohugo.io)



```bash
cd site
hugo server -D
```

```
Start building sites … 
hugo v0.92.2+extended linux/amd64 BuildDate=2023-01-31T11:11:57Z VendorInfo=ubuntu:0.92.2-1ubuntu0.1
ERROR 2024/07/08 07:32:00 render of "section" failed: execute of template failed: template: _default/list.html:10:15: executing "main" at <partial "cards" .>: error calling partial: execute of template failed: template: partials/cards.html:8:23: executing "partials/cards.html" at <partial "randImage" .>: error calling partial: "/tmp/hugotest/site/themes/quint/layouts/partials/randImage.html:5:31": execute of template failed: template: partials/randImage.html:5:31: executing "partials/randImage.html" at <math>: can't evaluate field Rand in type interface {}
Error: Error building site: failed to render pages: render of "page" failed: "/tmp/hugotest/site/themes/quint/layouts/_default/single.html:2:82": execute of template failed: template: _default/single.html:2:82: executing "main" at <math>: can't evaluate field Rand in type interface {}
Built in 12 ms
```
