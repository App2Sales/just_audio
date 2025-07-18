## 0.4.16

* Fix play interrupted by load.

## 0.4.15

* Support errorCode, errorMessage.

## 0.4.14

* Add setWebSinkId (@dganzella).

## 0.4.13

* Fix `dart2js`/`dart2wasm` compile error with Flutter 3.26.0 (@SleepySquash).

## 0.4.12

* Bump package:web version to `>=0.5.1 <2.0.0` (@ali2236)

## 0.4.11

* Bump package:web upper bound to <0.6.0
* Add AudioPlayer.setWebCrossOrigin for CORS on web (@danielwinkler).

## 0.4.10

* Migrate to package:web.

## 0.4.9

* Fix bug to ensure play exceptions pass through (@idy).

## 0.4.8

* Update minimum flutter version to 3.0.

## 0.4.7

* Fix bug handling simultaneous play requests.

## 0.4.6

* Fix bug playing quickly after load.

## 0.4.5

* Fix interrupted play request bug.

## 0.4.4

* Implement disposeAllPlayers.

## 0.4.3

* Fix bug where setSpeed is forgotten after load().

## 0.4.2

* Fix bug loading audio after concat delete/insert.

## 0.4.1

* Remember position after stopping.

## 0.4.0

* Upgrade to platform interface 4.0.0

## 0.3.2

* Upgrade to platform interface 3.1.0

## 0.3.1

* Propagate play() exceptions (@twogood).

## 0.3.0

* Null safety.

## 0.2.3

* Fix bug when modifying playlists (insert/move).

## 0.2.2

* Fix bug with empty playlist.
* Fix bug when modifying playlists.

## 0.2.1

* Fix bug with play before load.

## 0.2.0

* Support setShuffleOrder.

## 0.1.1

* Support initialPosition/initialIndex parameters to load.
* Remove `print` statements (@creativecreatorormaybenot).

## 0.1.0

* Update to use platform interface 1.1.0.

## 0.0.1

* Migrated to the federated plugin model.
