# NSS-77TR RECORD v0.1

NEURO-STRUCTURAL SYNCHRONIZATION ___ 77 TRANSITION ARCHIVE

## Features
- Monthly archive blocks
- DASH / ARCHIVE / LOG / DATA tabs
- Paste one-month text blocks
- Existing HIST-style log rendering
- Search / edit / delete
- JSON export/import
- Full text export/copy
- LocalStorage based

## Build
- BASE converted from REC.psd
- BASE size: 941 × 1900
- PSD conversion: ImageMagick

## v0.1 dashhistory
- DASH simplified to a direct full history list.
- Removed DASH stats / quick search / recent block cards.
- ARCHIVE keeps search/filter functions.

## v0.1 dashclean
- DASH now renders full history as plain text.
- Removed visible DASH cards, boxes, borders, and buttons.
- ARCHIVE / LOG / DATA remain unchanged.

## v0.1 flatblack-safe
- Rebuilt from working dashclean version.
- Applied flat black UI via CSS override only.
- No JS or structural mutation.
- Removed visible borders, corner radius, and colored box backgrounds.

## v0.1 datafix
- DATA tab simplified to EXPORT JSON / EXPORT TEXT / DASH only.
- Removed DANGER ZONE UI.
- Removed IMPORT JSON UI.
- DASH forced to plain full-history text rendering with no visible boxes or buttons.
- Flat black safe override retained.

## v0.1 dashfix
- DASH now uses a dedicated dashPlainStream renderer.
- DASH no longer uses blockCard, card boxes, item boxes, buttons, or actions.
- DASH displays only month title + formatted full text stream.
- ARCHIVE / LOG / DATA unchanged.

## v0.1 opacity70
- Box backgrounds changed from pure black to rgba(0,0,0,.70).
- Applied to cards, archive items, logbody, inputs, selects, textareas, buttons, and toast.
- DASH plain text stream remains transparent so the base image shows through.
- DATA remains EXPORT JSON / EXPORT TEXT / DASH only.

## v0.1 renderfix
- Embedded uploaded JSON backup as seed data.
- New storage key: nss77tr_record_v01_renderfix.
- Added RECORD monthly renderer.
- Monthly Core Summary is paragraph-normalized from PDF-copy line breaks.
- Summary section headings are bolded lightly.
- Daily logs keep STATUS/HIST-style section highlighting.
- DASH and ARCHIVE use the same formatted renderer.

## v0.1 formatfix
- Added title / divider / summary spacing:
  NSS-77TR RECORD
  ⸻
  Monthly Summary
- Added session spacing normalization:
  date
  Session time
  WU
- Primary WU / MN / CD / Notes sections now receive a blank line before each section.
- New storage key: nss77tr_record_v01_formatfix.

## v0.1 formatfix2
- Updated BASE.png from REC(1).psd.
- Kept visible version code unchanged.
- Box opacity changed from 70% to 60%.
- Reduced date -> Session time spacing.
- Storage key: nss77tr_record_v01_formatfix2.
- BASE conversion: ImageMagick
- BASE size: 941 × 1900

## v0.1 scrollfix
- Viewport height changed from 70% to 65%.
- Scrollbar track/background set to black.
- Scrollbar thumb and button indicators set to #ff0000.
- Visible version code unchanged.
- New storage key: nss77tr_record_v01_scrollfix.

## v0.1 scrollthin
- Red scrollbar thumb visually thinned using black inner border.
- Scrollbar slot remains stable while the red visible line is reduced.
- Scroll arrow red lines also narrowed.
- Visible version code unchanged.
- New storage key: nss77tr_record_v01_scrollthin.

## v0.1 scrollrootfix
- Root html/body scrollbar width forced to 4px.
- Global scrollbar track remains black and thumb remains #ff0000.
- Removed hover color fade for scrollbar thumb/buttons.
- DASH month label font size reduced by 2px and set to red.
- ARCHIVE month/title labels reduced by 2px and set to red.
- Visible version code unchanged.
- Storage key: nss77tr_record_v01_scrollrootfix.

## v0.1 hotspotfix
- Hotspot active state restored with dark gray overlay: rgba(80,80,80,.32).
- Scrollbar thumb color locked to #ff0000 across hover/active/window-inactive states.
- Scrollbar button color locked to black across hover/active states.
- Visible version code unchanged.
- Storage key: nss77tr_record_v01_hotspotfix.

## v0.1 pdffix
- Applied uploaded index(9).html with user-adjusted hotspot positions.
- Hotspot active overlay returned to transparent.
- DATA button changed from EXPORT TEXT to EXPORT PDF.
- Added browser print-based exportPdf() function.
- Added stronger scrollbar thumb color lock using inset box-shadow.
- Visible version code unchanged.
- Storage key: nss77tr_record_v01_pdffix.

## v0.1 pdfscreen
- Rebuilt EXPORT PDF layout as an app-screen style print view.
- Each month prints inside a BASE.png-backed screen frame.
- The record content is placed in a DASH-like viewport area.
- EXPORT PDF still uses browser print/save PDF.
- Visible version code unchanged.
- Storage key: nss77tr_record_v01_pdfscreen.

## v0.1 pdfpure
- EXPORT PDF changed back to a pure document output with no BASE image.
- Kept the current document margin style.
- Added DATA export range selector: ALL MONTHS or individual month.
- EXPORT JSON now respects the selected export range.
- EXPORT PDF now respects the selected export range.
- Visible version code unchanged.
- Storage key: nss77tr_record_v01_pdfpure.

## v0.1 pdfmarginfix
- EXPORT PDF keeps pure document output with no BASE image.
- @page margin set to 0 for no-white-edge print mode.
- Added internal black pdfSheet with 14mm padding to preserve document margins.
- Added fixed black page background layer for print-to-PDF background coverage.
- Export range selector remains active for JSON/PDF.
- Visible version code unchanged.
- Storage key: nss77tr_record_v01_pdfmarginfix.

## V0.1.2 RELEASE
- Visible build updated to V0.1.2.
- Removed visible EXPORT RANGE label row from DATA tab while keeping the month selector.
- Applied REC HEAD.png as app icon source.
- Updated icon-192.png and icon-512.png.
- EXPORT JSON / EXPORT PDF / DASH retained.
- Monthly export range selector retained.
- Storage key: nss77tr_record_v012_release.
- Cache: nss77tr-record-v012-release.
