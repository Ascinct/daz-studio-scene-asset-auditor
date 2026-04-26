DAZ Studio Scene Asset Auditor (Browser Tool)
=============================================
This tool scans a DAZ Studio .duf scene file and generates a report showing:

- Exact product matches using installed .dsx support files (optional)
- Likely products inferred from asset paths
- Possible matches from shared/common assets
- Scene node labels
- Raw asset file paths

The tool runs entirely in your browser and works using drag-and-drop.

------------------------------------------------------------
REQUIREMENTS
------------------------------------------------------------
A modern web browser (Chrome, Edge, Firefox).
- No installation required.
- No special scripts required.
- No internet connection required.

------------------------------------------------------------
QUICK START
------------------------------------------------------------
1) Open the tool in your browser:
- daz-studio-scene-asset-auditor-v1.html

2) Drag your .duf scene file into the Scene file area
or click to browse and select it.

3) (Optional) Select your DAZ support folder:
- Runtime\Support

4) Click: Generate report

5) The report will be displayed on the page.

6) Use the export buttons to download:
- HTML report
- Product title list

------------------------------------------------------------
OPTIONAL: DSX SUPPORT FOLDER
------------------------------------------------------------
Selecting a support folder enables exact product matching.

This folder typically exists in your DAZ content library:
Runtime\Support

Example:
D:\Programs\Daz Studio\Studio\Daz Studio Content\Runtime\Support

------------------------------------------------------------
MULTIPLE CONTENT LIBRARIES
------------------------------------------------------------
If you use multiple DAZ content libraries:

You must manually select the relevant Runtime\Support folder each time.

Note:
The browser cannot automatically scan multiple folders.

------------------------------------------------------------
IMPORTANT NOTES ABOUT SUPPORT FOLDER
------------------------------------------------------------
- The folder must contain .dsx files
- Subfolders are scanned automatically
- If no folder is selected:
-- The tool will still run
-- Reports will still be generated
-- Exact matching will be skipped

The last selected support folder name is remembered for convenience, but must be reselected.

------------------------------------------------------------
WHAT IS DSX EXACT MATCHING?
------------------------------------------------------------
DAZ Studio uses .dsx files to describe installed products.

These files often include references to:
- .duf presets
- .dsf geometry and morph files
- textures
- support assets

The tool compares asset paths from your scene file against these .dsx files.

This allows:
- Accurate product identification
- Better results than folder-name guessing

------------------------------------------------------------
REPORT SECTIONS
------------------------------------------------------------
Summary
- Shows counts for all sections and whether DSX matching was used.

Exact product matches
- Products matched directly against .dsx support files.
- These are the most reliable results.

Possible match
- Products that only matched shared/common assets.
- Treat these as suggestions, not confirmed matches.

Likely products
- Products inferred from folder paths.
- Useful, but not always exact.

Scene node labels
- Names of objects, figures, and elements found in the scene.

Raw asset paths
- All asset file paths referenced by the scene.
- Useful for troubleshooting.

------------------------------------------------------------
EXPORT OPTIONS
------------------------------------------------------------
Download HTML report
- Creates a standalone report file that can be shared.

Export product titles
- Creates a text file containing:
-- Exact product matches
-- Possible matches

------------------------------------------------------------
TROUBLESHOOTING
------------------------------------------------------------
No exact product matches found

Check that:
- The correct Runtime\Support folder was selected
- The folder contains .dsx files

The tool says matching was skipped
- This means no support folder was selected.

Too many possible matches
- This is normal when products share common base assets (e.g. Genesis base files).

Likely products look incorrect
- This section is based on folder inference.
- Use Exact product matches when available.

------------------------------------------------------------
SHARING NOTES
------------------------------------------------------------
This tool does not include any DAZ assets.

It only reads:
- The .duf file you provide
- .dsx files from your local system

Reports may include local file paths.
Review reports before sharing publicly.

------------------------------------------------------------
DONE
------------------------------------------------------------
You are ready to use the tool.


