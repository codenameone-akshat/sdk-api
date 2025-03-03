---
UID: NF:windows.foundation.IPropertyValueStatics.CreateSizeArray
title: IPropertyValueStatics::IPropertyValueStatics (windows.foundation.h)
description: Creates a new IPropertyValue object that contains the specified array of Size values.
helpviewer_keywords: ["CreateSizeArray","CreateSizeArray method [Windows Runtime]","CreateSizeArray method [Windows Runtime]","IPropertyValueStatics interface","IPropertyValueStatics interface [Windows Runtime]","CreateSizeArray method","IPropertyValueStatics.CreateSizeArray","IPropertyValueStatics.IPropertyValueStatics","IPropertyValueStatics::CreateSizeArray","IPropertyValueStatics::IPropertyValueStatics","windows/IPropertyValueStatics::CreateSizeArray","winrt.ipropertyvaluefactory_createsizearray","winrt.ipropertyvaluestatics_createsizearray"]
old-location: winrt\ipropertyvaluestatics_createsizearray.htm
tech.root: WinRT
ms.assetid: 8b9916e7-0a0d-44b1-8f8d-8307c145e57a
ms.date: 12/05/2018
ms.keywords: CreateSizeArray, CreateSizeArray method [Windows Runtime], CreateSizeArray method [Windows Runtime],IPropertyValueStatics interface, IPropertyValueStatics interface [Windows Runtime],CreateSizeArray method, IPropertyValueStatics.CreateSizeArray, IPropertyValueStatics.IPropertyValueStatics, IPropertyValueStatics::CreateSizeArray, IPropertyValueStatics::IPropertyValueStatics, windows/IPropertyValueStatics::CreateSizeArray, winrt.ipropertyvaluefactory_createsizearray, winrt.ipropertyvaluestatics_createsizearray
req.header: windows.foundation.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Windows.Foundation.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IPropertyValueStatics::CreateSizeArray
 - windows.foundation/IPropertyValueStatics::CreateSizeArray
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Windows.Foundation.h
api_name:
 - IPropertyValueStatics.CreateSizeArray
---

# IPropertyValueStatics::IPropertyValueStatics


## -description

Creates a new <a href="/windows/desktop/api/windows.foundation/nn-windows-foundation-ipropertyvalue">IPropertyValue</a> object that contains  the specified array of <a href="/windows/desktop/api/windows.foundation/ns-windows-foundation-size">Size</a> values.

## -parameters

### -param __valueSize [in]

Type: <b>UINT32</b>

The number of values in the array.

### -param value [in]

Type: <b><a href="/windows/desktop/api/windows.foundation/ns-windows-foundation-size">Size</a>*</b>

The array of <a href="/windows/desktop/api/windows.foundation/ns-windows-foundation-size">Size</a> values to store.

### -param propertyValue [out, retval]

Type: <b><a href="/windows/desktop/api/inspectable/nn-inspectable-iinspectable">IInspectable</a>**</b>

A pointer to a new object that contains <i>value</i>. Use the <a href="/windows/desktop/api/unknwn/nf-unknwn-iunknown-queryinterface(q)">IUnknown::QueryInterface</a> method to get the <a href="/windows/desktop/api/windows.foundation/nn-windows-foundation-ipropertyvalue">IPropertyValue</a> interface for the object.

## -returns

Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/api/windows.foundation/nf-windows-foundation-ipropertyvalue-getsizearray">IPropertyValue::GetSizeArray</a>



<a href="/windows/desktop/api/windows.foundation/nn-windows-foundation-ipropertyvaluestatics">IPropertyValueStatics</a>