# Changelog

# Unpublished

* `1051c3c` `2018-01-21` Add RC to readme 
* `fc71430` `2018-01-17` Handle all VDomModifier implicit conversions though the AsVDomModifier type class 
* `cc6bd29` `2018-01-17` Simplify node version declaration in travis 
* `1e15dc1` `2018-01-16` refactor code for storage handler factories 
* `ffc5813` `2018-01-16` add additional storage handler without storage events 
* `eb05898` `2018-01-16` Added return type and removed some warnings 
* `37840bd` `2018-01-16` Implement LocalStorage Handler which reacts on StorageEvent 
* `0546f88` `2018-01-17` Implement typed Elements (.asHtml, .asSvg) on Hooks 

# 1.0.0-RC2

* `2d676ee` `2018-01-16` Make hooks and emitterbuilder consistent, closes #152 
* `1419678` `2018-01-15` Fix #153 
* `11f32a0` `2018-01-12` Rename on{Pre,Post}patch to on{Pre,Post}Patch 
* `039e5d2` `2017-12-17` currentTarget/target syntax. 
* `a852822` `2018-01-11` Implement side effect to Sink conversion helper 
* `79f9727` `2018-01-11` Add unsafeOnNext on Sink 
* `94a4ee5` `2018-01-08` Update dependencies: monix, cats, cats-effect, snabbdom 
* `1e46c32` `2017-12-27` Managed subscriptions, closes #121. 
* `411c8e1` `2017-12-14` Extended styles for easy and composable CSS animations 
* `26c2e30` `2017-12-26` Fix for #137 
* `5ef03ac` `2017-12-16` Bug fix for the case of multiple child nodes when only one emits 
* `4a2f046` `2017-12-11` Add accumulated attribute support and make className accumulated by default. 
* `a73830e` `2017-12-14` Remove tags.all and styles.all dsl imports 
* `93dc12e` `2017-12-14` DOM DSL updates 
* `b55b20d` `2017-12-15` Use implicitly injected Scheduler in the library and inject the TrampolinedScheduler in tests where we want synchronous behaviour. 
* `50f99fc` `2017-12-15` Simplified tests 
* `d4cd913` `2017-12-15` Revert simple code move (makes diff easier to read) 
* `30e7be9` `2017-12-14` Fix compile warning 
* `d64b9ff` `2017-12-14` Updated monix dependency 
* `4ac65c8` `2017-12-13` Monix port 
* `ef06226` `2017-12-13` fix discarded non-unit value warning 
* `ccace54` `2017-12-13` remove HandlerFactories (fixes #128) 
* `fce4eb8` `2017-12-13` Fix cleanup of jsdom environment 
* `0e0e682` `2017-12-12` rename LifecycleHooks with on prefix 
* `5040e1a` `2017-12-12` Keep deprecated OutWatch.render to not break client code 
* `6eb9fa2` `2017-12-12` Rename render to be explicit (into/replace) 
* `d269bb5` `2017-12-12` Merge pull request #123 from mariusmuja/modifier-separation-refactor 
* `676d33a` `2017-12-12` IO.pure and some code moves 
* `e646989` `2017-12-11` make VTree apply work on VDomModifier_, handle IO only on IO[VTree] 
* `c902276` `2017-12-11` Refactored modifier separation to use a single pass. Re-organized creation of Snabdom structures in one place. Removed outwatch dependencies from the snabbdom package 
* `2af882b` `2017-12-10` Run child/children IO elements as late as possible (before passing to Snabbdom) 
* `e3b5d43` `2017-12-10` Some optimizations 
* `67d51e8` `2017-12-10` More efficient? Seq[IO[_]].sequence 
* `e24b313` `2017-12-11` unsafeRunSync childStream nodes once in VDomModifier IO 
* `22af7e1` `2017-12-11` fix multiple runs of IO in CompositeModifier 
* `c4acf11` `2017-12-11` fix multiple runs of IO when nesting VNodes 
* `541cdce` `2017-12-10` provide unique key in DomUtils 
* `0d65a0a` `2017-12-10` fix multiple runs of VDomModifier IO 
* `54847a5` `2017-12-09` refactor DomUtils extract of children 
* `c05aeb4` `2017-12-09` add TitledAttribute to distinguish EmptyAttribute 
* `ae47bab` `2017-12-08` VDomModifier_ tree structture comment 
* `300354a` `2017-12-06` Refactorings to the VDomModifier hierarchy. 
* `3cf80fb` `2017-12-06` Hook refactorings and optimizations 
* `a36bb06` `2017-12-05` Fixed issue with static nodes being destroyed/re-inserted on first child/children stream element. Minor refactorings. 
* `441298a` `2017-11-26` Implement custom snabbdom props module 
* `6744a8f` `2017-12-03` Merge pull request #114 from OutWatch/cornerman-patch-1 
* `875cca7` `2017-12-03` move TagsCompat to Tags trait 
* `6d31a29` `2017-12-03` Merge pull request #101 from fdietze/fix-source-maps 
* `3f5cd8e` `2017-11-23` Link source maps to raw.githubusercontent.com 
* `473d942` `2017-12-03` Update Scala versions to 2.11.12 and 2.12.4 
* `f98e73a` `2017-11-27` Ensure static vnodes have keys if child/children receivers exist 
* `d5c6499` `2017-11-26` Include all cases in extractChildren instead of generic case 
* `45bde1f` `2017-11-23` Preserve order of static, `child` and `children` VNode streams. Allow multiple `children` vnode streams in the same `VNode`. 
* `e5048ac` `2017-12-03` remove scalac option -Xcheckinit and update domtypes 
* `d62247a` `2017-11-29` Merge pull request #109 from cornerman/code-cleanup 
* `bc8e65f` `2017-11-29` Merge branch 'master' into code-cleanup 
* `a0037d6` `2017-11-29` Merge pull request #107 from cornerman/no-main 
* `c136522` `2017-11-29` remove unused imports and a warning 
* `f0d297d` `2017-11-29` disable scalaJSUseMainModuleInitializer option in build.sbt 
* `5c2a968` `2017-11-25` Merge pull request #62 from cornerman/scala-dom-types 
* `abf7ff5` `2017-11-25` make `for` not deprecated 
* `6d7833d` `2017-11-25` update domtypes 
* `802ca56` `2017-11-24` Added some backwards compatibility attributes/tag 
* `11bd82a` `2017-11-24` more compatability attributes 
* `de5edb2` `2017-11-24` fix custom prop function 
* `cf91cf0` `2017-11-24` fix boolean attribute encoder 
* `3f5b482` `2017-11-23` Some renames, simplified attribute encoder 
* `1423ade` `2017-11-24` rename DomTypes without Dom-prefix 
* `6966323` `2017-11-24` not stringify property values, can have type any 
* `4f1e526` `2017-11-23` Fix compilation error on 2.11. Ignore initEvent warnings 
* `24297a7` `2017-11-24` separate encoding for values of property and attribute 
* `3c27f25` `2017-11-23` Fix for boolean props 
* `32d52d3` `2017-11-23` handle boolean properties correctly 
* `9e281e6` `2017-11-19` expose DomWindowEvents and DomDocumentEvents for observable dom events 
* `555cf24` `2017-10-16` Use scala-dom-types 
* `64a6cb3` `2017-11-25` HandlerFactories should be functions 
* `f37529f` `2017-11-24` Merge pull request #100 from fdietze/readme-jitpack 
* `62a559a` `2017-11-24` Merge branch 'master' into readme-jitpack 
* `399c644` `2017-11-21` Build ChildStreamReceiver only for VNodeRender type class 
* `b951308` `2017-11-24` Add jitpack dependency to readme 
* `afd9db4` `2017-11-22` Scala 2.11 fix 
* `05288eb` `2017-11-22` Adding CompositeVDomModifier 
* `84b1037` `2017-11-22` Fix backwards compatibility broken in #91 
* `a68965b` `2017-11-21` Merge pull request #91 from mariusmuja/handler_refactor 
* `279704b` `2017-11-21` Minor changes 
* `669583c` `2017-11-21` PipeOps and HandlerOps as implicit classes 
* `d21fceb` `2017-11-20` HandlerOps with lens and imap 
* `4846f0f` `2017-11-20` Some Pipe/Handler renames, reorder PipeOps 
* `5e1ba29` `2017-11-20` Rename PipeOps 
* `6cb14cb` `2017-11-20` Handler with only one Type parameter 
* `565b318` `2017-11-15` Move transform... methods to HandlerOps trait 
* `2392bec` `2017-11-14` Mix in HandlerOps 
* `c7bbad7` `2017-11-14` Ups, forgot to add file 
* `7c58cb4` `2017-11-14` Refactorings 
* `ddc89b9` `2017-11-12` Deprecate Handlers.create...Handler. 
* `6c1de88` `2017-11-12` Handler/Sink refactor, added Pipe trait. 
* `2feffc3` `2017-11-11` Update plugins 
* `2590a15` `2017-11-11` Refactor EmitterBuilder 
* `79c5169` `2017-11-07` Update rxscala-js and cats version 
* `123e730` `2017-11-07` Refactorings, removes nested IO[] in the tests 
* `8c53e2a` `2017-11-06` Tag builders don't need to return IO[VTree] any more 
* `8b6a7da` `2017-11-06` Allow apply on VNode 
* `f7210de` `2017-11-03` Refactor ValueBuilder 
* `237ea0b` `2017-11-01` Mark some methods @inline 
* `a715ea7` `2017-11-01` Introduce stl as factory for StyleBuilder 
* `b374422` `2017-10-31` Added a test case 
* `228b4b8` `2017-10-31` Stay within IO monad 
* `e56cc68` `2017-10-31` Bug fix, make Sink.createHandler referential transparent 
* `5bd06a0` `2017-10-31` Fix tests under scala 2.11 
* `d9c2981` `2017-10-31` Small changes 
* `4fa8220` `2017-10-31` Referential transparent API refactorings, alternative to PR #68 
* `aee1669` `2017-10-30` Never hide IO Monad in API 
* `8dcf0b8` `2017-10-25` Update crossScalaVersions to 2.12.4 
* `6c9b309` `2017-10-24` Update to cats 1.0.0-MF and cats-effect 0.4 
* `513ca28` `2017-10-23` Update to Scala 2.12.4 
* `7aa6e74` `2017-10-22` Add some TODOs 
* `dcc8e71` `2017-10-22` Use Nil instead of List.empty 
* `68cae07` `2017-10-21` Update test dependencies 
* `b455d41` `2017-10-19` Address feedback 
* `aa35a6d` `2017-10-19` Add VNode#apply 
* `7678e9c` `2017-10-13` Update HTTP usage 
* `12d3854` `2017-10-13` Use new store 
* `9c944d5` `2017-10-07` New store implementation 
* `ac86403` `2017-10-07` Replace Promise with STRef 
* `fbb2846` `2017-10-06` Weird compiler bug 
* `24251eb` `2017-10-06` Refactor to referential transparent api 
* `07a0f2d` `2017-10-19` Add TL CoC 
* `d05a917` `2017-10-19` Update README.md 
* `104e907` `2017-10-02` add style builder 
* `1a7c0e2` `2017-10-01` handle boolean attributes with snabbdom 
* `2b29262` `2017-10-02` Form submit emits an Event. (Useful for preventDefault()) 
* `fcf7d72` `2017-09-29` enable some scalac options and fix warnings 
* `6acff94` `2017-09-28` Travis: Enable caching for yarn and sbt 
* `507a3c9` `2017-09-28` Use case classes instead of tuples for separation 
* `a68a9d4` `2017-09-28` Use collection.breakOut instead of .map( ... ).toJSArray 
* `d334b9f` `2017-09-24` Introduce Style Attribute 

# 0.11
