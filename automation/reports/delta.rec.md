### 🔁 Changes since last build _(merge order: recorded)_

**New PRs (22)**
- [#7858](https://github.com/IfcOpenShell/IfcOpenShell/pull/7858) → merged — Fix #6602: Print IfcSpaces in projection.
- [#8429](https://github.com/IfcOpenShell/IfcOpenShell/pull/8429) → merged — Fix horizontal profile editing for sloped LAYER3 slabs
- [#8599](https://github.com/IfcOpenShell/IfcOpenShell/pull/8599) → merged — Bonsai: don't crash decoration labels on a zero-length text direction
- [#8600](https://github.com/IfcOpenShell/IfcOpenShell/pull/8600) → merged — Bonsai: skip drawing decorations when the scene has no active camera
- [#8610](https://github.com/IfcOpenShell/IfcOpenShell/pull/8610) → merged — ifcpatch: fix MergeDuplicateTypes destroying distinct/cross-class types
- [#8668](https://github.com/IfcOpenShell/IfcOpenShell/pull/8668) → merged — project.append_asset: don't crash on untracked removed element (#8666)
- [#8822](https://github.com/IfcOpenShell/IfcOpenShell/pull/8822) → merged — Bonsai: harden BBIM_Boolean.Data parsing against non-list payloads
- [#8928](https://github.com/IfcOpenShell/IfcOpenShell/pull/8928) → skipped_draft — Bonsai + ifcopenshell.api: merge/reassign redundant materials into one
- [#9016](https://github.com/IfcOpenShell/IfcOpenShell/pull/9016) → merged — Bonsai: fix "Feet - Decimal" dimension unit breaking annotation decorators (#9015)
- [#9018](https://github.com/IfcOpenShell/IfcOpenShell/pull/9018) → merged — Bonsai: allow aggregating IfcAnnotation elements and moving them as a unit
- [#9054](https://github.com/IfcOpenShell/IfcOpenShell/pull/9054) → merged — copy_class: don't share the original's annotations with the duplicate (#9049, cause behind #4014)
- [#9307](https://github.com/IfcOpenShell/IfcOpenShell/pull/9307) → merged — Fix #8603: drawing underlay renders the previously active drawing's objects
- [#9318](https://github.com/IfcOpenShell/IfcOpenShell/pull/9318) → merged — Fix EPset_Drawing.BringToFront not applying to merged cut geometry
- [#9320](https://github.com/IfcOpenShell/IfcOpenShell/pull/9320) → merged — Fix reflected plan drawings rebuilding their camera on every create_drawing
- [#9441](https://github.com/IfcOpenShell/IfcOpenShell/pull/9441) → merged — Bonsai: resolve IFC save path to absolute before writing (fixes relative-path save failure)
- [#9478](https://github.com/IfcOpenShell/IfcOpenShell/pull/9478) → merged — Bonsai: reload external styles from .blend in update_current_style
- [#9491](https://github.com/IfcOpenShell/IfcOpenShell/pull/9491) → merged — Bonsai: set unit scale when a project is loaded from a .blend (#9490)
- [#9493](https://github.com/IfcOpenShell/IfcOpenShell/pull/9493) → merged — Bonsai: key cut linework on the material of the cut, not the layer set
- [#9494](https://github.com/IfcOpenShell/IfcOpenShell/pull/9494) → merged — Bonsai: emit one SVG class per metadata value, and per layer where cut
- [#9507](https://github.com/IfcOpenShell/IfcOpenShell/pull/9507) → merged — Bonsai: retry the .blend save in save_project when the file is briefly locked (#9506)
- [#9515](https://github.com/IfcOpenShell/IfcOpenShell/pull/9515) → merged — Bonsai: flatten roof footprint instead of failing, keep path preview, direct_profile_edit support
- [#9765](https://github.com/IfcOpenShell/IfcOpenShell/pull/9765) → merged — Bonsai: strip HTML comments from annotation text

**Now merging (1)**
- [#8251](https://github.com/IfcOpenShell/IfcOpenShell/pull/8251) (skipped_conflict → merged) — pset.edit_pset: treat an empty string for a numeric property as no value (#4112)
