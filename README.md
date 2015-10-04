# RelativeTime

A tiny Javascript library for calculating relative time in Qt Quick.

## How do I use it ?

First install the library via qpm:

```
qpm install com.cutehacks.relativetime
```

You can now start using it in your .qml files:

```
import com.cutehacks.relativetime 1.0 as RelativeTime

...
  Text {
    text: RelativeTime.timeSince(new Date(object.metadata.created)) + " ago";
  }

```

## Functions

* `timeSince(date)`
* `timeLeft(date)`
* `timeFraction(date, total)`
* `timeSinceObject(date)`
* `timeLeftObject(date)`
* `timeObject(seconds)`
* `timeInterval(seconds)`

## What license is it released under?

[MIT][license]
