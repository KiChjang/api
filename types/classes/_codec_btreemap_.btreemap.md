[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["codec/BTreeMap"](../modules/_codec_btreemap_.md) › [BTreeMap](_codec_btreemap_.btreemap.md)

# Class: BTreeMap <**K, V**>

## Type parameters

▪ **K**: *[Codec](../interfaces/_types_codec_.codec.md)*

▪ **V**: *[Codec](../interfaces/_types_codec_.codec.md)*

## Hierarchy

  ↳ [CodecMap](_codec_map_.codecmap.md)‹K, V›

  ↳ **BTreeMap**

## Implements

* [Codec](../interfaces/_types_codec_.codec.md)

## Index

### Constructors

* [constructor](_codec_btreemap_.btreemap.md#constructor)

### Properties

* [#KeyClass](_codec_btreemap_.btreemap.md##keyclass)
* [#ValClass](_codec_btreemap_.btreemap.md##valclass)
* [#type](_codec_btreemap_.btreemap.md##type)
* [registry](_codec_btreemap_.btreemap.md#registry)
* [size](_codec_btreemap_.btreemap.md#size)

### Accessors

* [encodedLength](_codec_btreemap_.btreemap.md#encodedlength)
* [hash](_codec_btreemap_.btreemap.md#hash)
* [isEmpty](_codec_btreemap_.btreemap.md#isempty)

### Methods

* [clear](_codec_btreemap_.btreemap.md#clear)
* [delete](_codec_btreemap_.btreemap.md#delete)
* [eq](_codec_btreemap_.btreemap.md#eq)
* [forEach](_codec_btreemap_.btreemap.md#foreach)
* [get](_codec_btreemap_.btreemap.md#get)
* [has](_codec_btreemap_.btreemap.md#has)
* [set](_codec_btreemap_.btreemap.md#set)
* [toHex](_codec_btreemap_.btreemap.md#tohex)
* [toHuman](_codec_btreemap_.btreemap.md#tohuman)
* [toJSON](_codec_btreemap_.btreemap.md#tojson)
* [toRawType](_codec_btreemap_.btreemap.md#torawtype)
* [toString](_codec_btreemap_.btreemap.md#tostring)
* [toU8a](_codec_btreemap_.btreemap.md#tou8a)
* [with](_codec_btreemap_.btreemap.md#static-with)

## Constructors

###  constructor

\+ **new BTreeMap**(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `type`: "BTreeMap" | "HashMap", `keyType`: [Constructor](../interfaces/_types_codec_.constructor.md)‹K› | keyof InterfaceTypes, `valType`: [Constructor](../interfaces/_types_codec_.constructor.md)‹V› | keyof InterfaceTypes, `rawValue`: any): *[BTreeMap](_codec_btreemap_.btreemap.md)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[constructor](_codec_map_.codecmap.md#constructor)*

*Defined in [packages/types/src/codec/Map.ts:101](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L101)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) |
`type` | "BTreeMap" &#124; "HashMap" |
`keyType` | [Constructor](../interfaces/_types_codec_.constructor.md)‹K› &#124; keyof InterfaceTypes |
`valType` | [Constructor](../interfaces/_types_codec_.constructor.md)‹V› &#124; keyof InterfaceTypes |
`rawValue` | any |

**Returns:** *[BTreeMap](_codec_btreemap_.btreemap.md)*

## Properties

###  #KeyClass

• **#KeyClass**: *[Constructor](../interfaces/_types_codec_.constructor.md)‹K›*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[#KeyClass](_codec_map_.codecmap.md##keyclass)*

*Defined in [packages/types/src/codec/Map.ts:97](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L97)*

___

###  #ValClass

• **#ValClass**: *[Constructor](../interfaces/_types_codec_.constructor.md)‹V›*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[#ValClass](_codec_map_.codecmap.md##valclass)*

*Defined in [packages/types/src/codec/Map.ts:99](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L99)*

___

###  #type

• **#type**: *string*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[#type](_codec_map_.codecmap.md##type)*

*Defined in [packages/types/src/codec/Map.ts:101](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L101)*

___

###  registry

• **registry**: *[Registry](../interfaces/_types_registry_.registry.md)*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md).[registry](../interfaces/_types_codec_.codec.md#registry)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[registry](_codec_map_.codecmap.md#registry)*

*Defined in [packages/types/src/codec/Map.ts:95](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L95)*

___

###  size

• **size**: *number*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:28

## Accessors

###  encodedLength

• **get encodedLength**(): *number*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[encodedLength](_codec_map_.codecmap.md#encodedlength)*

*Defined in [packages/types/src/codec/Map.ts:115](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L115)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[hash](_codec_map_.codecmap.md#hash)*

*Defined in [packages/types/src/codec/Map.ts:128](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L128)*

**`description`** Returns a hash of the value

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[isEmpty](_codec_map_.codecmap.md#isempty)*

*Defined in [packages/types/src/codec/Map.ts:135](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L135)*

**`description`** Checks if the value is an empty value

**Returns:** *boolean*

## Methods

###  clear

▸ **clear**(): *void*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:22

**Returns:** *void*

___

###  delete

▸ **delete**(`key`: K): *boolean*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:23

**Parameters:**

Name | Type |
------ | ------ |
`key` | K |

**Returns:** *boolean*

___

###  eq

▸ **eq**(`other?`: any): *boolean*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[eq](_codec_map_.codecmap.md#eq)*

*Defined in [packages/types/src/codec/Map.ts:142](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L142)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | any |

**Returns:** *boolean*

___

###  forEach

▸ **forEach**(`callbackfn`: function, `thisArg?`: any): *void*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:24

**Parameters:**

▪ **callbackfn**: *function*

▸ (`value`: V, `key`: K, `map`: [Map](_codec_struct_.struct.md#static-map)‹K, V›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`value` | V |
`key` | K |
`map` | [Map](_codec_struct_.struct.md#static-map)‹K, V› |

▪`Optional`  **thisArg**: *any*

**Returns:** *void*

___

###  get

▸ **get**(`key`: K): *V | undefined*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[get](_codec_map_.codecmap.md#get)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:25

**Parameters:**

Name | Type |
------ | ------ |
`key` | K |

**Returns:** *V | undefined*

___

###  has

▸ **has**(`key`: K): *boolean*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:26

**Parameters:**

Name | Type |
------ | ------ |
`key` | K |

**Returns:** *boolean*

___

###  set

▸ **set**(`key`: K, `value`: V): *this*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:27

**Parameters:**

Name | Type |
------ | ------ |
`key` | K |
`value` | V |

**Returns:** *this*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[toHex](_codec_map_.codecmap.md#tohex)*

*Defined in [packages/types/src/codec/Map.ts:149](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L149)*

**`description`** Returns a hex string representation of the value. isLe returns a LE (number-only) representation

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(`isExtended?`: undefined | false | true): *[AnyJson](../modules/_types_helpers_.md#anyjson)*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[toHuman](_codec_map_.codecmap.md#tohuman)*

*Defined in [packages/types/src/codec/Map.ts:156](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L156)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Parameters:**

Name | Type |
------ | ------ |
`isExtended?` | undefined &#124; false &#124; true |

**Returns:** *[AnyJson](../modules/_types_helpers_.md#anyjson)*

___

###  toJSON

▸ **toJSON**(): *[AnyJson](../modules/_types_helpers_.md#anyjson)*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[toJSON](_codec_map_.codecmap.md#tojson)*

*Defined in [packages/types/src/codec/Map.ts:169](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L169)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *[AnyJson](../modules/_types_helpers_.md#anyjson)*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[toRawType](_codec_map_.codecmap.md#torawtype)*

*Defined in [packages/types/src/codec/Map.ts:182](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L182)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[toString](_codec_map_.codecmap.md#tostring)*

*Defined in [packages/types/src/codec/Map.ts:189](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L189)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

*Inherited from [CodecMap](_codec_map_.codecmap.md).[toU8a](_codec_map_.codecmap.md#tou8a)*

*Defined in [packages/types/src/codec/Map.ts:197](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/Map.ts#L197)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

___

### `Static` with

▸ **with**<**K**, **V**>(`keyType`: [Constructor](../interfaces/_types_codec_.constructor.md)‹K› | keyof InterfaceTypes, `valType`: [Constructor](../interfaces/_types_codec_.constructor.md)‹V› | keyof InterfaceTypes): *[Constructor](../interfaces/_types_codec_.constructor.md)‹[CodecMap](_codec_map_.codecmap.md)‹K, V››*

*Defined in [packages/types/src/codec/BTreeMap.ts:10](https://github.com/polkadot-js/api/blob/82c1e3f35a/packages/types/src/codec/BTreeMap.ts#L10)*

**Type parameters:**

▪ **K**: *[Codec](../interfaces/_types_codec_.codec.md)*

▪ **V**: *[Codec](../interfaces/_types_codec_.codec.md)*

**Parameters:**

Name | Type |
------ | ------ |
`keyType` | [Constructor](../interfaces/_types_codec_.constructor.md)‹K› &#124; keyof InterfaceTypes |
`valType` | [Constructor](../interfaces/_types_codec_.constructor.md)‹V› &#124; keyof InterfaceTypes |

**Returns:** *[Constructor](../interfaces/_types_codec_.constructor.md)‹[CodecMap](_codec_map_.codecmap.md)‹K, V››*