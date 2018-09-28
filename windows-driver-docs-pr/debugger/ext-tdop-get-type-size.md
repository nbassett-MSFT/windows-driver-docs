---
title: EXT\_TDOP\_GET\_TYPE\_SIZE
description: The EXT\_TDOP\_GET\_TYPE\_SIZE sub-operation of the DEBUG\_REQUEST\_EXT\_TYPED\_DATA\_ANSI Request operation returns the size of the specified typed data.
ms.assetid: 3e668522-60bb-4abc-87b8-6b1beea573a3
keywords: ["EXT_TDOP_GET_TYPE_SIZE Windows Debugging"]
topic_type:
- apiref
api_name:
- EXT_TDOP_GET_TYPE_SIZE
api_type:
- NA
ms.author: domars
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
ms.localizationpriority: medium
---

# EXT\_TDOP\_GET\_TYPE\_SIZE


The EXT\_TDOP\_GET\_TYPE\_SIZE sub-operation of the [**DEBUG\_REQUEST\_EXT\_TYPED\_DATA\_ANSI**](debug-request-ext-typed-data-ansi.md)[**Request**](request.md) operation returns the size of the specified typed data.

**Parameters**

<span id="Operation"></span><span id="operation"></span><span id="OPERATION"></span>**Operation**  
Set to EXT\_TDOP\_GET\_TYPE\_SIZE for this sub-operation.

<span id="InData"></span><span id="indata"></span><span id="INDATA"></span>**InData**  
Specifies the typed data whose size is being requested.

<span id="Out32"></span><span id="out32"></span><span id="OUT32"></span>**Out32**  
Receives the size, in bytes, of the typed data.

<span id="Status"></span><span id="status"></span><span id="STATUS"></span>**Status**  
Receives the status code returned by this sub-operation. This is the same as the value returned by [**Request**](request.md).

Remarks
-------

EXT\_TDOP\_GET\_TYPE\_SIZE is a value in the [**EXT\_TDOP**](https://msdn.microsoft.com/library/windows/hardware/ff544529) enumeration.

The parameters for this sub-operation are members of the [**EXT\_TYPED\_DATA**](https://msdn.microsoft.com/library/windows/hardware/ff545306) structure. The members of EXT\_TYPED\_DATA that are not listed in the preceding Parameters section are not used by this sub-operation and should be set to zero. The descriptions of the members in the preceding Parameters section specify what the members are used for. See **EXT\_TYPED\_DATA** for more details.

## <span id="see_also"></span>See also


[**DEBUG\_REQUEST\_EXT\_TYPED\_DATA\_ANSI**](debug-request-ext-typed-data-ansi.md)

[**EXT\_TDOP**](https://msdn.microsoft.com/library/windows/hardware/ff544529)

[**EXT\_TYPED\_DATA**](https://msdn.microsoft.com/library/windows/hardware/ff545306)

[**Request**](request.md)

 

 





