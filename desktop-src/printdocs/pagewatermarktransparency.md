---
Description: This topic is not current. For the most current information, see the Print Schema Specification.
ms.assetid: f94c1450-9648-4aee-8f88-2a9213eba4a9
title: PageWatermarkTransparency
ms.topic: article
ms.date: 05/31/2018
---

# PageWatermarkTransparency

This topic is not current. For the most current information, see the [Print Schema Specification](https://www.microsoft.com/whdc/xps/printschema.mspx).

Specifies the transparency for the watermark. Fully opaque would have a value of 0.

-   [Element Information](#element-information)
-   [Structure Content](#structure-content)

## Element Information



| Name                       |                                            |
|----------------------------|--------------------------------------------|
| Element Type <br/>   | ParameterDef<br/>                    |
| Scoping Prefix <br/> | Page<br/>                            |
| Notes <br/>          | Linked to PageWatermark element<br/> |



 

## Structure Content

The XML structure of this element is as follows:

``` syntax
<psf:ParameterDef name="psk:PageWatermarkTransparency">
  <psf:Property name="psf:DataType">
    <psf:Value xsi:type="xs:string">xs:integer</psf:Value>
  </psf:Property>
  <psf:Property name="psf:DefaultValue">
    <psf:Value xsi:type="xs:integer">0</psf:Value>
  </psf:Property>
  <psf:Property name="psf:MaxValue">
    <psf:Value xsi:type="xs:integer">100</psf:Value>
  </psf:Property>
  <psf:Property name="psf:MinValue">
    <psf:Value xsi:type="xs:integer">0</psf:Value>
  </psf:Property>
  <psf:Property name="psf:Multiple">
    <psf:Value xsi:type="xs:integer">1</psf:Value>
  </psf:Property>
  <psf:Property name="psf:Mandatory">
    <psf:Value xsi:type="xs:string">psk:Conditional</psf:Value>
  </psf:Property>
  <psf:Property name="psf:UnitType">
    <psf:Value xsi:type="xs:string">percent</psf:Value>
  </psf:Property>
</psf:ParameterDef>
```

## Structure Properties

The following table outlines the characteristics of the variables defined in the XML structure.



| Property                | xsi:type           | Value                      |
|-------------------------|--------------------|----------------------------|
| DataType<br/>     | string<br/>  | xs:integer<br/>      |
| DefaultValue<br/> | integer<br/> | 0<br/>               |
| MaxValue<br/>     | integer<br/> | 100<br/>             |
| MinValue<br/>     | integer<br/> | 0<br/>               |
| Multiple<br/>     | integer<br/> | 1<br/>               |
| Mandatory<br/>    | string<br/>  | psk:Conditional<br/> |
| UnitType<br/>     | string<br/>  | percent<br/>         |



 

## Related topics

<dl> <dt>

[Print Schema Specification](https://www.microsoft.com/whdc/xps/printschema.mspx)
</dt> </dl>

 

 




