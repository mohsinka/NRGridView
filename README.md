#NRGridView

iOS 6.0 minimum. 32/64 bits compatible.

##License

Without any further information, all the sources provided here are under the MIT License quoted in NRGridView/LICENSE.

##What is NRGridView

NRGridView is a grid-view UI component (built as a static library) which has been developed by Louka Desroziers, for Novedia Regions.
How it works? Almost like UITableView works. You set a dataSource, and a delegate.. and you implement all @required methods.
It also has a 'layoutStyle'. It means you can use it as a vertical gridView, or horizontal grid-view!

![image](https://github.com/ldesroziers/NRGridView/blob/master/NRGridViewSampleApp/Screenshots/Vertical-Landscape.png?raw=true)
![image](https://github.com/ldesroziers/NRGridView/blob/master/NRGridViewSampleApp/Screenshots/Horizontal-Landscape.png?raw=true)

If you got any suggestions, or if you need more UITableView-like methods, do not hesitate to email me via github

##Latest Changelog

####Added

`- (void)reloadCellsAtIndexPaths:(NSArray *)indexPaths withCellAnimation:(NRGridViewCellAnimation)cellAnimation;`

`- (void)reloadSections:(NSIndexSet *)sections withCellAnimation:(NRGridViewCellAnimation)cellAnimation;`

`typedef enum{
`

`NRGridViewCellAnimationFade,`
`NRGridViewCellAnimationRight,`
`NRGridViewCellAnimationLeft,`
`NRGridViewCellAnimationTop,`
`NRGridViewCellAnimationBottom,`
`NRGridViewCellAnimationNone,`
`NRGridViewCellAnimationAutomatic,`
`} NRGridViewCellAnimation;`

`- (NSArray*)visibleCellsAtIndexPaths:(NSArray*)indexPaths;`

##Comments

Referencing this project in your AboutBox is appreciated.
Please tell me if you use this class so we can cross-reference our projects.

Enjoy, and share ;)