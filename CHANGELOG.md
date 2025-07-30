## 0.36.0 (2025-07-30)

### 🚀 Features

- Dark theme ([#171](https://github.com/must/BlockNote/pull/171))
- Multiplayer API and homepage collaboration ([#200](https://github.com/must/BlockNote/pull/200))
- Custom Blocks ([#191](https://github.com/must/BlockNote/pull/191), [#202](https://github.com/must/BlockNote/issues/202), [#217](https://github.com/must/BlockNote/issues/217), [#223](https://github.com/must/BlockNote/issues/223))
- Dark theme fixes + enable theme on website + docs ([#236](https://github.com/must/BlockNote/pull/236), [#239](https://github.com/must/BlockNote/issues/239))
- Color scheme customization ([#305](https://github.com/must/BlockNote/pull/305))
- Improved block type dropdown customization ([#324](https://github.com/must/BlockNote/pull/324))
- Default image blocks ([#331](https://github.com/must/BlockNote/pull/331), [#346](https://github.com/must/BlockNote/issues/346))
- Add Drag Handle Menu item `closeMenuOnClick` prop ([#363](https://github.com/must/BlockNote/pull/363))
- Return values for block manipulation methods ([#458](https://github.com/must/BlockNote/pull/458))
- Separate image, hyperlink, & table components for export ([#625](https://github.com/must/BlockNote/pull/625), [#637](https://github.com/must/BlockNote/issues/637), [#645](https://github.com/must/BlockNote/issues/645), [#640](https://github.com/must/BlockNote/issues/640), [#635](https://github.com/must/BlockNote/issues/635), [#561](https://github.com/must/BlockNote/issues/561))
- option to disable trailing block ([#679](https://github.com/must/BlockNote/pull/679), [#631](https://github.com/must/BlockNote/issues/631))
- add french locales to dictionary ([#728](https://github.com/must/BlockNote/pull/728))
- Add Chinese i18n support ([#726](https://github.com/must/BlockNote/pull/726))
- add i18n support for Brazilian Portuguese (pt-BR) ([#735](https://github.com/must/BlockNote/pull/735))
- add i18n support for pl-PL and is-IS ([#752](https://github.com/must/BlockNote/pull/752))
- Add Japanese i18n ([#756](https://github.com/must/BlockNote/pull/756))
- File blocks ([#731](https://github.com/must/BlockNote/pull/731))
- Checkbox/TODO list item block ([#729](https://github.com/must/BlockNote/pull/729))
- Pasting & dropping files ([#852](https://github.com/must/BlockNote/pull/852))
- Allow custom user fields ([#892](https://github.com/must/BlockNote/pull/892))
- added support for uppy ([#842](https://github.com/must/BlockNote/pull/842))
- server-side processing ([#451](https://github.com/must/BlockNote/pull/451))
- Add Emoji Picker Option ([#854](https://github.com/must/BlockNote/pull/854))
- added german translation ([#992](https://github.com/must/BlockNote/pull/992))
- SuggestionMenuController.tsx support ignoreQueryLength ([#1072](https://github.com/must/BlockNote/pull/1072))
- add option to set html id ([#1078](https://github.com/must/BlockNote/pull/1078))
- make callback return value optional in forEachBlock ([#1081](https://github.com/must/BlockNote/pull/1081))
- Non-selectable custom blocks ([#1090](https://github.com/must/BlockNote/pull/1090))
- Keyboard shortcuts to move selected block up/down ([#1126](https://github.com/must/BlockNote/pull/1126))
- Add Croatian Translation Dictionary ([#1128](https://github.com/must/BlockNote/pull/1128))
- Table row/column extension UI ([#1172](https://github.com/must/BlockNote/pull/1172))
- Code block ([#1177](https://github.com/must/BlockNote/pull/1177))
- added placeholder example ([#1252](https://github.com/must/BlockNote/pull/1252))
- Tab key handling for tables (simple) ([#1275](https://github.com/must/BlockNote/pull/1275))
- Mobile-optimized formatting toolbar ([#1284](https://github.com/must/BlockNote/pull/1284))
- list "start" index and add optional props ([#1326](https://github.com/must/BlockNote/pull/1326))
- add more css specificity for tables ([#1336](https://github.com/must/BlockNote/pull/1336))
- stop suggestion menu event propagation ([#1346](https://github.com/must/BlockNote/pull/1346))
- Code block support in PDF & DOCX exporters ([#1367](https://github.com/must/BlockNote/pull/1367))
- Improved collaboration cursor UX ([#1374](https://github.com/must/BlockNote/pull/1374))
- Page break ([#1372](https://github.com/must/BlockNote/pull/1372))
- add factory function for extensions ([#1390](https://github.com/must/BlockNote/pull/1390))
- Ukrainian localization support ([#1407](https://github.com/must/BlockNote/pull/1407))
- add support for tiptap / liveblocks comments ([#1442](https://github.com/must/BlockNote/pull/1442))
- File insertion QoL ([#1459](https://github.com/must/BlockNote/pull/1459))
- Norwegian localisation ([#1420](https://github.com/must/BlockNote/pull/1420))
- odt exporter ([#1331](https://github.com/must/BlockNote/pull/1331))
- support new table properties in PDF export ([#1475](https://github.com/must/BlockNote/pull/1475))
- split out localization files for optimized bundle ([#1533](https://github.com/must/BlockNote/pull/1533))
- remove shiki dep, add new @blocknote/code-block package for slim shiki build ([#1519](https://github.com/must/BlockNote/pull/1519))
- Block quote ([#1563](https://github.com/must/BlockNote/pull/1563))
- markdown pasting & custom paste handlers ([#1490](https://github.com/must/BlockNote/pull/1490))
- position storage ([#1529](https://github.com/must/BlockNote/pull/1529))
- `change` event allows getting a list of the block changed ([#1585](https://github.com/must/BlockNote/pull/1585))
- expose `editor.prosemirrorState` again ([#1615](https://github.com/must/BlockNote/pull/1615))
- add `undo` and `redo` methods to editor API ([#1592](https://github.com/must/BlockNote/pull/1592))
- new auth & payment system ([#1617](https://github.com/must/BlockNote/pull/1617))
- re-implement Y.js collaboration as BlockNote plugins ([#1638](https://github.com/must/BlockNote/pull/1638))
- toggle blocks ([#1707](https://github.com/must/BlockNote/pull/1707))
- FloatingUI options prop for `BlockPositioner` ([#1801](https://github.com/must/BlockNote/pull/1801))
- Support Google Gemini AI ([#1805](https://github.com/must/BlockNote/pull/1805))
- support multi-column block in PDF, DOCX & ODT exporters ([#1781](https://github.com/must/BlockNote/pull/1781))
- support react 19 ([f7b3466d](https://github.com/must/BlockNote/commit/f7b3466d))
- disable conversion of headings to list items ([#1799](https://github.com/must/BlockNote/pull/1799))
- report `moves` (indents and outdents) as changes when using `getChanges` #1757 ([#1786](https://github.com/must/BlockNote/pull/1786), [#1757](https://github.com/must/BlockNote/issues/1757))
- allow inline content to be `draggable` ([#1818](https://github.com/must/BlockNote/pull/1818))
- added type guards, types, and `editor` prop to custom inline content rendering ([#1736](https://github.com/must/BlockNote/pull/1736))
- use fumadocs for website ([#1654](https://github.com/must/BlockNote/pull/1654))
- llms.mdx routes ([cea93840](https://github.com/must/BlockNote/commit/cea93840))
- enhance text cursor positioning in blocks ([cccf9f74](https://github.com/must/BlockNote/commit/cccf9f74))
- **block-change:** adds a new API for blocking changes to editor state, by filtering transactions ([#1750](https://github.com/must/BlockNote/pull/1750))
- **core:** support h4, h5, and h6 ([#1634](https://github.com/must/BlockNote/pull/1634))
- **file:** `previewWidth` prop now defaults to `undefined` ([#1664](https://github.com/must/BlockNote/pull/1664))
- **i18n:** add Arabic translation ([#822](https://github.com/must/BlockNote/pull/822))
- **locales:** add zh-TW i18n ([#1668](https://github.com/must/BlockNote/pull/1668))
- **nx-cloud:** set up nx workspace ([#1586](https://github.com/must/BlockNote/pull/1586))
- **tables:** overhaul table cells ([#1429](https://github.com/must/BlockNote/pull/1429))
- **xl-email-exporter:** add email exporter ([#1768](https://github.com/must/BlockNote/pull/1768))

### 🩹 Fixes

- parentElement did not work ([#127](https://github.com/must/BlockNote/pull/127))
- externalize unified plugins by adding them to package.json ([#128](https://github.com/must/BlockNote/pull/128))
- parameters and foreachblock ([#153](https://github.com/must/BlockNote/pull/153))
- slashmenu dropdown positioning on edge of page ([#166](https://github.com/must/BlockNote/pull/166))
- dragging multiple blocks ([#170](https://github.com/must/BlockNote/pull/170))
- Isolated drag/drop per editor instance ([#174](https://github.com/must/BlockNote/pull/174))
- Custom UI element API ([#177](https://github.com/must/BlockNote/pull/177))
- Address React Warning when clicking DragHandleMenuItem ([#210](https://github.com/must/BlockNote/pull/210))
- Block side menu flipping to right side ([#225](https://github.com/must/BlockNote/pull/225))
- Error caused by converting `hardBreak` nodes ([#229](https://github.com/must/BlockNote/pull/229))
- Formatting Toolbar not hiding when clicking on elements outside it ([#233](https://github.com/must/BlockNote/pull/233))
- Documentation site screenshots ([#248](https://github.com/must/BlockNote/pull/248))
- vitest run mode ([#259](https://github.com/must/BlockNote/pull/259))
- update playwright image ([#260](https://github.com/must/BlockNote/pull/260))
- Scrolling responsiveness & UI element overflow ([#250](https://github.com/must/BlockNote/pull/250))
- keep marks when merging blocks ([#256](https://github.com/must/BlockNote/pull/256), [#255](https://github.com/must/BlockNote/issues/255))
- `getBlockInfoFromPos` no longer returns `undefined` ([#293](https://github.com/must/BlockNote/pull/293))
- include tippy dependency ([#294](https://github.com/must/BlockNote/pull/294))
- Updates for demos in docs ([#295](https://github.com/must/BlockNote/pull/295))
- Custom blocks without inline content ([#312](https://github.com/must/BlockNote/pull/312))
- Menu overflows ([#340](https://github.com/must/BlockNote/pull/340))
- Error when custom blocks are in `initialContent` ([#348](https://github.com/must/BlockNote/pull/348))
- Boolean/number props not getting parsed correctly ([#362](https://github.com/must/BlockNote/pull/362))
- saving-loading meta info ([#376](https://github.com/must/BlockNote/pull/376))
- `_tiptapOptions` typing and fields getting overridden ([#398](https://github.com/must/BlockNote/pull/398))
- block id null when using collaboration ([#419](https://github.com/must/BlockNote/pull/419))
- additional fix for collaboration state that got reset ([d122932c](https://github.com/must/BlockNote/commit/d122932c))
- `BlockNoteView` types export ([#457](https://github.com/must/BlockNote/pull/457))
- Bug in `replaceBlocks` ([#487](https://github.com/must/BlockNote/pull/487))
- Image block DOM clutter, keyboard handling, and copy/paste ([#456](https://github.com/must/BlockNote/pull/456))
- Multiline list indentation ([#491](https://github.com/must/BlockNote/pull/491))
- Remove console logs while pasting ([#489](https://github.com/must/BlockNote/pull/489))
- Docs home page demo styling fix ([#507](https://github.com/must/BlockNote/pull/507))
- List item shortcuts ([#528](https://github.com/must/BlockNote/pull/528))
- Errors when hovering image block while editor is uneditable ([#533](https://github.com/must/BlockNote/pull/533))
- Formatting toolbar not hiding while dragging blocks ([#529](https://github.com/must/BlockNote/pull/529))
- Mantine styles ([#553](https://github.com/must/BlockNote/pull/553))
- unnecessary call to canNestBlock ([1a5b2c5e](https://github.com/must/BlockNote/commit/1a5b2c5e))
- Nest block buttons should only be visible for certain blocks ([#646](https://github.com/must/BlockNote/pull/646))
- List item enter handler applying to custom blocks ([#571](https://github.com/must/BlockNote/pull/571))
- serialize React content with existing React tree ([#641](https://github.com/must/BlockNote/pull/641))
- inline content react remounting ([#647](https://github.com/must/BlockNote/pull/647))
- Slash Command Android Chrome Issue  #437 ([#443](https://github.com/must/BlockNote/pull/443), [#437](https://github.com/must/BlockNote/issues/437))
- match query anywhere to filter slash menu items ([#719](https://github.com/must/BlockNote/pull/719))
- clean react package deps ([8cb58291](https://github.com/must/BlockNote/commit/8cb58291))
- update version number of examples ([98cc05c0](https://github.com/must/BlockNote/commit/98cc05c0))
- onclick handling mantine suggestion item ([79045641](https://github.com/must/BlockNote/commit/79045641))
- fix light / dark theme switching ([04c70605](https://github.com/must/BlockNote/commit/04c70605))
- Key inputs in blocks without content ([#730](https://github.com/must/BlockNote/pull/730))
- Scroll page to where user is editing ([#680](https://github.com/must/BlockNote/pull/680))
- shouldshow ([#744](https://github.com/must/BlockNote/pull/744))
- export blocknoteviewprops ([#774](https://github.com/must/BlockNote/pull/774))
- remove console log + add lint rule ([#793](https://github.com/must/BlockNote/pull/793))
- update zh.ts (chinese) ([c9a53bb9](https://github.com/must/BlockNote/commit/c9a53bb9))
- Side menu not updating in edge cases ([#791](https://github.com/must/BlockNote/pull/791))
- PDF block example styling ([#785](https://github.com/must/BlockNote/pull/785))
- Parsing paragraphs without text content ([#798](https://github.com/must/BlockNote/pull/798))
- Custom inline content placeholder bug and enter handling ([#784](https://github.com/must/BlockNote/pull/784))
- Link keyboard shortcut and remove warning ([#782](https://github.com/must/BlockNote/pull/782))
- UI element position on scroll ([#769](https://github.com/must/BlockNote/pull/769))
- Mantine sub-menu rendering in the DOM ([#802](https://github.com/must/BlockNote/pull/802))
- Issues when editor is non-editable ([#783](https://github.com/must/BlockNote/pull/783))
- More Notion-like side menu positioning ([#812](https://github.com/must/BlockNote/pull/812))
- Removed ShadCN focus global CSS ([#815](https://github.com/must/BlockNote/pull/815))
- Side menu block finding logic ([#814](https://github.com/must/BlockNote/pull/814))
- fix margin of block of playground in small screen ([#806](https://github.com/must/BlockNote/pull/806))
- custom inline content crash ([#788](https://github.com/must/BlockNote/pull/788))
- node conversion ([#800](https://github.com/must/BlockNote/pull/800))
- Suggestion menu scrolling to selected item ([#838](https://github.com/must/BlockNote/pull/838))
- update `remarkStringify` config ([#841](https://github.com/must/BlockNote/pull/841))
- ShadCN Tailwind scoping ([#847](https://github.com/must/BlockNote/pull/847))
- ShadCN styles scoping & ref error ([#896](https://github.com/must/BlockNote/pull/896))
- Copy selection starting in nested block ([#870](https://github.com/must/BlockNote/pull/870))
- Drag preview issues ([#905](https://github.com/must/BlockNote/pull/905))
- usePrefersColorScheme window reference breaks nextjs ([#907](https://github.com/must/BlockNote/pull/907))
- color scheme queries in usememo ([2a93ad00](https://github.com/must/BlockNote/commit/2a93ad00))
- Side menu not actually freezing ([#943](https://github.com/must/BlockNote/pull/943))
- Formatting toolbar opening on drop ([#944](https://github.com/must/BlockNote/pull/944))
- Dropping blocks above editor ([#945](https://github.com/must/BlockNote/pull/945), [#944](https://github.com/must/BlockNote/issues/944))
- examples link in `readme.md` ([#946](https://github.com/must/BlockNote/pull/946))
- emojimart import ([#950](https://github.com/must/BlockNote/pull/950))
- windows gen file ([#970](https://github.com/must/BlockNote/pull/970))
- change height to maxHeight ([#981](https://github.com/must/BlockNote/pull/981))
- Attribute check in `getDraggableBlockFromElement` ([#995](https://github.com/must/BlockNote/pull/995))
- Slightly changed suggestion menu positioning ([#1025](https://github.com/must/BlockNote/pull/1025))
- Block insert twice when using korean at suggestion ([#1034](https://github.com/must/BlockNote/pull/1034))
- Unexpected getSelection ([#1030](https://github.com/must/BlockNote/pull/1030))
- Emoji suggestion slash menu does not display ([#984](https://github.com/must/BlockNote/pull/984), [#975](https://github.com/must/BlockNote/issues/975))
- External file drag/drop and copy/paste ([#1052](https://github.com/must/BlockNote/pull/1052))
- xss in link toolbar and file download ([#1060](https://github.com/must/BlockNote/pull/1060))
- `blocksToHTMLLossy` props as `data-` attributes ([#1068](https://github.com/must/BlockNote/pull/1068))
- Loading indicator when dropping/pasting files ([#1069](https://github.com/must/BlockNote/pull/1069))
- add editor parameter to inline content render (core) ([#1091](https://github.com/must/BlockNote/pull/1091))
- Table handles hide when selection is active ([#1111](https://github.com/must/BlockNote/pull/1111))
- Null list item index fix ([#1113](https://github.com/must/BlockNote/pull/1113))
- Block update removing children when setting content ([#1103](https://github.com/must/BlockNote/pull/1103))
- build error ([6b644f66](https://github.com/must/BlockNote/commit/6b644f66))
- React 19 compatibility ([#1173](https://github.com/must/BlockNote/pull/1173))
- for link / inline content pasting in table ([#1181](https://github.com/must/BlockNote/pull/1181))
- caption width match file container #1169 ([#1182](https://github.com/must/BlockNote/pull/1182), [#1169](https://github.com/must/BlockNote/issues/1169))
- small issues with table extend button logic ([7783abdb](https://github.com/must/BlockNote/commit/7783abdb))
- update test snapshots for file preview caption width ([6f2e806b](https://github.com/must/BlockNote/commit/6f2e806b))
- try to add react 19 rc versions as peerdep ([937ada82](https://github.com/must/BlockNote/commit/937ada82))
- react 19 strictmode race condition ([#1196](https://github.com/must/BlockNote/pull/1196))
- Clipboard insertion with multiple data types ([#1224](https://github.com/must/BlockNote/pull/1224))
- `getNearestBlockContainerPos` unclear ([#1241](https://github.com/must/BlockNote/pull/1241))
- Remove background color from table props ([#1245](https://github.com/must/BlockNote/pull/1245))
- Typing after link doesn't revert to regular text ([#1225](https://github.com/must/BlockNote/pull/1225))
- List item shortcuts throwing errors ([#1236](https://github.com/must/BlockNote/pull/1236))
- Various multi-column bugs ([#1240](https://github.com/must/BlockNote/pull/1240))
- export updateBlock, to allow extending heading block ([#1235](https://github.com/must/BlockNote/pull/1235))
- add show state control in freezeMenu ([#1184](https://github.com/must/BlockNote/pull/1184))
- ShadCN: inherit <a> styling for inline content ([#1228](https://github.com/must/BlockNote/pull/1228))
- Made column/table resize bars get disabled when editor is non-editable ([#1247](https://github.com/must/BlockNote/pull/1247))
- CodeBlock fixes (select menu, bundled languages, paste from VS Code) ([#1219](https://github.com/must/BlockNote/pull/1219))
- Remove redundant zindex values ([#1257](https://github.com/must/BlockNote/pull/1257))
- disableExtensions ([f53faa1d](https://github.com/must/BlockNote/commit/f53faa1d))
- Tab handling (indentation and toolbar focus) ([#1285](https://github.com/must/BlockNote/pull/1285))
- delete file ru tooltip ([#1270](https://github.com/must/BlockNote/pull/1270))
- update max-height to inherit for suggestion menus ([#1282](https://github.com/must/BlockNote/pull/1282))
- File HTML export and resizing UX ([#1305](https://github.com/must/BlockNote/pull/1305))
- Link UX ([#1304](https://github.com/must/BlockNote/pull/1304))
- `getSelection` behaviour and build ([#1318](https://github.com/must/BlockNote/pull/1318))
- useReactNodeView ref for React 19 compatibility ([#1317](https://github.com/must/BlockNote/pull/1317))
- typing issue for some users ([#1316](https://github.com/must/BlockNote/pull/1316))
- collaboration wrapping to new line (firefox on linux) ([#1273](https://github.com/must/BlockNote/pull/1273))
- Table copy paste into spreadsheets ([#1298](https://github.com/must/BlockNote/pull/1298), [#1319](https://github.com/must/BlockNote/pull/1319))
- better paste handling ([#1324](https://github.com/must/BlockNote/pull/1324))
- Selecting start of table cell ([#1354](https://github.com/must/BlockNote/pull/1354))
- Code block language parsing ([#1362](https://github.com/must/BlockNote/pull/1362))
- Multi-editor drag & drop ([#1341](https://github.com/must/BlockNote/pull/1341))
- Cache & reuse Shiki highlighter & parser for improved performance ([#1363](https://github.com/must/BlockNote/pull/1363))
- Rollup config for `xl` and `server-util` packages ([#1365](https://github.com/must/BlockNote/pull/1365))
- Minor collaboration cursor & docs changes ([#1381](https://github.com/must/BlockNote/pull/1381))
- Adjust page break styles ([#1383](https://github.com/must/BlockNote/pull/1383))
- Side menu scrolling ([#1394](https://github.com/must/BlockNote/pull/1394))
- translation fix in fr.ts ([#1400](https://github.com/must/BlockNote/pull/1400))
- Drag and drop event handling ([#1413](https://github.com/must/BlockNote/pull/1413))
- shadcn button type ([#1416](https://github.com/must/BlockNote/pull/1416))
- improve collab cursor code ([#1405](https://github.com/must/BlockNote/pull/1405))
- cursors will not break to new-line on firefox and fix zoom on chrome #1419 ([#1422](https://github.com/must/BlockNote/pull/1422), [#1419](https://github.com/must/BlockNote/issues/1419))
- collaboration cursor chrome should not wrap mid-line ([#1423](https://github.com/must/BlockNote/pull/1423))
- chrome zoom bug ([#1426](https://github.com/must/BlockNote/pull/1426))
- upgrade prosemirror view and use correct clipboard import ([#1431](https://github.com/must/BlockNote/pull/1431))
- cut/copy handling in non-editable blocks and empty selections ([#1427](https://github.com/must/BlockNote/pull/1427))
- insertblocks when no type is provided ([#1436](https://github.com/must/BlockNote/pull/1436))
- placeholder improvements ([#1439](https://github.com/must/BlockNote/pull/1439))
- Blocks being deleted when dropped outside editor container ([#1443](https://github.com/must/BlockNote/pull/1443))
- add detail to collab cursor error ([#1449](https://github.com/must/BlockNote/pull/1449))
- drag & drop issues ([#1458](https://github.com/must/BlockNote/pull/1458))
- Formatting toolbar `mouseup` handler ([#1460](https://github.com/must/BlockNote/pull/1460))
- Mantine CSS variables element ([#1463](https://github.com/must/BlockNote/pull/1463))
- rm unused link ([ac4ee8f0](https://github.com/must/BlockNote/commit/ac4ee8f0))
- externalize react-dom/client ([#1483](https://github.com/must/BlockNote/pull/1483))
- forward refs to the final component ([#1485](https://github.com/must/BlockNote/pull/1485))
- make link hovered by mouse only considered in updates dispatched by `mouseover` handler ([#1486](https://github.com/must/BlockNote/pull/1486))
- typo of peerDependenciesMeta ([#1495](https://github.com/must/BlockNote/pull/1495))
- update package-lock ([fe967455](https://github.com/must/BlockNote/commit/fe967455))
- scope cursor caret CSS to be more specific ([#1492](https://github.com/must/BlockNote/pull/1492))
- compatibility with new react-pdf ([#1494](https://github.com/must/BlockNote/pull/1494))
- pull from the default export which is available in both ESM and CJS ([#1468](https://github.com/must/BlockNote/pull/1468), [#1493](https://github.com/must/BlockNote/pull/1493))
- upgrade y-prosemirror and remove clientID hack ([#1497](https://github.com/must/BlockNote/pull/1497))
- prefix the collaboration cursor classname ([#1498](https://github.com/must/BlockNote/pull/1498))
- import emoji-mart dynamically like ([#950](https://github.com/must/BlockNote/pull/950), [#1491](https://github.com/must/BlockNote/pull/1491))
- resolve unneeded error being thrown ([#1503](https://github.com/must/BlockNote/pull/1503))
- check for undefined headerMatrix resolves #1506 ([#1507](https://github.com/must/BlockNote/pull/1507), [#1506](https://github.com/must/BlockNote/issues/1506))
- React custom blocks not valid drop targets ([#1511](https://github.com/must/BlockNote/pull/1511))
- Drag & drop for blocks with iframes not working ([#1531](https://github.com/must/BlockNote/pull/1531))
- table error in collaboration mode ([8e9195b5](https://github.com/must/BlockNote/commit/8e9195b5))
- resolve several sentry errors ([#1524](https://github.com/must/BlockNote/pull/1524))
- improve markview setup ([#1544](https://github.com/must/BlockNote/pull/1544))
- add unit test for table parsing ([#1547](https://github.com/must/BlockNote/pull/1547))
- immediately add nodeviews to fix flushSync error ([#1546](https://github.com/must/BlockNote/pull/1546))
- Backspace in empty block deletes previous block ([#1505](https://github.com/must/BlockNote/pull/1505))
- Selection when clicking past end of inline content ([#1553](https://github.com/must/BlockNote/pull/1553))
- better expose setting a draghandlemenu's items #1525 ([#1526](https://github.com/must/BlockNote/pull/1526), [#1525](https://github.com/must/BlockNote/issues/1525))
- Multi-block links ([#1565](https://github.com/must/BlockNote/pull/1565))
- Hard break keyboard shortcut not working in custom blocks ([#1554](https://github.com/must/BlockNote/pull/1554))
- Overlapping marks in comments ([#1564](https://github.com/must/BlockNote/pull/1564))
- some more sentry fixes ([#1577](https://github.com/must/BlockNote/pull/1577))
- update packages to use correct react versions ([ea11ebce](https://github.com/must/BlockNote/commit/ea11ebce))
- minor update for publishing ([c2820fda](https://github.com/must/BlockNote/commit/c2820fda))
- allow opening another suggestion menu if another is triggered #1473 ([#1591](https://github.com/must/BlockNote/pull/1591), [#1473](https://github.com/must/BlockNote/issues/1473))
- add quote to schema ([aa16b15f](https://github.com/must/BlockNote/commit/aa16b15f))
- update y-prosemirror to fix #1462 ([#1608](https://github.com/must/BlockNote/pull/1608), [#1462](https://github.com/must/BlockNote/issues/1462))
- dispatch suggestion menu as a separate transaction ([#1614](https://github.com/must/BlockNote/pull/1614))
- try not to always use workspace version ([7af344ea](https://github.com/must/BlockNote/commit/7af344ea))
- Formatting toolbar regression ([#1630](https://github.com/must/BlockNote/pull/1630))
- provide `blockId` to `uploadFile` in UploadTab ([#1641](https://github.com/must/BlockNote/pull/1641))
- do not close the menu on content/selection change ([#1644](https://github.com/must/BlockNote/pull/1644))
- keep file panel open during collaboration ([#1646](https://github.com/must/BlockNote/pull/1646))
- force pasting plain text into code block ([#1663](https://github.com/must/BlockNote/pull/1663))
- updating HTML parsing rules to account for `prosemirror-model@1.25.1` ([#1661](https://github.com/must/BlockNote/pull/1661))
- better type-safety ([678086d4](https://github.com/must/BlockNote/commit/678086d4))
- do not use `editor.dispatch` ([#1698](https://github.com/must/BlockNote/pull/1698))
- re-added `display: flex` to blocks without inline content ([#1702](https://github.com/must/BlockNote/pull/1702))
- Playwright flaky keyboard handler test ([#1704](https://github.com/must/BlockNote/pull/1704))
- backwards-compat for `_extensions` ([#1708](https://github.com/must/BlockNote/pull/1708))
- re-release ([0bc546e1](https://github.com/must/BlockNote/commit/0bc546e1))
- ignore falsy values in boolean prop schema ([#1730](https://github.com/must/BlockNote/pull/1730))
- AI generation with empty document ([#1740](https://github.com/must/BlockNote/pull/1740))
- do not send a welcome email if magic link was used on an account older than a minute ago ([db88fe4a](https://github.com/must/BlockNote/commit/db88fe4a))
- AI system messages should always be at start of prompt ([#1741](https://github.com/must/BlockNote/pull/1741))
- Selection clicking editor padding ([#1717](https://github.com/must/BlockNote/pull/1717))
- preserve marks across a shift+enter #1672 ([#1743](https://github.com/must/BlockNote/pull/1743), [#1672](https://github.com/must/BlockNote/issues/1672))
- react 19 strict mode compatibility ([#1726](https://github.com/must/BlockNote/pull/1726))
- add keys to pdf exporter ([#1739](https://github.com/must/BlockNote/pull/1739))
- only listten for left click on formatting toolbar ([#1774](https://github.com/must/BlockNote/pull/1774))
- prevent formatting toolbar from closing if click was from inside the editor ([#1775](https://github.com/must/BlockNote/pull/1775))
- support multi-character suggestions ([#1734](https://github.com/must/BlockNote/pull/1734))
- switch foreground color based on selected user color dynamically #1785 ([#1787](https://github.com/must/BlockNote/pull/1787), [#1785](https://github.com/must/BlockNote/issues/1785))
- mark react package as external in email exporter ([#1807](https://github.com/must/BlockNote/pull/1807))
- Duplicate `formatConversionTest` files ([#1798](https://github.com/must/BlockNote/pull/1798))
- AI empty document handling ([#1810](https://github.com/must/BlockNote/pull/1810))
- `bn-inline-content` class name getting duplicated ([#1794](https://github.com/must/BlockNote/pull/1794))
- remove lookbehind regex for browser compat ([#1827](https://github.com/must/BlockNote/pull/1827))
- `ToggleWrapper` button defaulting to `submit` type ([#1823](https://github.com/must/BlockNote/pull/1823))
- disable $ref in AI schemas (html format) ([#1819](https://github.com/must/BlockNote/pull/1819))
- re-evaluate side-menu on scroll ([#1830](https://github.com/must/BlockNote/pull/1830))
- hide table extend buttons when not editable #1848 ([#1850](https://github.com/must/BlockNote/pull/1850), [#1848](https://github.com/must/BlockNote/issues/1848))
- resolve several drag & drop issues ([#1845](https://github.com/must/BlockNote/pull/1845))
- insert file upload before block if it is closer to the top of the block ([#1857](https://github.com/must/BlockNote/pull/1857))
- rename albert model ([3b0ba8d2](https://github.com/must/BlockNote/commit/3b0ba8d2))
- resolve some minor drag & drop regressions ([#1862](https://github.com/must/BlockNote/pull/1862))
- blockquote HTML parsing #1762 ([#1877](https://github.com/must/BlockNote/pull/1877), [#1762](https://github.com/must/BlockNote/issues/1762))
- Editors in comments not inheriting theme ([#1890](https://github.com/must/BlockNote/pull/1890))
- **ai:** undo-redo after accepting/rejecting changes will undo as expected ([#1752](https://github.com/must/BlockNote/pull/1752))
- **code-block:** handle unknown languages better ([#1626](https://github.com/must/BlockNote/pull/1626))
- **commentss:** small comment issues ([#1520](https://github.com/must/BlockNote/pull/1520))
- **locales:** add slovak i18n ([#1649](https://github.com/must/BlockNote/pull/1649))
- **locales:** add translations for some comment strings ([#1764](https://github.com/must/BlockNote/pull/1764))
- **locales:** add Hebrew translations for various components ([#1779](https://github.com/must/BlockNote/pull/1779))
- **react:** export react components #1509 ([#1510](https://github.com/must/BlockNote/pull/1510), [#1509](https://github.com/must/BlockNote/issues/1509))
- **react:** add missing exports ([#1689](https://github.com/must/BlockNote/pull/1689))
- **ui:** missing margin in checklist while in RTL ([#827](https://github.com/must/BlockNote/pull/827))
- **website:** log in bug fixes ([#1742](https://github.com/must/BlockNote/pull/1742))

### ❤️ Thank You

- andrewmnlv @andrewmnlv
- Arek Nawo @areknawo
- Aslam @Aslam97
- Bara Kona @BaraKona
- Brad Greenlee
- Bryan
- Conor Broderick
- daisy @linxianxi
- Damien Schneider @damien-schneider
- Daniel Lucas
- Deepak Kumar @i-am-chitti
- Diogo Cadavez
- Dominik Łasiński @Dmkk01
- Drew Johnson
- Ethan Chen @jkcs
- Ezhil Shanmugham
- Gonçalo Basto @gbasto
- Héctor Zhuang @Hector-Zhuang
- Hoonseok @hoongding
- Horacio Herrera @horacioh
- Hunain Ahmed @hunxjunedo
- Ivan
- Jhonattan Santos @jhonattan-santos
- Jonathan Marbutt @jmarbutt
- Junho @d2n0s4ur
- jurmaev @jurmaev
- Kashif Wahaj @Kashifwahaj
- l0st0 @l0st0
- Lawrence Lin @linyiru
- lujdong @SadEaston
- Martin Anselmo
- Martinrsts @Martinrsts
- Matthew Lipski @matthewlipski
- Matthias Risto @m-risto
- MengXi @Crayon-ShinChan
- Michael Wonng @mwonng
- Mustapha Ben Chaaben @must
- Muvels @Muvels
- Nick Perez @nperez0111
- Nick the Sick @nperez0111
- noblejasper @noblejasper
- Philip @PhilipWillms
- Quentin Nativel
- Ryan Fogle
- Samuel Bisberg
- Steffen Beyer @serpent213
- tensor tian @tensor-tian
- tpostoliuk @tpostolyuk
- Vinicius Fernandes @ViniCleFer
- virgile-dev
- Vivek Shah
- Yousef
- yousefed
- Zakher Masri @zaaakher
- Zeyu Zhang @zeyu2001

## 0.35.0 (2025-07-25)

### 🚀 Features

- use fumadocs for website ([#1654](https://github.com/TypeCellOS/BlockNote/pull/1654))
- llms.mdx routes ([cea93840e](https://github.com/TypeCellOS/BlockNote/commit/cea93840e))

### 🩹 Fixes

- insert file upload before block if it is closer to the top of the block ([#1857](https://github.com/TypeCellOS/BlockNote/pull/1857))
- rename albert model ([3b0ba8d25](https://github.com/TypeCellOS/BlockNote/commit/3b0ba8d25))
- resolve some minor drag & drop regressions ([#1862](https://github.com/TypeCellOS/BlockNote/pull/1862))
- blockquote HTML parsing #1762 ([#1877](https://github.com/TypeCellOS/BlockNote/pull/1877), [#1762](https://github.com/TypeCellOS/BlockNote/issues/1762))

### ❤️ Thank You

- Brad Greenlee
- Nick Perez
- Nick the Sick
- yousefed

## 0.34.0 (2025-07-17)

### 🚀 Features

- support multi-column block in PDF, DOCX & ODT exporters ([#1781](https://github.com/TypeCellOS/BlockNote/pull/1781))
- support react 19 ([f7b3466d3](https://github.com/TypeCellOS/BlockNote/commit/f7b3466d3))
- disable conversion of headings to list items ([#1799](https://github.com/TypeCellOS/BlockNote/pull/1799))
- report `moves` (indents and outdents) as changes when using `getChanges` #1757 ([#1786](https://github.com/TypeCellOS/BlockNote/pull/1786), [#1757](https://github.com/TypeCellOS/BlockNote/issues/1757))
- allow inline content to be `draggable` ([#1818](https://github.com/TypeCellOS/BlockNote/pull/1818))
- added type guards, types, and `editor` prop to custom inline content rendering ([#1736](https://github.com/TypeCellOS/BlockNote/pull/1736))
- **block-change:** adds a new API for blocking changes to editor state, by filtering transactions ([#1750](https://github.com/TypeCellOS/BlockNote/pull/1750))

### 🩹 Fixes

- remove lookbehind regex for browser compat ([#1827](https://github.com/TypeCellOS/BlockNote/pull/1827))
- `ToggleWrapper` button defaulting to `submit` type ([#1823](https://github.com/TypeCellOS/BlockNote/pull/1823))
- disable $ref in AI schemas (html format) ([#1819](https://github.com/TypeCellOS/BlockNote/pull/1819))
- re-evaluate side-menu on scroll ([#1830](https://github.com/TypeCellOS/BlockNote/pull/1830))
- hide table extend buttons when not editable #1848 ([#1850](https://github.com/TypeCellOS/BlockNote/pull/1850), [#1848](https://github.com/TypeCellOS/BlockNote/issues/1848))
- resolve several drag & drop issues ([#1845](https://github.com/TypeCellOS/BlockNote/pull/1845))

### ❤️ Thank You

- Arek Nawo @areknawo
- Gonçalo Basto @gbasto
- Héctor Zhuang @Hector-Zhuang
- Matthew Lipski @matthewlipski
- Nick Perez
- Nick the Sick @nperez0111
- Yousef

## 0.33.0 (2025-07-03)

### 🚀 Features

- FloatingUI options prop for `BlockPositioner` ([#1801](https://github.com/TypeCellOS/BlockNote/pull/1801))
- Support Google Gemini AI ([#1805](https://github.com/TypeCellOS/BlockNote/pull/1805))

### 🩹 Fixes

- support multi-character suggestions ([#1734](https://github.com/TypeCellOS/BlockNote/pull/1734))
- switch foreground color based on selected user color dynamically #1785 ([#1787](https://github.com/TypeCellOS/BlockNote/pull/1787), [#1785](https://github.com/TypeCellOS/BlockNote/issues/1785))
- mark react package as external in email exporter ([#1807](https://github.com/TypeCellOS/BlockNote/pull/1807))
- Duplicate `formatConversionTest` files ([#1798](https://github.com/TypeCellOS/BlockNote/pull/1798))
- AI empty document handling ([#1810](https://github.com/TypeCellOS/BlockNote/pull/1810))
- `bn-inline-content` class name getting duplicated ([#1794](https://github.com/TypeCellOS/BlockNote/pull/1794))

### ❤️ Thank You

- Matthew Lipski @matthewlipski
- Nick Perez
- Yousef

## 0.32.0 (2025-06-24)

### 🚀 Features

- toggle blocks ([#1707](https://github.com/TypeCellOS/BlockNote/pull/1707))
- **core:** support h4, h5, and h6 ([#1634](https://github.com/TypeCellOS/BlockNote/pull/1634))
- **xl-email-exporter:** add email exporter ([#1768](https://github.com/TypeCellOS/BlockNote/pull/1768))

### 🩹 Fixes

- react 19 strict mode compatibility ([#1726](https://github.com/TypeCellOS/BlockNote/pull/1726))
- add keys to pdf exporter ([#1739](https://github.com/TypeCellOS/BlockNote/pull/1739))
- only listten for left click on formatting toolbar ([#1774](https://github.com/TypeCellOS/BlockNote/pull/1774))
- prevent formatting toolbar from closing if click was from inside the editor ([#1775](https://github.com/TypeCellOS/BlockNote/pull/1775))
- **locales:** add Hebrew translations for various components ([#1779](https://github.com/TypeCellOS/BlockNote/pull/1779))

### ❤️ Thank You

- Aslam @Aslam97
- Drew Johnson
- Jonathan Marbutt @jmarbutt
- Matthew Lipski @matthewlipski
- Nick Perez
- Samuel Bisberg
- Yousef

## 0.31.3 (2025-06-18)

### 🩹 Fixes

- AI generation with empty document ([#1740](https://github.com/TypeCellOS/BlockNote/pull/1740))
- do not send a welcome email if magic link was used on an account older than a minute ago ([db88fe4aa](https://github.com/TypeCellOS/BlockNote/commit/db88fe4aa))
- AI system messages should always be at start of prompt ([#1741](https://github.com/TypeCellOS/BlockNote/pull/1741))
- Selection clicking editor padding ([#1717](https://github.com/TypeCellOS/BlockNote/pull/1717))
- preserve marks across a shift+enter #1672 ([#1743](https://github.com/TypeCellOS/BlockNote/pull/1743), [#1672](https://github.com/TypeCellOS/BlockNote/issues/1672))
- **ai:** undo-redo after accepting/rejecting changes will undo as expected ([#1752](https://github.com/TypeCellOS/BlockNote/pull/1752))
- **locales:** add translations for some comment strings ([#1764](https://github.com/TypeCellOS/BlockNote/pull/1764))
- **website:** log in bug fixes ([#1742](https://github.com/TypeCellOS/BlockNote/pull/1742))

### ❤️ Thank You

- Matthew Lipski @matthewlipski
- Nick Perez
- Nick the Sick
- Vinicius Fernandes @ViniCleFer
- Yousef

## 0.31.2 (2025-06-05)

### 🩹 Fixes

- re-release ([0bc546e18](https://github.com/TypeCellOS/BlockNote/commit/0bc546e18))
- ignore falsy values in boolean prop schema ([#1730](https://github.com/TypeCellOS/BlockNote/pull/1730))

### ❤️ Thank You

- Nick Perez
- Nick the Sick

## 0.31.1 (2025-05-23)

### 🩹 Fixes

- backwards-compat for `_extensions` ([#1708](https://github.com/TypeCellOS/BlockNote/pull/1708))

### ❤️ Thank You

- Nick Perez

## 0.31.0 (2025-05-20)

### 🩹 Fixes

- Playwright flaky keyboard handler test ([#1704](https://github.com/TypeCellOS/BlockNote/pull/1704))

### ❤️ Thank You

- Matthew Lipski @matthewlipski

## 0.30.1 (2025-05-20)

### 🩹 Fixes

- better type-safety ([678086d4d](https://github.com/TypeCellOS/BlockNote/commit/678086d4d))
- do not use `editor.dispatch` ([#1698](https://github.com/TypeCellOS/BlockNote/pull/1698))
- re-added `display: flex` to blocks without inline content ([#1702](https://github.com/TypeCellOS/BlockNote/pull/1702))
- **react:** add missing exports ([#1689](https://github.com/TypeCellOS/BlockNote/pull/1689))

### ❤️ Thank You

- Matthew Lipski @matthewlipski
- Nick Perez
- Nick the Sick

## 0.30.0 (2025-05-09)

### 🚀 Features

- expose `editor.prosemirrorState` again ([#1615](https://github.com/TypeCellOS/BlockNote/pull/1615))
- add `undo` and `redo` methods to editor API ([#1592](https://github.com/TypeCellOS/BlockNote/pull/1592))
- new auth & payment system ([#1617](https://github.com/TypeCellOS/BlockNote/pull/1617))
- re-implement Y.js collaboration as BlockNote plugins ([#1638](https://github.com/TypeCellOS/BlockNote/pull/1638))
- **file:** `previewWidth` prop now defaults to `undefined` ([#1664](https://github.com/TypeCellOS/BlockNote/pull/1664))
- **locales:** add zh-TW i18n ([#1668](https://github.com/TypeCellOS/BlockNote/pull/1668))

### 🩹 Fixes

- Formatting toolbar regression ([#1630](https://github.com/TypeCellOS/BlockNote/pull/1630))
- provide `blockId` to `uploadFile` in UploadTab ([#1641](https://github.com/TypeCellOS/BlockNote/pull/1641))
- do not close the menu on content/selection change ([#1644](https://github.com/TypeCellOS/BlockNote/pull/1644))
- keep file panel open during collaboration ([#1646](https://github.com/TypeCellOS/BlockNote/pull/1646))
- force pasting plain text into code block ([#1663](https://github.com/TypeCellOS/BlockNote/pull/1663))
- updating HTML parsing rules to account for `prosemirror-model@1.25.1` ([#1661](https://github.com/TypeCellOS/BlockNote/pull/1661))
- **code-block:** handle unknown languages better ([#1626](https://github.com/TypeCellOS/BlockNote/pull/1626))
- **locales:** add slovak i18n ([#1649](https://github.com/TypeCellOS/BlockNote/pull/1649))

### ❤️ Thank You

- l0st0 @l0st0
- Lawrence Lin @linyiru
- Matthew Lipski @matthewlipski
- Nick Perez
- Quentin Nativel

## 0.29.1 (2025-04-17)

### 🩹 Fixes

- try not to always use workspace version ([7af344ea9](https://github.com/TypeCellOS/BlockNote/commit/7af344ea9))

### ❤️ Thank You

- Nick the Sick

## 0.29.0 (2025-04-17)

### 🚀 Features

- `change` event allows getting a list of the block changed ([#1585](https://github.com/TypeCellOS/BlockNote/pull/1585))

### 🩹 Fixes

- allow opening another suggestion menu if another is triggered #1473 ([#1591](https://github.com/TypeCellOS/BlockNote/pull/1591), [#1473](https://github.com/TypeCellOS/BlockNote/issues/1473))
- add quote to schema ([aa16b15fe](https://github.com/TypeCellOS/BlockNote/commit/aa16b15fe))
- update y-prosemirror to fix #1462 ([#1608](https://github.com/TypeCellOS/BlockNote/pull/1608), [#1462](https://github.com/TypeCellOS/BlockNote/issues/1462))
- dispatch suggestion menu as a separate transaction ([#1614](https://github.com/TypeCellOS/BlockNote/pull/1614))

### ❤️ Thank You

- Nick Perez
- Nick the Sick

## 0.28.0 (2025-04-07)

### 🚀 Features

- position storage ([#1529](https://github.com/TypeCellOS/BlockNote/pull/1529))

### ❤️ Thank You

- Nick Perez

## 0.27.2 (2025-04-05)

### 🩹 Fixes

- minor update for publishing ([c2820fdac](https://github.com/TypeCellOS/BlockNote/commit/c2820fdac))

### ❤️ Thank You

- Nick the Sick

## 0.27.1 (2025-04-05)

### 🚀 Features

- **nx-cloud:** set up nx workspace ([#1586](https://github.com/TypeCellOS/BlockNote/pull/1586))

### 🩹 Fixes

- update packages to use correct react versions ([ea11ebce0](https://github.com/TypeCellOS/BlockNote/commit/ea11ebce0))

### ❤️ Thank You

- Nick Perez
- Nick the Sick

## 0.27.0 (2025-04-04)

### 🚀 Features

- split out localization files for optimized bundle ([#1533](https://github.com/TypeCellOS/BlockNote/pull/1533))
- remove shiki dep, add new @blocknote/code-block package for slim shiki build ([#1519](https://github.com/TypeCellOS/BlockNote/pull/1519))
- Block quote ([#1563](https://github.com/TypeCellOS/BlockNote/pull/1563))
- markdown pasting & custom paste handlers ([#1490](https://github.com/TypeCellOS/BlockNote/pull/1490))

### 🩹 Fixes

- Backspace in empty block deletes previous block ([#1505](https://github.com/TypeCellOS/BlockNote/pull/1505))
- Selection when clicking past end of inline content ([#1553](https://github.com/TypeCellOS/BlockNote/pull/1553))
- better expose setting a draghandlemenu's items #1525 ([#1526](https://github.com/TypeCellOS/BlockNote/pull/1526), [#1525](https://github.com/TypeCellOS/BlockNote/issues/1525))
- Multi-block links ([#1565](https://github.com/TypeCellOS/BlockNote/pull/1565))
- Hard break keyboard shortcut not working in custom blocks ([#1554](https://github.com/TypeCellOS/BlockNote/pull/1554))
- Overlapping marks in comments ([#1564](https://github.com/TypeCellOS/BlockNote/pull/1564))
- some more sentry fixes ([#1577](https://github.com/TypeCellOS/BlockNote/pull/1577))

### ❤️ Thank You

- Martinrsts @Martinrsts
- Matthew Lipski @matthewlipski
- Nick Perez

## Previous Versions

See [Github Releases](https://github.com/TypeCellOS/BlockNote/releases) for previous versions.
