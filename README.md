<a name="Logger"></a>

# ProLogger
ProLogger is a simple logger with extension support
Look at test.js for examples ;)

# Documentation

## Logger
**Kind**: global class  

* [Logger](#Logger)
    * [.noprefix](#Logger+noprefix) : <code>bool</code>
    * [.log(data, options)](#Logger+log) ⇒ <code>this</code>
    * [.warn(data, options)](#Logger+warn) ⇒ <code>this</code>
    * [.error(data, options)](#Logger+error) ⇒ <code>this</code>
    * [.info(data, options)](#Logger+info) ⇒ <code>this</code>
    * [.success(data, options)](#Logger+success) ⇒ <code>this</code>
    * [.setLevels(levels)](#Logger+setLevels) ⇒ <code>this</code>
    * [.removeLevel(level)](#Logger+removeLevel) ⇒ <code>this</code>
    * [.setCallback(event, callback)](#Logger+setCallback) ⇒ <code>this</code>

<a name="Logger+noprefix"></a>

### logger.noprefix : <code>bool</code>
Disable prefix by default

**Kind**: instance property of [<code>Logger</code>](#Logger)  
**Access**: public  
<a name="Logger+log"></a>

### logger.log(data, options) ⇒ <code>this</code>
Advance console.log

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| data | <code>any</code> | data |
| options | <code>object</code> \| <code>undefined</code> \| <code>any</code> | Options || disable [PREFIX] |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+warn"></a>

### logger.warn(data, options) ⇒ <code>this</code>
Advance console.warn

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| data | <code>any</code> | data |
| options | <code>object</code> \| <code>undefined</code> \| <code>any</code> | Options || disable [PREFIX] |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+error"></a>

### logger.error(data, options) ⇒ <code>this</code>
Advance console.error

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| data | <code>any</code> | data |
| options | <code>object</code> \| <code>undefined</code> \| <code>any</code> | Options || disable [PREFIX] |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+info"></a>

### logger.info(data, options) ⇒ <code>this</code>
Advance console.info

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| data | <code>any</code> | data |
| options | <code>object</code> \| <code>undefined</code> \| <code>any</code> | Options || disable [PREFIX] |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+success"></a>

### logger.success(data, options) ⇒ <code>this</code>
Analog of info but green

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| data | <code>any</code> | data |
| options | <code>object</code> \| <code>undefined</code> \| <code>any</code> | Options || disable [PREFIX] |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+setLevels"></a>

### logger.setLevels(levels) ⇒ <code>this</code>
Add or replace log levels

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| levels | <code>array</code> \| <code>string</code> | If set (array) or add (string) the level |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+removeLevel"></a>

### logger.removeLevel(level) ⇒ <code>this</code>
Remove log level

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| level | <code>string</code> | Level whitch you want to remove |
| [options.level] | <code>string</code> | Log with custom log level |
| [options.noconvert] | <code>bool</code> | Disable timestamp |
| [options.prefix] | <code>bool</code> | Enable prefix |

<a name="Logger+setCallback"></a>

### logger.setCallback(event, callback) ⇒ <code>this</code>
Bind callback to the event

**Kind**: instance method of [<code>Logger</code>](#Logger)  
**Returns**: <code>this</code> - this  

| Param | Type | Description |
| --- | --- | --- |
| event | <code>string</code> | Event like log/error/success/warn etc. |
| callback | <code>function</code> | Function to bind to the event |

