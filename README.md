https://github.com/jphp-group/dn-dffi-ext   
https://github.com/HackMemory/dn-dffi-ext

# dn-dffi-ext

[![Видео](https://github.com/user-attachments/assets/54dc75c6-d54a-4972-b978-a44818affae1)](https://github.com/jphp-group-community/dn-dffi-ext/releases/download/0.4/DevelNext.xtreme3d.2.mp4)


## static DFFI
```php 
callFunction($lib, $returnType, $functionName, Array $args, Array $types);
```
```php
addSearchPath($lib, $path);
```

## DFFIReferenceValue
```php
DFFIReferenceValue($type);
```
```php
DFFIReferenceValue($type, $value);
```
```php
setValue($value);
```
```php
getValue();
```

## DFFIStruct
```php
DFFIStruct($name, Array $types);
```
```php
getResponse();
```

## Типы
* String
* WString
* Int
* Long
* Float
* Double
* Struct
* Reference

DevelNext Foreign Function Interface
