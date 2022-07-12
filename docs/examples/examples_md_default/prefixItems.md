# Address

- [1. [Optional] Property `Address > address`](#address)
  - [1.1. Address > address > a number](#autogenerated_heading_2)
  - [1.2. Address > address > address item 1](#autogenerated_heading_3)
  - [1.3. Address > address > again a string](#autogenerated_heading_4)
  - [1.4. Address > address > finally an enum](#autogenerated_heading_5)

**Title:** Address

| Type                      | `object`                                                                  |
| ------------------------- | ------------------------------------------------------------------------- |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

| Property               | Pattern | Type  | Deprecated | Definition | Title/Description |
| ---------------------- | ------- | ----- | ---------- | ---------- | ----------------- |
| - [address](#address ) | No      | array | No         | -          | -                 |

## <a name="address"></a>1. [Optional] Property `Address > address`

| Type | `array` |
| ---- | ------- |

|                      | Array restrictions |
| -------------------- | ------------------ |
| **Min items**        | N/A                |
| **Max items**        | N/A                |
| **Items unicity**    | False              |
| **Additional items** | True               |
| **Tuple validation** | See below          |

| Each item of this array must be      | Description          |
| ------------------------------------ | -------------------- |
| [a number](#address_items_i0)        | -                    |
| [address item 1](#address_items_i1)  | followed by a string |
| [again a string](#address_items_i2)  | -                    |
| [finally an enum](#address_items_i3) | -                    |

### <a name="autogenerated_heading_2"></a>1.1. Address > address > a number

**Title:** a number

| Type | `number` |
| ---- | -------- |

### <a name="autogenerated_heading_3"></a>1.2. Address > address > address item 1

| Type | `string` |
| ---- | -------- |

**Description:** followed by a string

### <a name="autogenerated_heading_4"></a>1.3. Address > address > again a string

**Title:** again a string

| Type | `enum (of string)` |
| ---- | ------------------ |

Must be one of:
* "Street"
* "Avenue"
* "Boulevard"

### <a name="autogenerated_heading_5"></a>1.4. Address > address > finally an enum

**Title:** finally an enum

| Type | `enum (of string)` |
| ---- | ------------------ |

Must be one of:
* "NW"
* "NE"
* "SW"
* "SE"

**Example:** 

```json
[
    1600,
    "Pennsylvania",
    "Avenue",
    "NW",
    "Washington"
]
```

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans)