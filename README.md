# input-unified-pointers

[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

A unified input to use mouse and touch inputs as if they were the same. Essentially the mouse is another touch point.

## Usage

[![NPM](https://nodei.co/npm/input-unified-pointers.png)](https://nodei.co/npm/input-unified-pointers/)

All events are signals that broadcast x, y and id.

Each finger in touch and the mouse has a unique id.

* onPointerSelectSignal - Similar to a click or tap

* onPointerDownSignal - Similar to mouseDown or touchStart

* onPointerUpSignal - Similar to mouseUp or touchEnd

* onPointerMoveSignal - Similar to mouseMove or touchMove

* onPointerHoverSignal - Similar to mouseMove without a mouseDown or touchMove

* onPointerDragSignal - Similar to mouseMove with a mouseDown or touchMove

## License

MIT, see [LICENSE.md](http://github.com/bunnybones1/input-unified-pointers/blob/master/LICENSE.md) for details.
