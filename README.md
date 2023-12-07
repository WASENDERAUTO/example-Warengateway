## <div align="center">**WAREN GATEWAY - CYBEROREN 3.x**</div>
#### <div align="center">- **REST API AND WEBHOOK** -</div>

#### **# GIT CLONE :**
```bash
git clone https://github.com/WASENDERAUTO/example-Warengateway.git
```

### **# Example Body Array PHP**
<br>

**PHP Example Send Text :**
```php
$body = array(
    "api_key" => "xxxxxxxxxxxx",
    "receiver" => "6285xxx",
    "data" => array("message" => "Hello World")
);
```
**PHP Example Send Image :**
```php
$body = array(
    "api_key" => "b97b74f802c2802b94358267c160bbd282f5c384",
    "receiver" => "6285xxx",
    "data" => array(
        "url" => "https://i.ibb.co/QbmsBqs/code.png",
        "media_type" => "image",
        "caption" => "Hello World"
    )
);
```

#### **By :**
- <a href="https://github.com/jxxzy">**JXXZY** </a>
