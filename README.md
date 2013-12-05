earl
====

Probably the 10.000th grocery web app. But the others didn't cut it. Or I didn't find them.

Basic ideas:

* targeted at mobile devices (including my trusty nokia with OperMini. So JavaScript must not be mandatory)
* no accounts. Bit like doodle. Creating a list also creates its unique link. Share it. Or don't.
* one line text items only. No bullshit.
  * remember: clean out html
* on JavaScript enabled devices the items can be reordered
* enter-box on top. New items appear right bellow
* one item consists of
  * text
  * some kind of location (enter '@location' in text. Gets cut out and used in "tagcloud")
  * creation date (no due date. This is not a GTD thing)
  * (internaly) position for ordering
* things that can be done on an active item
  * click ok (or on mobile devices wipe to the right)
   * makes the item drop to the bottom of the list an being greyed out
   * items are permanently deleted an hour after being clicked
  * click on tag/location to filter by them (by the way. Do I need a full text search?)
  * some kind of edit. No clue how to that right now
* things that can be done on an inactive item
  * move back to active (how?)
  * nothing else
* keyboardbings. vi. Of course.
* tech
  * scala
  * play
  * scalaz if I feel funky

