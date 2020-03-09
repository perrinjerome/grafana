+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "getLogLevel"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
draft = true
+++

## getLogLevel() function

### getLogLevel() function

Returns the log level of a log line. Parse the line for level words. If no level is found, it returns `LogLevel.unknown`<!-- -->.

Example: `getLogLevel('WARN 1999-12-31 this is great') // LogLevel.warn`

<b>Signature</b>

```typescript
export declare function getLogLevel(line: string): LogLevel;
```
<b>Import</b>

```typescript
import { getLogLevel } from '@grafana/data';
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  line | <code>string</code> |  |

<b>Returns:</b>

`LogLevel`
