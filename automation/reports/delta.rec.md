### 🔁 Changes since last build _(merge order: recorded)_

**New PRs (9)**
- [#10198](https://github.com/IfcOpenShell/IfcOpenShell/pull/10198) → merged — Don't fail drawing when viewer fails to launch
- [#10202](https://github.com/IfcOpenShell/IfcOpenShell/pull/10202) → merged — Add Alt+T butt join for walls
- [#10204](https://github.com/IfcOpenShell/IfcOpenShell/pull/10204) → merged — Cap gizmo icon size when zooming in
- [#10227](https://github.com/IfcOpenShell/IfcOpenShell/pull/10227) → merged — Bonsai: save plain edit-mode mesh edits on Tab out
- [#10228](https://github.com/IfcOpenShell/IfcOpenShell/pull/10228) → merged — Bonsai: keep geometry in place on IFC Set Origin
- [#10347](https://github.com/IfcOpenShell/IfcOpenShell/pull/10347) → merged — Bonsai: edit several representation items at once
- [#10348](https://github.com/IfcOpenShell/IfcOpenShell/pull/10348) → merged — Bonsai: edit extrusion depth and direction with a handle in edit mode
- [#10349](https://github.com/IfcOpenShell/IfcOpenShell/pull/10349) → merged — Bonsai: Shift+D in item mode adds a copy of the item to the element
- [#10350](https://github.com/IfcOpenShell/IfcOpenShell/pull/10350) → merged — Bonsai: refresh the item profile list after replacing a named profile

**Updated (new commits) (8)**
- [#8658](https://github.com/IfcOpenShell/IfcOpenShell/pull/8658) — Bonsai: toggle a profile type's length between typed and per-instance
- [#9021](https://github.com/IfcOpenShell/IfcOpenShell/pull/9021) — Bonsai: allow a single IfcAnnotation to appear on multiple drawings (#9019)
- [#9047](https://github.com/IfcOpenShell/IfcOpenShell/pull/9047) — Bonsai: add bim.select_assigned_annotations, the inverse of select_assigned_product
- [#9517](https://github.com/IfcOpenShell/IfcOpenShell/pull/9517) — Bonsai: fuse underside clip solids into one UNION tool (#9516)
- [#9589](https://github.com/IfcOpenShell/IfcOpenShell/pull/9589) — Collect whole aggregates in bim.add_aggregate
- [#10039](https://github.com/IfcOpenShell/IfcOpenShell/pull/10039) — Bonsai: clip walls to steep undersides without notching the eave (#10038)
- [#10045](https://github.com/IfcOpenShell/IfcOpenShell/pull/10045) — Add parametric framing systems (railings, curtain walls, storefronts)
- [#10153](https://github.com/IfcOpenShell/IfcOpenShell/pull/10153) — Keep the clicked side in wall and profile joins

**Dropped (36)** _(merged upstream or PR closed)_
- #9868 (was merged) — Structural Analysis 1: Fix load cases, load groups and activities
- #9869 (was merged) — Structural Analysis 2: Streamline applying and editing loads
- #9870 (was merged) — Structural Analysis 3: Readable point force diagrams in Show Loads
- #9871 (was merged) — Structural Analysis 4: Edit loads from the viewport
- #9872 (was merged) — Structural Analysis 5: See and show a structural item's loads
- #9900 (was merged) — Structural Analysis 6: Enter loads by eighths and refine their display
- #9901 (was merged) — Structural Analysis 7: Lock known force values and solve the unknowns
- #9902 (was merged) — Structural Analysis 8: Tilt structural point axes in the X-Z plane
- #9903 (was merged) — Structural Analysis 9: Export structural calculation reports
- #9904 (was merged) — Structural Analysis 10: Resolve forces on inclines and from known components
- #9905 (was merged) — Structural Analysis 11: Document structural calculation reports
- #9911 (was merged) — Structural Analysis 12: Fold structural analysis plans into the dev note
- #9912 (was merged) — Structural Analysis 13: Measure a resultant's angle from any axis
- #9915 (was merged) — Structural Analysis 14: Make structural load diagrams more legible
- #9917 (was merged) — Structural Analysis 15: Enter loads against point axes and edit loads by clicking
- #9923 (was merged) — Structural Analysis 16: Draw the +Y axis at loaded points
- #9924 (was merged) — Structural Analysis 17: Link load magnitudes, equal or by a ratio
- #9925 (was merged) — Structural Analysis 18: Mark found slopes and resultants with a padlock
- #9933 (was merged) — Structural Analysis 19: Take moments of point forces about a point
- #9936 (was merged) — Structural Analysis 20: Edit the moment centre from moments drawn
- #9938 (was merged) — Structural Analysis 21: Set and keep a resultant moment about a point
- #9939 (was merged) — Structural Analysis 22: Find where the moment centre must be
- #9940 (was merged) — Structural Analysis 23: Show moments signed, counter-clockwise positive
- #9943 (was merged) — Structural Analysis 24: Find where a force must act for a kept moment
- #9944 (was merged) — Structural Analysis 25: Dimension a force's place from A and its arm's slope
- #9961 (was merged) — Structural Analysis 26: Keep kept moments as structural points move
- #9990 (was merged) — Structural Analysis 27: Label structural topology as Reference; default angle unit
- #10001 (was merged) — Structural Analysis 28: Recognise load groups typed as load cases
- #10002 (was merged) — Structural Analysis 29: Read global loads in the model's axes
- #10003 (was merged) — Structural Analysis 30: Name pushes by the side they arrive from
- #10017 (was merged) — Structural Analysis 31: Point axes named in names, and their components shown
- #10064 (was merged) — Structural Analysis 32: Make moment drawings easier to read
- #10118 (was merged) — Restore #3052 guard for big lists in remove_deep2
- #10174 (was merged) — Give new structural curve items an Axis
- #10175 (was merged) — Assign structural analysis models to buildings
- #10181 (was merged) — Add replace() to the selector format language
