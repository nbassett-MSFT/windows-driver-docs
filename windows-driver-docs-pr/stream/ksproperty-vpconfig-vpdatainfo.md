---
title: KSPROPERTY\_VPCONFIG\_VPDATAINFO
description: The KSPROPERTY\_VPCONFIG\_VPDATAINFO property indicates the initial configuration state of the video port.
ms.assetid: 66419d5a-c701-45f4-9ac6-322997e2f000
keywords: ["KSPROPERTY_VPCONFIG_VPDATAINFO Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_VPCONFIG_VPDATAINFO
api_location:
- ksmedia.h
api_type:
- HeaderDef
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
ms.localizationpriority: medium
---

# KSPROPERTY\_VPCONFIG\_VPDATAINFO


The KSPROPERTY\_VPCONFIG\_VPDATAINFO property indicates the initial configuration state of the video port.

## <span id="ddk_ksproperty_vpconfig_vpdatainfo_ks"></span><span id="DDK_KSPROPERTY_VPCONFIG_VPDATAINFO_KS"></span>


### Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Pin</p></td>
<td><p>[<strong>KSPROPERTY</strong>](https://docs.microsoft.com/windows-hardware/drivers/ddi/content/ks/ns-ks-ksidentifier)</p></td>
<td><p>[<strong>KS_AMVPDATAINFO</strong>](https://msdn.microsoft.com/library/windows/hardware/ff567261)</p></td>
</tr>
</tbody>
</table>

 

The property value (operation data) is a KS\_AMVPDATAINFO structure that describes the properties of the video port.

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

## See also


[**KSPROPERTY**](https://docs.microsoft.com/windows-hardware/drivers/ddi/content/ks/ns-ks-ksidentifier)

[**KS\_AMVPDATAINFO**](https://msdn.microsoft.com/library/windows/hardware/ff567261)

 

 





