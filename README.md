https://github.com/jphp-group/dn-dffi-ext   
https://github.com/HackMemory/dn-dffi-ext

# dn-dffi-ext

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
