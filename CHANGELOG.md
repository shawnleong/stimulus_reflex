# Changelog

## [Unreleased](https://github.com/hopsoft/stimulus_reflex/tree/HEAD)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.3.0.pre2...HEAD)

**Merged pull requests:**

- Simplify devise authentication logic \(in docs\) [\#276](https://github.com/hopsoft/stimulus_reflex/pull/276) ([inner-whisper](https://github.com/inner-whisper))
- Bump lodash from 4.17.15 to 4.17.19 in /javascript [\#275](https://github.com/hopsoft/stimulus_reflex/pull/275) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v3.3.0.pre2](https://github.com/hopsoft/stimulus_reflex/tree/v3.3.0.pre2) (2020-07-17)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.3.0.pre1...v3.3.0.pre2)

**Closed issues:**

- afterReflex not always firing on morph with selectors [\#269](https://github.com/hopsoft/stimulus_reflex/issues/269)
- Lifecycle hooks [\#266](https://github.com/hopsoft/stimulus_reflex/issues/266)
- Stimulus Reflex with Rspec not working [\#263](https://github.com/hopsoft/stimulus_reflex/issues/263)

**Merged pull requests:**

- Smarter warnings when element not found [\#274](https://github.com/hopsoft/stimulus_reflex/pull/274) ([hopsoft](https://github.com/hopsoft))
- Add the attributes to the warning message when element not found [\#273](https://github.com/hopsoft/stimulus_reflex/pull/273) ([hopsoft](https://github.com/hopsoft))
- Update find element to ignore SR attrs [\#272](https://github.com/hopsoft/stimulus_reflex/pull/272) ([hopsoft](https://github.com/hopsoft))
- Refactor of the morph feature [\#270](https://github.com/hopsoft/stimulus_reflex/pull/270) ([hopsoft](https://github.com/hopsoft))
- coerce html arguments to string type [\#268](https://github.com/hopsoft/stimulus_reflex/pull/268) ([leastbad](https://github.com/leastbad))
- Update deployment docs after the official AnyCable 1.0 release [\#267](https://github.com/hopsoft/stimulus_reflex/pull/267) ([rmacklin](https://github.com/rmacklin))

## [v3.3.0.pre1](https://github.com/hopsoft/stimulus_reflex/tree/v3.3.0.pre1) (2020-07-08)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.3.0.pre0...v3.3.0.pre1)

**Merged pull requests:**

- Fix selector morphs for updating partials and ViewComponents [\#262](https://github.com/hopsoft/stimulus_reflex/pull/262) ([leastbad](https://github.com/leastbad))

## [v3.3.0.pre0](https://github.com/hopsoft/stimulus_reflex/tree/v3.3.0.pre0) (2020-07-04)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.3...v3.3.0.pre0)

**Implemented enhancements:**

- Returns more helpful error message if Reflex doesn't exist [\#254](https://github.com/hopsoft/stimulus_reflex/pull/254) ([leastbad](https://github.com/leastbad))
- Update install.rake to handle Typescript [\#241](https://github.com/hopsoft/stimulus_reflex/pull/241) ([iv-mexx](https://github.com/iv-mexx))
- Morph Modes: page, selector and nothing [\#211](https://github.com/hopsoft/stimulus_reflex/pull/211) ([leastbad](https://github.com/leastbad))

**Fixed bugs:**

- Limit MutationObserver mutations [\#256](https://github.com/hopsoft/stimulus_reflex/pull/256) ([jasoncharnes](https://github.com/jasoncharnes))

**Closed issues:**

- beforeUpdate/updateSuccess/updateError functions deprecated? [\#255](https://github.com/hopsoft/stimulus_reflex/issues/255)
- Error handling will fail if reflex is not defined [\#253](https://github.com/hopsoft/stimulus_reflex/issues/253)
- Select with data-reflex in Firefox flickers [\#251](https://github.com/hopsoft/stimulus_reflex/issues/251)
- data-reflex-attributes vs data-reflex-dataset [\#237](https://github.com/hopsoft/stimulus_reflex/issues/237)
- Shorthand action notations corresponding to stimulus [\#233](https://github.com/hopsoft/stimulus_reflex/issues/233)
- Lifecycle methods only called for one reflex [\#225](https://github.com/hopsoft/stimulus_reflex/issues/225)
- Tweak the generator so we can specify reflex actions [\#219](https://github.com/hopsoft/stimulus_reflex/issues/219)
- Docs: Clarify forcing DOM update with authentication [\#123](https://github.com/hopsoft/stimulus_reflex/issues/123)
- ActiveJob integration example [\#112](https://github.com/hopsoft/stimulus_reflex/issues/112)

**Merged pull requests:**

- Prep for pre release of 3.3.0 [\#259](https://github.com/hopsoft/stimulus_reflex/pull/259) ([hopsoft](https://github.com/hopsoft))
- Fallback to first Stimulus controller in array [\#257](https://github.com/hopsoft/stimulus_reflex/pull/257) ([jasoncharnes](https://github.com/jasoncharnes))
- Fix cases where plural reflexes were unresolved [\#252](https://github.com/hopsoft/stimulus_reflex/pull/252) ([joshleblanc](https://github.com/joshleblanc))
- warn against collections of identical elements that trigger reflexes [\#250](https://github.com/hopsoft/stimulus_reflex/pull/250) ([leastbad](https://github.com/leastbad))
- always calls params to persist them into controller action [\#249](https://github.com/hopsoft/stimulus_reflex/pull/249) ([RolandStuder](https://github.com/RolandStuder))
- Update deployment.md [\#248](https://github.com/hopsoft/stimulus_reflex/pull/248) ([user073](https://github.com/user073))
- Update reflexes.md [\#247](https://github.com/hopsoft/stimulus_reflex/pull/247) ([user073](https://github.com/user073))
- Bump actionpack from 6.0.3.1 to 6.0.3.2 [\#245](https://github.com/hopsoft/stimulus_reflex/pull/245) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump rack from 2.2.2 to 2.2.3 [\#244](https://github.com/hopsoft/stimulus_reflex/pull/244) ([dependabot[bot]](https://github.com/apps/dependabot))
- Revert "Revert "Add instructions for pulling the user id out of session storage"" [\#240](https://github.com/hopsoft/stimulus_reflex/pull/240) ([leastbad](https://github.com/leastbad))
- Revert "Add instructions for pulling the user id out of session storage" [\#239](https://github.com/hopsoft/stimulus_reflex/pull/239) ([leastbad](https://github.com/leastbad))
- Add instructions for pulling the user id out of session storage [\#238](https://github.com/hopsoft/stimulus_reflex/pull/238) ([mtomov](https://github.com/mtomov))
- adds params documentation [\#230](https://github.com/hopsoft/stimulus_reflex/pull/230) ([RolandStuder](https://github.com/RolandStuder))
- Fix calling wrong controller lifecycle methods [\#226](https://github.com/hopsoft/stimulus_reflex/pull/226) ([davidalejandroaguilar](https://github.com/davidalejandroaguilar))
- Allow to pass reflex action names to reflex generator [\#224](https://github.com/hopsoft/stimulus_reflex/pull/224) ([marcoroth](https://github.com/marcoroth))

## [v3.2.3](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.3) (2020-06-15)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.2...v3.2.3)

**Fixed bugs:**

- Add more smarts to \_\_perform [\#235](https://github.com/hopsoft/stimulus_reflex/pull/235) ([hopsoft](https://github.com/hopsoft))
- \_\_perform had a bug where it was only ever calling the first event [\#234](https://github.com/hopsoft/stimulus_reflex/pull/234) ([leastbad](https://github.com/leastbad))
- merges insteads of overwrites params for reflex actions with form data [\#231](https://github.com/hopsoft/stimulus_reflex/pull/231) ([RolandStuder](https://github.com/RolandStuder))

**Closed issues:**

- "Uncaught \(in promise\)" error after failed declarative reflex [\#170](https://github.com/hopsoft/stimulus_reflex/issues/170)

**Merged pull requests:**

- Fix typos in the documentation [\#228](https://github.com/hopsoft/stimulus_reflex/pull/228) ([dlt](https://github.com/dlt))

## [v3.2.2](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.2) (2020-06-06)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.2.pre1...v3.2.2)

**Closed issues:**

- Issue with doing a partial dom update [\#223](https://github.com/hopsoft/stimulus_reflex/issues/223)

## [v3.2.2.pre1](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.2.pre1) (2020-05-30)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.2.pre0...v3.2.2.pre1)

**Fixed bugs:**

- Session lost after throw :abort [\#221](https://github.com/hopsoft/stimulus_reflex/issues/221)
- Fix multipleInstances convenience method [\#220](https://github.com/hopsoft/stimulus_reflex/pull/220) ([julianrubisch](https://github.com/julianrubisch))

**Merged pull requests:**

- Always commit session [\#222](https://github.com/hopsoft/stimulus_reflex/pull/222) ([hopsoft](https://github.com/hopsoft))

## [v3.2.2.pre0](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.2.pre0) (2020-05-27)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.1...v3.2.2.pre0)

**Implemented enhancements:**

- Add a halted lifecycle event [\#190](https://github.com/hopsoft/stimulus_reflex/issues/190)
- Allow extractElementAttributes to use a checkbox list [\#147](https://github.com/hopsoft/stimulus_reflex/issues/147)
- reflex\_name restriction loosening [\#212](https://github.com/hopsoft/stimulus_reflex/pull/212) ([leastbad](https://github.com/leastbad))
- Make element even more user friendly [\#210](https://github.com/hopsoft/stimulus_reflex/pull/210) ([hopsoft](https://github.com/hopsoft))
- Form parameters [\#204](https://github.com/hopsoft/stimulus_reflex/pull/204) ([jasoncharnes](https://github.com/jasoncharnes))
- Map hashes in incoming arguments using with\_indifferent\_access [\#203](https://github.com/hopsoft/stimulus_reflex/pull/203) ([jaredcwhite](https://github.com/jaredcwhite))
- Combine dataset with data-attributes from parent elements on reflex call [\#200](https://github.com/hopsoft/stimulus_reflex/pull/200) ([marcoroth](https://github.com/marcoroth))
- Setup mutation aware declarative reflexes [\#197](https://github.com/hopsoft/stimulus_reflex/pull/197) ([hopsoft](https://github.com/hopsoft))

**Fixed bugs:**

- Text area values are lost if re-sized [\#195](https://github.com/hopsoft/stimulus_reflex/issues/195)

**Closed issues:**

- Accessing dataset as before is returning nil [\#218](https://github.com/hopsoft/stimulus_reflex/issues/218)
- Spurious console error using data-reflex-root and CSS attribute selector [\#207](https://github.com/hopsoft/stimulus_reflex/issues/207)
- ActionController Parameters [\#199](https://github.com/hopsoft/stimulus_reflex/issues/199)

**Merged pull requests:**

- Bump activesupport from 6.0.3 to 6.0.3.1 [\#217](https://github.com/hopsoft/stimulus_reflex/pull/217) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump activestorage from 6.0.3 to 6.0.3.1 [\#216](https://github.com/hopsoft/stimulus_reflex/pull/216) ([dependabot[bot]](https://github.com/apps/dependabot))
- Bump actionpack from 6.0.3 to 6.0.3.1 [\#215](https://github.com/hopsoft/stimulus_reflex/pull/215) ([dependabot[bot]](https://github.com/apps/dependabot))
- Update dataset handling and some minor refactoring to better naming [\#214](https://github.com/hopsoft/stimulus_reflex/pull/214) ([hopsoft](https://github.com/hopsoft))
- Stimulus reflexData assignment after callback  [\#208](https://github.com/hopsoft/stimulus_reflex/pull/208) ([jasoncharnes](https://github.com/jasoncharnes))
- Loosen Rails requirement to 5.2 with instructions [\#205](https://github.com/hopsoft/stimulus_reflex/pull/205) ([jasoncharnes](https://github.com/jasoncharnes))
- Fix undefined is not an object for Object.keys in log.js [\#201](https://github.com/hopsoft/stimulus_reflex/pull/201) ([marcoroth](https://github.com/marcoroth))
- Small typo/grammar fix in quickstart doc. [\#198](https://github.com/hopsoft/stimulus_reflex/pull/198) ([acoffman](https://github.com/acoffman))
- Add halted lifecycle event [\#193](https://github.com/hopsoft/stimulus_reflex/pull/193) ([seb1441](https://github.com/seb1441))
- 147 extract multiple checkbox values [\#175](https://github.com/hopsoft/stimulus_reflex/pull/175) ([julianrubisch](https://github.com/julianrubisch))

## [v3.2.1](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.1) (2020-05-09)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.0...v3.2.1)

**Merged pull requests:**

- Prevent halting if reflex returns false [\#194](https://github.com/hopsoft/stimulus_reflex/pull/194) ([hopsoft](https://github.com/hopsoft))

## [v3.2.0](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.0) (2020-05-09)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.0.pre1...v3.2.0)

## [v3.2.0.pre1](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.0.pre1) (2020-05-08)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.0-pre0...v3.2.0.pre1)

**Fixed bugs:**

- Add guard to morph that checks stimulusReflex [\#191](https://github.com/hopsoft/stimulus_reflex/pull/191) ([hopsoft](https://github.com/hopsoft))

## [v3.2.0-pre0](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.0-pre0) (2020-05-07)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.2.0.pre0...v3.2.0-pre0)

## [v3.2.0.pre0](https://github.com/hopsoft/stimulus_reflex/tree/v3.2.0.pre0) (2020-05-07)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.1.4...v3.2.0.pre0)

**Implemented enhancements:**

- Stimulate without a reflex target [\#179](https://github.com/hopsoft/stimulus_reflex/issues/179)
- Reflex callbacks [\#155](https://github.com/hopsoft/stimulus_reflex/issues/155)
- Replace camelize with homegrown version [\#184](https://github.com/hopsoft/stimulus_reflex/pull/184) ([jonathan-s](https://github.com/jonathan-s))
- Replace uuid4 dependency with function in repo [\#181](https://github.com/hopsoft/stimulus_reflex/pull/181) ([jonathan-s](https://github.com/jonathan-s))
- Allow channel exceptions to be rescuable [\#180](https://github.com/hopsoft/stimulus_reflex/pull/180) ([dark-panda](https://github.com/dark-panda))
- add console log messages for every reflex call [\#163](https://github.com/hopsoft/stimulus_reflex/pull/163) ([marcoroth](https://github.com/marcoroth))
- add reflex callbacks [\#160](https://github.com/hopsoft/stimulus_reflex/pull/160) ([seb1441](https://github.com/seb1441))

**Fixed bugs:**

-  Pluralize the generated class name, so that will match with the file name [\#178](https://github.com/hopsoft/stimulus_reflex/pull/178) ([darkrubyist](https://github.com/darkrubyist))
- Allow other CableReady operations to perform [\#145](https://github.com/hopsoft/stimulus_reflex/pull/145) ([hopsoft](https://github.com/hopsoft))

**Closed issues:**

-  The ActionCable connection is not open! `this.isActionCableConnectionOpen\(\)` must return true before calling `this.stimulate\(\)` [\#187](https://github.com/hopsoft/stimulus_reflex/issues/187)
- Promises just resolve with last Partial DOM update [\#171](https://github.com/hopsoft/stimulus_reflex/issues/171)

**Merged pull requests:**

- Some housekeeping [\#189](https://github.com/hopsoft/stimulus_reflex/pull/189) ([hopsoft](https://github.com/hopsoft))
- Allow to call stimulate without a reflex target [\#188](https://github.com/hopsoft/stimulus_reflex/pull/188) ([marcoroth](https://github.com/marcoroth))
- Fix bug in super documentation [\#174](https://github.com/hopsoft/stimulus_reflex/pull/174) ([silva96](https://github.com/silva96))

## [v3.1.4](https://github.com/hopsoft/stimulus_reflex/tree/v3.1.4) (2020-04-27)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.1.3...v3.1.4)

**Implemented enhancements:**

- TypeScript typing support [\#152](https://github.com/hopsoft/stimulus_reflex/issues/152)

**Fixed bugs:**

- Possible bug when about to perform cableready operations [\#166](https://github.com/hopsoft/stimulus_reflex/issues/166)
- Reflex not binding to ajax loaded content [\#161](https://github.com/hopsoft/stimulus_reflex/issues/161)
- Input field values sometimes remain [\#159](https://github.com/hopsoft/stimulus_reflex/issues/159)

**Closed issues:**

- Devise authenticated routes not supported anymore [\#173](https://github.com/hopsoft/stimulus_reflex/issues/173)
- CableReady detected an error in morph! Event is not a constructor [\#165](https://github.com/hopsoft/stimulus_reflex/issues/165)
- Testing Integrations [\#164](https://github.com/hopsoft/stimulus_reflex/issues/164)
- Error during install: "File unchanged! The supplied flag value not found!  app/javascript/packs/application.js" [\#118](https://github.com/hopsoft/stimulus_reflex/issues/118)
- Make the javascript in stimulus-reflex websocket agnostic [\#113](https://github.com/hopsoft/stimulus_reflex/issues/113)

**Merged pull requests:**

- prettier-standard: include all js files in the project [\#177](https://github.com/hopsoft/stimulus_reflex/pull/177) ([marcoroth](https://github.com/marcoroth))
- Remove implicit permanent for text inputs [\#176](https://github.com/hopsoft/stimulus_reflex/pull/176) ([hopsoft](https://github.com/hopsoft))
- Support devise authenticated routes [\#172](https://github.com/hopsoft/stimulus_reflex/pull/172) ([db0sch](https://github.com/db0sch))
- setupDeclarativeReflexes export with UJS support [\#169](https://github.com/hopsoft/stimulus_reflex/pull/169) ([leastbad](https://github.com/leastbad))
- Fix compilation issue [\#168](https://github.com/hopsoft/stimulus_reflex/pull/168) ([jonathan-s](https://github.com/jonathan-s))

## [v3.1.3](https://github.com/hopsoft/stimulus_reflex/tree/v3.1.3) (2020-04-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.1.2...v3.1.3)

**Implemented enhancements:**

- Server initiated redirects [\#25](https://github.com/hopsoft/stimulus_reflex/issues/25)

**Fixed bugs:**

- Unable to register the ActionCable Consumer [\#156](https://github.com/hopsoft/stimulus_reflex/issues/156)
- Remove unneeded registerConsumer logic [\#158](https://github.com/hopsoft/stimulus_reflex/pull/158) ([hopsoft](https://github.com/hopsoft))

**Closed issues:**

- Scoping when using Stimulus does not work as expected [\#144](https://github.com/hopsoft/stimulus_reflex/issues/144)
- Shared connections to reduce websocket connections? [\#136](https://github.com/hopsoft/stimulus_reflex/issues/136)
- routing reflexes to controllers [\#97](https://github.com/hopsoft/stimulus_reflex/issues/97)
- Time for introducing a develop branch? [\#84](https://github.com/hopsoft/stimulus_reflex/issues/84)
- out-of-band Reflex updates [\#64](https://github.com/hopsoft/stimulus_reflex/issues/64)

## [v3.1.2](https://github.com/hopsoft/stimulus_reflex/tree/v3.1.2) (2020-04-16)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.1.1...v3.1.2)

## [v3.1.1](https://github.com/hopsoft/stimulus_reflex/tree/v3.1.1) (2020-04-16)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.1.0...v3.1.1)

**Fixed bugs:**

- Cannot read property 'removeEventListener' of undefined after updating to 3.1.0 [\#151](https://github.com/hopsoft/stimulus_reflex/issues/151)
- remove changelog rake task [\#150](https://github.com/hopsoft/stimulus_reflex/pull/150) ([andrewmcodes](https://github.com/andrewmcodes))

**Closed issues:**

- Setup & Quick Start guide from scratch results in showstopping error [\#153](https://github.com/hopsoft/stimulus_reflex/issues/153)

**Merged pull requests:**

- Trap errors in registerConsumer [\#154](https://github.com/hopsoft/stimulus_reflex/pull/154) ([hopsoft](https://github.com/hopsoft))

## [v3.1.0](https://github.com/hopsoft/stimulus_reflex/tree/v3.1.0) (2020-04-15)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v3.0.0...v3.1.0)

**Implemented enhancements:**

- Check the ActionCable connection on stimuluate [\#148](https://github.com/hopsoft/stimulus_reflex/pull/148) ([hopsoft](https://github.com/hopsoft))
- Attach element.tagName to extracted attributes [\#146](https://github.com/hopsoft/stimulus_reflex/pull/146) ([julianrubisch](https://github.com/julianrubisch))
- Create dynamic changelog [\#143](https://github.com/hopsoft/stimulus_reflex/pull/143) ([andrewmcodes](https://github.com/andrewmcodes))
- add funding file [\#141](https://github.com/hopsoft/stimulus_reflex/pull/141) ([andrewmcodes](https://github.com/andrewmcodes))

**Closed issues:**

- Non-morph operations are not executed by CableReady on errors [\#139](https://github.com/hopsoft/stimulus_reflex/issues/139)
- Pass element tagname in reflex [\#137](https://github.com/hopsoft/stimulus_reflex/issues/137)
- ActionCable npm package renamed [\#132](https://github.com/hopsoft/stimulus_reflex/issues/132)

**Merged pull requests:**

- Allow \#stimulate to use promises [\#142](https://github.com/hopsoft/stimulus_reflex/pull/142) ([dark-panda](https://github.com/dark-panda))

## [v3.0.0](https://github.com/hopsoft/stimulus_reflex/tree/v3.0.0) (2020-04-06)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.2.3...v3.0.0)

**Breaking changes:**

- Update ActionCable JS dep to @rails/actioncable [\#135](https://github.com/hopsoft/stimulus_reflex/pull/135) ([hopsoft](https://github.com/hopsoft))

**Implemented enhancements:**

- update install script to set session store [\#134](https://github.com/hopsoft/stimulus_reflex/pull/134) ([leastbad](https://github.com/leastbad))
- update package.json and readme [\#133](https://github.com/hopsoft/stimulus_reflex/pull/133) ([andrewmcodes](https://github.com/andrewmcodes))

**Closed issues:**

- \[WIP\] AnyCable and Stimulus Reflex [\#46](https://github.com/hopsoft/stimulus_reflex/issues/46)

## [v2.2.3](https://github.com/hopsoft/stimulus_reflex/tree/v2.2.3) (2020-03-27)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.2.2...v2.2.3)

**Implemented enhancements:**

- Reload session prior to each reflex accessing it [\#131](https://github.com/hopsoft/stimulus_reflex/pull/131) ([hopsoft](https://github.com/hopsoft))
- tweak prettier-standard and add actions caching [\#125](https://github.com/hopsoft/stimulus_reflex/pull/125) ([andrewmcodes](https://github.com/andrewmcodes))

**Closed issues:**

- Cannot read property 'stimulusReflexController' of null [\#127](https://github.com/hopsoft/stimulus_reflex/issues/127)

**Merged pull requests:**

- Bump actionview from 6.0.2.1 to 6.0.2.2 [\#128](https://github.com/hopsoft/stimulus_reflex/pull/128) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v2.2.2](https://github.com/hopsoft/stimulus_reflex/tree/v2.2.2) (2020-03-04)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.2.1...v2.2.2)

**Implemented enhancements:**

- Commit session after rerendering page [\#124](https://github.com/hopsoft/stimulus_reflex/pull/124) ([hopsoft](https://github.com/hopsoft))
- Propose post install message [\#122](https://github.com/hopsoft/stimulus_reflex/pull/122) ([julianrubisch](https://github.com/julianrubisch))

## [v2.2.1](https://github.com/hopsoft/stimulus_reflex/tree/v2.2.1) (2020-02-28)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.2.0...v2.2.1)

**Fixed bugs:**

- Cleanup and fixes around lifecycle dispatch [\#121](https://github.com/hopsoft/stimulus_reflex/pull/121) ([hopsoft](https://github.com/hopsoft))

## [v2.2.0](https://github.com/hopsoft/stimulus_reflex/tree/v2.2.0) (2020-02-28)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.9...v2.2.0)

**Implemented enhancements:**

- Explicit and implicit registering of the ActionCable consumer [\#116](https://github.com/hopsoft/stimulus_reflex/pull/116) ([hopsoft](https://github.com/hopsoft))

## [v2.1.9](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.9) (2020-02-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.8...v2.1.9)

**Implemented enhancements:**

- Add lifecycle events [\#114](https://github.com/hopsoft/stimulus_reflex/issues/114)
- Setup DOM event based lifecycle [\#115](https://github.com/hopsoft/stimulus_reflex/pull/115) ([hopsoft](https://github.com/hopsoft))

## [v2.1.8](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.8) (2020-01-27)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.7...v2.1.8)

**Implemented enhancements:**

- More defense in the received handler [\#107](https://github.com/hopsoft/stimulus_reflex/pull/107) ([hopsoft](https://github.com/hopsoft))

**Fixed bugs:**

- Fix bug related to trailing slash in URL path [\#111](https://github.com/hopsoft/stimulus_reflex/pull/111) ([hopsoft](https://github.com/hopsoft))

## [v2.1.7](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.7) (2019-12-28)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.6...v2.1.7)

**Implemented enhancements:**

- Support devise authenticated routes [\#105](https://github.com/hopsoft/stimulus_reflex/pull/105) ([hopsoft](https://github.com/hopsoft))

**Closed issues:**

- SR cannot re-render authenticated devise routes [\#104](https://github.com/hopsoft/stimulus_reflex/issues/104)
- Docs formatting broken in Persistence section [\#93](https://github.com/hopsoft/stimulus_reflex/issues/93)

## [v2.1.6](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.6) (2019-12-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.5...v2.1.6)

**Implemented enhancements:**

- StimulusReflex::Channel - Error messages include stack trace info [\#100](https://github.com/hopsoft/stimulus_reflex/pull/100) ([szTheory](https://github.com/szTheory))

**Closed issues:**

- Demo appears to be broken [\#101](https://github.com/hopsoft/stimulus_reflex/issues/101)

## [v2.1.5](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.5) (2019-11-04)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.4...v2.1.5)

**Implemented enhancements:**

- Custom Stimulus schema breaks Reflex [\#91](https://github.com/hopsoft/stimulus_reflex/issues/91)
- Add schema support [\#94](https://github.com/hopsoft/stimulus_reflex/pull/94) ([hopsoft](https://github.com/hopsoft))
- inherit stimulus schema [\#92](https://github.com/hopsoft/stimulus_reflex/pull/92) ([nickyvanurk](https://github.com/nickyvanurk))
- Single source of truth [\#76](https://github.com/hopsoft/stimulus_reflex/pull/76) ([leastbad](https://github.com/leastbad))

**Fixed bugs:**

- Use application.js as fallback file path [\#82](https://github.com/hopsoft/stimulus_reflex/pull/82) ([julianrubisch](https://github.com/julianrubisch))

**Closed issues:**

- Slack Community [\#90](https://github.com/hopsoft/stimulus_reflex/issues/90)
- Installer fails on fresh Rails 5.2.3 app w/ webpacker 3.6 [\#81](https://github.com/hopsoft/stimulus_reflex/issues/81)
- Correct List Order in setup.md under Rooms Section [\#78](https://github.com/hopsoft/stimulus_reflex/issues/78)
- Scoped onClick event [\#73](https://github.com/hopsoft/stimulus_reflex/issues/73)

## [v2.1.4](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.4) (2019-10-19)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.3...v2.1.4)

**Implemented enhancements:**

- Add CodeFund sponsorship [\#75](https://github.com/hopsoft/stimulus_reflex/pull/75) ([coderberry](https://github.com/coderberry))

**Fixed bugs:**

- Don't assume that connection identifiers are model instances [\#77](https://github.com/hopsoft/stimulus_reflex/pull/77) ([hopsoft](https://github.com/hopsoft))

## [v2.1.3](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.3) (2019-10-16)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.2...v2.1.3)

**Implemented enhancements:**

- Create Rails generators [\#3](https://github.com/hopsoft/stimulus_reflex/issues/3)
- Update installer [\#71](https://github.com/hopsoft/stimulus_reflex/pull/71) ([hopsoft](https://github.com/hopsoft))
- Tweak generators [\#69](https://github.com/hopsoft/stimulus_reflex/pull/69) ([hopsoft](https://github.com/hopsoft))
- add generators [\#67](https://github.com/hopsoft/stimulus_reflex/pull/67) ([andrewmcodes](https://github.com/andrewmcodes))

**Fixed bugs:**

- too many afterReflex/reflexSuccess callbacks [\#68](https://github.com/hopsoft/stimulus_reflex/issues/68)
- Prevent redundant `after` lifecycle callbacks [\#70](https://github.com/hopsoft/stimulus_reflex/pull/70) ([hopsoft](https://github.com/hopsoft))

## [v2.1.2](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.2) (2019-10-09)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.1...v2.1.2)

## [v2.1.1](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.1) (2019-10-08)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.1.0...v2.1.1)

**Fixed bugs:**

- Fix issue in reflex root discovery [\#66](https://github.com/hopsoft/stimulus_reflex/pull/66) ([hopsoft](https://github.com/hopsoft))

## [v2.1.0](https://github.com/hopsoft/stimulus_reflex/tree/v2.1.0) (2019-10-07)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.0.2...v2.1.0)

**Implemented enhancements:**

- Move ActionCable room configuration to controller registration [\#51](https://github.com/hopsoft/stimulus_reflex/issues/51)
- Client side call-backs? [\#34](https://github.com/hopsoft/stimulus_reflex/issues/34)
- Scoped register\(\)? [\#26](https://github.com/hopsoft/stimulus_reflex/issues/26)
- Add guard to verify same URL prior to morph [\#63](https://github.com/hopsoft/stimulus_reflex/pull/63) ([hopsoft](https://github.com/hopsoft))
- Add reflex name to the lifecycle args [\#62](https://github.com/hopsoft/stimulus_reflex/pull/62) ([hopsoft](https://github.com/hopsoft))
- Refactor some helper methods out of main file [\#61](https://github.com/hopsoft/stimulus_reflex/pull/61) ([hopsoft](https://github.com/hopsoft))
- Documentation update [\#58](https://github.com/hopsoft/stimulus_reflex/pull/58) ([leastbad](https://github.com/leastbad))
- \# Support for data-reflex-permanent [\#57](https://github.com/hopsoft/stimulus_reflex/pull/57) ([hopsoft](https://github.com/hopsoft))
- Stricter parsing of attributes [\#56](https://github.com/hopsoft/stimulus_reflex/pull/56) ([hopsoft](https://github.com/hopsoft))
- \# Use inner\_html to avoid reliance on HTMLTemplateElement behavior [\#55](https://github.com/hopsoft/stimulus_reflex/pull/55) ([hopsoft](https://github.com/hopsoft))
- Trim values before attribute assignment [\#54](https://github.com/hopsoft/stimulus_reflex/pull/54) ([hopsoft](https://github.com/hopsoft))
- add test action [\#53](https://github.com/hopsoft/stimulus_reflex/pull/53) ([andrewmcodes](https://github.com/andrewmcodes))
- Scoped Stimulus Reflex controllers [\#43](https://github.com/hopsoft/stimulus_reflex/pull/43) ([leastbad](https://github.com/leastbad))

**Closed issues:**

- Install StandardJS linter [\#40](https://github.com/hopsoft/stimulus_reflex/issues/40)

## [v2.0.2](https://github.com/hopsoft/stimulus_reflex/tree/v2.0.2) (2019-09-30)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.0.1...v2.0.2)

**Implemented enhancements:**

- Add support to configure room via register option [\#52](https://github.com/hopsoft/stimulus_reflex/pull/52) ([hopsoft](https://github.com/hopsoft))
- Move gitbook files to docs [\#49](https://github.com/hopsoft/stimulus_reflex/pull/49) ([hopsoft](https://github.com/hopsoft))

**Closed issues:**

- Formatting issues on README [\#48](https://github.com/hopsoft/stimulus_reflex/issues/48)

## [v2.0.1](https://github.com/hopsoft/stimulus_reflex/tree/v2.0.1) (2019-09-28)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v2.0.0...v2.0.1)

**Implemented enhancements:**

- Provide before/after callbacks for calls delegated to server side Stimulus controllers [\#4](https://github.com/hopsoft/stimulus_reflex/issues/4)
- Updated Minimal Javascript Example in README.md [\#47](https://github.com/hopsoft/stimulus_reflex/pull/47) ([kobaltz](https://github.com/kobaltz))
- Setup StimulusReflex controller callbacks [\#45](https://github.com/hopsoft/stimulus_reflex/pull/45) ([hopsoft](https://github.com/hopsoft))
- add .vscode directory to .gitignore [\#42](https://github.com/hopsoft/stimulus_reflex/pull/42) ([andrewmcodes](https://github.com/andrewmcodes))
- Allow override of default controller [\#37](https://github.com/hopsoft/stimulus_reflex/pull/37) ([hopsoft](https://github.com/hopsoft))
- update the name of the actions per feedback [\#36](https://github.com/hopsoft/stimulus_reflex/pull/36) ([andrewmcodes](https://github.com/andrewmcodes))
- update github templates [\#35](https://github.com/hopsoft/stimulus_reflex/pull/35) ([andrewmcodes](https://github.com/andrewmcodes))
- Tighten up security of remote invocation [\#32](https://github.com/hopsoft/stimulus_reflex/pull/32) ([hopsoft](https://github.com/hopsoft))

**Fixed bugs:**

- Reflex is a reflex [\#38](https://github.com/hopsoft/stimulus_reflex/pull/38) ([leastbad](https://github.com/leastbad))

**Closed issues:**

- Add GH templates [\#30](https://github.com/hopsoft/stimulus_reflex/issues/30)

## [v2.0.0](https://github.com/hopsoft/stimulus_reflex/tree/v2.0.0) (2019-09-11)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v1.1.1...v2.0.0)

**Implemented enhancements:**

- update github action triggers [\#29](https://github.com/hopsoft/stimulus_reflex/pull/29) ([andrewmcodes](https://github.com/andrewmcodes))
- Add support for declarative stimulus/reflex behavior [\#28](https://github.com/hopsoft/stimulus_reflex/pull/28) ([hopsoft](https://github.com/hopsoft))

**Fixed bugs:**

- fix merge issue for GitHub actions [\#27](https://github.com/hopsoft/stimulus_reflex/pull/27) ([andrewmcodes](https://github.com/andrewmcodes))

## [v1.1.1](https://github.com/hopsoft/stimulus_reflex/tree/v1.1.1) (2019-09-09)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v1.1.0...v1.1.1)

## [v1.1.0](https://github.com/hopsoft/stimulus_reflex/tree/v1.1.0) (2019-09-09)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v1.0.2...v1.1.0)

**Implemented enhancements:**

- Implicitly send DOM attributes to reflex methods [\#21](https://github.com/hopsoft/stimulus_reflex/pull/21) ([hopsoft](https://github.com/hopsoft))
- Add Ruby magic comment [\#18](https://github.com/hopsoft/stimulus_reflex/pull/18) ([dixpac](https://github.com/dixpac))
- Add GitHub Actions for Linters [\#17](https://github.com/hopsoft/stimulus_reflex/pull/17) ([andrewmcodes](https://github.com/andrewmcodes))

**Fixed bugs:**

- Fix GitHub Actions [\#20](https://github.com/hopsoft/stimulus_reflex/pull/20) ([andrewmcodes](https://github.com/andrewmcodes))

## [v1.0.2](https://github.com/hopsoft/stimulus_reflex/tree/v1.0.2) (2019-08-17)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v1.0.1...v1.0.2)

**Implemented enhancements:**

- Small performance enhancements [\#16](https://github.com/hopsoft/stimulus_reflex/pull/16) ([hopsoft](https://github.com/hopsoft))

## [v1.0.1](https://github.com/hopsoft/stimulus_reflex/tree/v1.0.1) (2019-08-10)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v1.0.0...v1.0.1)

**Implemented enhancements:**

- Add support for rooms [\#11](https://github.com/hopsoft/stimulus_reflex/pull/11) ([hopsoft](https://github.com/hopsoft))

**Closed issues:**

- Trying to get this working in Rails 6 [\#8](https://github.com/hopsoft/stimulus_reflex/issues/8)

## [v1.0.0](https://github.com/hopsoft/stimulus_reflex/tree/v1.0.0) (2019-08-09)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.3.3...v1.0.0)

**Implemented enhancements:**

- Ruby function splat args return arity of -1 [\#9](https://github.com/hopsoft/stimulus_reflex/pull/9) ([leastbad](https://github.com/leastbad))

## [v0.3.3](https://github.com/hopsoft/stimulus_reflex/tree/v0.3.3) (2019-05-13)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.3.2...v0.3.3)

## [v0.3.2](https://github.com/hopsoft/stimulus_reflex/tree/v0.3.2) (2019-03-25)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.3.1...v0.3.2)

## [v0.3.1](https://github.com/hopsoft/stimulus_reflex/tree/v0.3.1) (2019-03-01)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.3.0...v0.3.1)

## [v0.3.0](https://github.com/hopsoft/stimulus_reflex/tree/v0.3.0) (2019-02-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.2.0...v0.3.0)

**Breaking changes:**

- Update naming conventions [\#7](https://github.com/hopsoft/stimulus_reflex/pull/7) ([hopsoft](https://github.com/hopsoft))

## [v0.2.0](https://github.com/hopsoft/stimulus_reflex/tree/v0.2.0) (2018-11-16)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.12...v0.2.0)

**Implemented enhancements:**

- Explicit opt-in for ActionCable connection [\#6](https://github.com/hopsoft/stimulus_reflex/pull/6) ([hopsoft](https://github.com/hopsoft))

## [v0.1.12](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.12) (2018-11-03)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.10...v0.1.12)

## [v0.1.10](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.10) (2018-10-26)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.9...v0.1.10)

## [v0.1.9](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.9) (2018-10-24)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.8...v0.1.9)

**Closed issues:**

- URL helpers generate the wrong paths when page is rendered [\#1](https://github.com/hopsoft/stimulus_reflex/issues/1)

## [v0.1.8](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.8) (2018-10-22)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.7...v0.1.8)

**Fixed bugs:**

- Update env so url helpers work [\#2](https://github.com/hopsoft/stimulus_reflex/pull/2) ([hopsoft](https://github.com/hopsoft))

## [v0.1.7](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.7) (2018-10-21)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.6...v0.1.7)

## [v0.1.6](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.6) (2018-10-21)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.5...v0.1.6)

## [v0.1.5](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.5) (2018-10-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.4...v0.1.5)

## [v0.1.4](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.4) (2018-10-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.3...v0.1.4)

## [v0.1.3](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.3) (2018-10-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.2...v0.1.3)

## [v0.1.2](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.2) (2018-10-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.1...v0.1.2)

## [v0.1.1](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.1) (2018-10-20)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/v0.1.0...v0.1.1)

## [v0.1.0](https://github.com/hopsoft/stimulus_reflex/tree/v0.1.0) (2018-10-14)

[Full Changelog](https://github.com/hopsoft/stimulus_reflex/compare/bbd0d068aa40abb7d9f13deb099645dae3d5b3ed...v0.1.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
