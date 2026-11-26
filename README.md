# My-3D-prints.

This repository is dedicated to 3D prints designed by me at [SatyaForge](https://satyaforge.com).

## Reusable Filament Spool

**Current design version: v0.1**

This project is a reusable filament spool designed in FreeCAD. The goal is not only to provide printable parts, but also to make the design genuinely editable so that other people can adapt it to their own needs.

Where possible, the editable FreeCAD source will be provided alongside the printable files. The intention is to let users inspect the feature tree, open the sketches, understand the constraints, and change dimensions without having to recreate the design from scratch.

### Design documentation in progress

I am preparing a companion write-up for the eventual Printables upload. It will explain how the model is constructed and how to make common changes in FreeCAD.

The guide will include annotated screenshots showing exactly which sketch, constraint, or feature to open and what to change. The notes will be developed alongside the model so that the instructions match the actual v0.1 file.

### Sketch constraints and linked dimensions

Some dimensions are intentionally linked between opposite sides of the spool. For example, the retaining flanges on the two sides currently use an **Equal** constraint so that changing one thickness also changes the other.

In the current model, this relationship was made using geometry imported through a **Binder**. The relevant sketches include `Sketch` and `Sketch002`.

The planned instructions will show:

- Where the linked dimensions are defined.
- How to change a dimension while keeping both sides equal.
- How to remove the relevant **Equal** constraint when independent dimensions are wanted.
- Which sketch and feature should be edited, with screenshots to make the changes easy to follow.

These instructions are being documented as the model develops. They should be checked against the matching project version before making changes.

### Planned project files

As the project is prepared for release, this repository is intended to contain:

- The editable FreeCAD source file.
- STL or 3MF files for users who only want to print the parts.
- Annotated screenshots of important sketches and settings.
- A step-by-step modification guide for common adjustments.
- Version notes describing changes and known limitations.

### Version history

| Version | Status | Notes |
| --- | --- | --- |
| v0.1 | Initial development | First documented design version. Editable-source guidance and annotated screenshots are being prepared. |

This is an evolving design. Dimensions, features, and instructions may change in later versions as the spool is tested and refined.
