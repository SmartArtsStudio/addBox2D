![addbox2d logo color](https://cloud.githubusercontent.com/assets/8098454/12345206/c4156d7c-bb99-11e5-961a-69064c6aae31.png)

A professional, developer friendly, native JavaScript optimized Box2D and LiquidFun library.
Not an unreadable ASM.js result of c++ transpilation.

Whilst developed for [addPhysicsJS](https://github.com/SmartArtsStudio/addPhysicsJS) which adds "Code FREE JavaScript Box2D
to Flash IDE", addBox2D remains a stand alone developer freindly javascript port of Erin Catto's [Box2D](https://github.com/erincatto/Box2D).

Box2d modules fully documented with Erin Catto's original comments, LiquidFun's Particle module fully documented with the 
Google teams original comments for easier developer education and all round ENJOYABLE experience.

YUIdoc comments syntax and generated API website not only slash the learning curve, but to also contribute 'type' compatibility 
for [Google Closure Compiler](https://github.com/google/closure-compiler), which compiles source code into excellent JavaScript optimisations and deployment compression.

Light weight and optimized for web, containing all the Joints and functionality of Box2D v2.3.1. All prototype chain lookups 
slashed to minimum. 'Scope' and 'context' are managed by the call stack which is much faster than javascripts convenience methods .apply() and .call() which are not used anywhere. All classes are written in their own file (for enjoyable source code management)
and COMPATIBLE with Google Closure Compiler. Hundreds of the common practice goog.provides()/imports() eliminated by manually sequenced classes, which also eliminates the need to include Closure library's 'base.js'. All just unnecessary extra work for the browser and bloat for to download, eliminated.

Potentially replace LinkedList data structures c++ requires for memory management with more efficient LookupTable data
Structures. LookupTables are apparently more compatible with the JavaScript environment than they were with c++ environment.
