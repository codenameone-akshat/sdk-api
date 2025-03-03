---
UID: NF:d3d12video.ID3D12VideoExtensionCommand.GetProtectedResourceSession
title: ID3D12VideoExtensionCommand::GetProtectedResourceSession
ms.date: 11/4/2019
ms.topic: language-reference
targetos: Windows
description: Gets the ID3D12ProtectedResourceSession that was passed into ID3D12VideoDevice2::CreateVideoExtensionCommand when the ID3D12VideoExtensionCommand was created.
tech.root: mf
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: d3d12video.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Windows 10, version 2004 (10.0; Build 19041)
req.target-min-winversvr: Windows Server, version 2004 (10.0; Build 19041)
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - d3d12video.h
api_name:
 - ID3D12VideoExtensionCommand::GetProtectedResourceSession
f1_keywords:
 - ID3D12VideoExtensionCommand::GetProtectedResourceSession
 - d3d12video/ID3D12VideoExtensionCommand::GetProtectedResourceSession
dev_langs:
 - c++
---

## -description

Gets the [ID3D12ProtectedResourceSession](../d3d12/nn-d3d12-id3d12protectedresourcesession.md) that was passed into [ID3D12VideoDevice2::CreateVideoExtensionCommand](nf-d3d12video-id3d12videodevice2-createvideoextensioncommand.md) when the [ID3D12VideoExtensionCommand](nn-d3d12video-id3d12videoextensioncommand.md) was created.

## -parameters

### -param riid

The globally unique identifier (GUID) for the **ID3D12ProtectedResourceSession** interface.

### -param ppProtectedSession

Receives a void pointer representing the **ID3D12ProtectedResourceSession** interface.

## -returns

This method returns HRESULT.

## -remarks

## -see-also