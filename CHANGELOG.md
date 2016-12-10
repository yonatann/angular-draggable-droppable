# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="0.2.0"></a>
# [0.2.0](https://github.com/mattlewis92/angular-draggable-droppable/compare/v0.1.1...v0.2.0) (2016-12-10)


### Bug Fixes

* completely remove applied styled after dragging ([3445337](https://github.com/mattlewis92/angular-draggable-droppable/commit/3445337))
* **draggable:** dont fire duplicate dragging events with the same coordinates ([222914b](https://github.com/mattlewis92/angular-draggable-droppable/commit/222914b)), closes [#6](https://github.com/mattlewis92/angular-draggable-droppable/issues/6)
* **draggable:** when dragging is disabled, no drag events should be emitted ([729f24e](https://github.com/mattlewis92/angular-draggable-droppable/commit/729f24e))
* **droppable:** only allow dropping of events when the cursor is inside ([652d632](https://github.com/mattlewis92/angular-draggable-droppable/commit/652d632)), closes [#5](https://github.com/mattlewis92/angular-draggable-droppable/issues/5)


### Features

* **draggable:** auto change the cursor to the move icon on hover ([50d1962](https://github.com/mattlewis92/angular-draggable-droppable/commit/50d1962)), closes [#9](https://github.com/mattlewis92/angular-draggable-droppable/issues/9)
* **snapGrid:** rename to dragSnapGrid ([a77d07a](https://github.com/mattlewis92/angular-draggable-droppable/commit/a77d07a)), closes [#7](https://github.com/mattlewis92/angular-draggable-droppable/issues/7)
* **validateDrag:** add the validate drag input ([9e5ac95](https://github.com/mattlewis92/angular-draggable-droppable/commit/9e5ac95)), closes [#8](https://github.com/mattlewis92/angular-draggable-droppable/issues/8)


### BREAKING CHANGES

* droppable: the drag enter, leave and drop events will not fire until cursor is inside the droppable element. This is to mimic how native drag and drop works
* snapGrid: The snapGrid input has been renamed to dragSnapGrid



<a name="0.1.1"></a>
## [0.1.1](https://github.com/mattlewis92/angular-draggable-droppable/compare/v0.1.0...v0.1.1) (2016-12-09)


### Bug Fixes

* **draggable:** disable pointer events on the element when dragging ([f29b424](https://github.com/mattlewis92/angular-draggable-droppable/commit/f29b424))



<a name="0.1.0"></a>
# 0.1.0 (2016-11-27)


### Bug Fixes

* **draggable:** dispose of observables when the component is destroyed ([710c7f7](https://github.com/mattlewis92/angular-draggable-droppable/commit/710c7f7))
* prevent the default move move interaction on dragging ([d2fdcde](https://github.com/mattlewis92/angular-draggable-droppable/commit/d2fdcde))


### Features

* **dragAxix:** allow the drag axis to be locked to just x and y ([38fd4b5](https://github.com/mattlewis92/angular-draggable-droppable/commit/38fd4b5)), closes [#2](https://github.com/mattlewis92/angular-draggable-droppable/issues/2)
* **draggable:** add mwlDraggable directive ([c6771eb](https://github.com/mattlewis92/angular-draggable-droppable/commit/c6771eb))
* **droppable:** add the mwlDroppable directive ([6016f12](https://github.com/mattlewis92/angular-draggable-droppable/commit/6016f12)), closes [#1](https://github.com/mattlewis92/angular-draggable-droppable/issues/1)
* **ghostDragEnabled:** add option to disable the ghost dragging effect ([709327c](https://github.com/mattlewis92/angular-draggable-droppable/commit/709327c)), closes [#3](https://github.com/mattlewis92/angular-draggable-droppable/issues/3)
* **snapGrid:** implement draggable snap grids ([16a3df8](https://github.com/mattlewis92/angular-draggable-droppable/commit/16a3df8)), closes [#4](https://github.com/mattlewis92/angular-draggable-droppable/issues/4)