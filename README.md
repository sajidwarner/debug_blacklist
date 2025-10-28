## 🧩 Debug Blacklist Configuration

To enhance security during debugging, this configuration hides sensitive data such as cookies, server variables, and environment variables from Laravel's error output.

### 🔒 Code Example
```php
'debug_blacklist' => [
    '_COOKIE' => array($_COOKIE),
    '_SERVER' => array($_SERVER),
    '_ENV' => array($_ENV),
],
