> Archived – Now maintained in the Netherlands3D Main Repository; OpenUPM updates suspended.

# Minimap

A minimap canvas solution to navigate through a WMTS map, and click to move the 3D camera to that location.

## Installing

This package is provided through OpenUPM, to install it using the CLI you can perform the following:

```bash
$ openupm add eu.netherlands3d.minimap
```

or, you have to add `https://package.openupm.com` as a scoped registry with, at least, the following scopes:

- `eu.netherlands3d`

## Usage

Place the minimap prefab in a canvas.
Scriptable objects can be swapped/created to create new WMTS services.

## Events - WMTSMap

The `WMTSMap` class features two events: `onZoom` and `onClick`.

### onZoom

This event is triggered when the user performs a zoom action.

### onClick

This event is triggered when a user clicks on a location on the minimap. The event returns the coordinates of the
clicked location in the Rijksdriehoekformaat coordinate system.

# Repository Archived

This repository has been **archived** and is no longer maintained independently.

The contents of this package have been merged into the  
**[Netherlands3D Main Repository](https://github.com/Netherlands3D/twin)**  
into the `Packages` folder.

## Current Location

The latest version and future updates of this package will be maintained inside the Netherlands3D main repository as part of an effort to simplify and unify our development workflow.

## Why was this repository archived?

To streamline development and reduce overhead, the Netherlands3D packages are being integrated into the main repository.  
This approach allows for better coordination between packages and features, while we continue to evaluate whether a full monorepo setup (including versioning) is desirable in the future.

## Where to contribute

Please open issues and pull requests in the [Netherlands3D Main Repository](https://github.com/Netherlands3D/twin).

## Publication status

Updates to this package on **OpenUPM** are **suspended until further notice**.  
Future releases will be managed from the main repository once the new development flow has been finalized.

## Historical reference

This repository remains available in read-only mode as a historical record of its standalone development.
