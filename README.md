# Get-all-URLs-from-a-website
:seedling:
## Setting
```
require_once __DIR__ . '/get_all_urls_website.php';

$url = '[URL_WEBSITE]';
$depth = 2; // default 5, depth of the URL
$get_urls = new Get_all_URLs($url, $depth);
$get_urls->run();
```

## Demo
> - N: number
> - HTTP_STATUS: HTTP Status
> - TIME: time load page, seconds
> - DEPTH: depth of the URL
> - URL: Current URL

![](https://i.imgur.com/NZpAOvE.png)  
