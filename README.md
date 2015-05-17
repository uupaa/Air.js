# Air.js [![Build Status](https://travis-ci.org/uupaa/Air.js.png)](http://travis-ci.org/uupaa/Air.js)

[![npm](https://nodei.co/npm/uupaa.air.js.png?downloads=true&stars=true)](https://nodei.co/npm/uupaa.air.js/)

# Air.js

## Document

- [Air.js wiki](https://github.com/uupaa/Air.js/wiki/Air)
- [WebModule](https://github.com/uupaa/WebModule)
    - [Slide](http://uupaa.github.io/Slide/slide/WebModule/index.html)
    - [Development](https://github.com/uupaa/WebModule/wiki/Development)

## Run on

### Browser and node-webkit

```js
<script src="lib/Air.js"></script>
```


| Device                   | CHARS | cache   | BS | ms   | fps  | note |
|--------------------------|-------|---------|----|------|------|------|
| ZenFone2 5.0.0 44 dev    | 1000  | false   | 8  | 55.1 | 8.9  |      |
| ZenFone2 5.0.0 44 dev    | 1000  | false   | 16 | 54.0 | 8.7  |      |
| ZenFone2 5.0.0 44 dev    | 1000  | false   | 32 | 54.5 | 8.0  |      |
| ZenFone2 5.0.0 44 dev    | 1000  | false   | 64 | 55.2 | 6.8  |      |
| ZenFone2 5.0.0 44 dev    | 1000  |   87 ms | 8  | 65.2 | 9.3  |      |
| ZenFone2 5.0.0 44 dev    | 1000  |   92 ms | 16 | 66.0 | 9.4  |      |
| ZenFone2 5.0.0 44 dev    | 1000  |  146 ms | 32 | 62.2 | 9.4  |      |
| ZenFone2 5.0.0 44 dev    | 1000  |  397 ms | 64 | 69.3 | 7.4  |      |

| Device                   | CHARS | cache   | BS | ms   | fps  | note |
|--------------------------|-------|---------|----|------|------|------|
| ZenFone2 5.0.0 42.0.2311 | 1000  | false   | 8  | 17.4 | 27.5 |      |
| ZenFone2 5.0.0 42.0.2311 | 1000  | false   | 16 | 51.0 | 18.0 |      |
| ZenFone2 5.0.0 42.0.2311 | 1000  | false   | 32 | 51.1 | 18.1 |      |
| ZenFone2 5.0.0 42.0.2311 | 1000  | false   | 64 | 50.1 | 18.5 |      |

| Device                   | CHARS | cache   | BS | ms   | fps  | note |
|--------------------------|-------|---------|----|------|------|------|
| ZenFone2 5.0.0 42.0.2311 | 1000  |   87 ms | 8  | 16.1 | 28.9 |      |
| ZenFone2 5.0.0 42.0.2311 | 1000  |  179 ms | 16 | 16.6 | 28.2 |      |
| ZenFone2 5.0.0 42.0.2311 | 1000  |  270 ms | 32 | 16.6 | 29.1 |      |
| ZenFone2 5.0.0 42.0.2311 | 1000  |  699 ms | 64 | 16.2 | 28.7 |      |

| Device                   | CHARS | cache   | BS | ms   | fps  | note |
|--------------------------|-------|---------|----|------|------|------|
| ZenFone2 5.0.0 40 custom | 1000  | false   | 8  | 12.2 | 28.6 |      |
| ZenFone2 5.0.0 40 custom | 1000  | false   | 16 | 45.5 | 18.3 | 描画異常 |
| ZenFone2 5.0.0 40 custom | 1000  | false   | 32 | 45.6 | 19.0 | 描画異常 |
| ZenFone2 5.0.0 40 custom | 1000  | false   | 64 | 47.5 | 19.4 | 描画異常 |
| ZenFone2 5.0.0 40 custom | 1000  |   78 ms | 8  | 14.2 | 28.9 |      |
| ZenFone2 5.0.0 40 custom | 1000  |  132 ms | 16 | 14.5 | 28.9 |      |
| ZenFone2 5.0.0 40 custom | 1000  |  207 ms | 32 | 15.0 | 28.9 |      |
| ZenFone2 5.0.0 40 custom | 1000  |  605 ms | 64 | 14.4 | 29.6 |      |

| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| Nexus7(2012) 5.0.2 | 1000  | false   | 8  | 24.4 | 23.2 |      |
| Nexus7(2012) 5.0.2 | 1000  | false   | 16 | 68.3 | 13.8 |      |
| Nexus7(2012) 5.0.2 | 1000  | false   | 32 | 71.2 | 13.3 |      |
| Nexus7(2012) 5.0.2 | 1000  | false   | 64 | 70.6 | 13.5 |      |

| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| Nexus7(2012) 5.0.2 | 1000  |  165 ms | 8  | 26.8 | 22.0 |      |
| Nexus7(2012) 5.0.2 | 1000  |  267 ms | 16 | 26.6 | 22.3 |      |
| Nexus7(2012) 5.0.2 | 1000  |  379 ms | 32 | 26.3 | 22.4 |      |
| Nexus7(2012) 5.0.2 | 1000  | 1238 ms | 64 | 28.9 | 21.3 |      |

| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| NW-Z1000 4.0.2     | 1000  | false   | 8  | 22.1 | 22.8 |      |
| NW-Z1000 4.0.2     | 1000  | false   | 16 | 71.8 | 12.6 |      |
| NW-Z1000 4.0.2     | 1000  | false   | 32 | 72.4 | 12.6 |      |
| NW-Z1000 4.0.2     | 1000  | false   | 64 | 75.3 |  9.1 |      |

| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| NW-Z1000 4.0.2     | 1000  |  111 ms | 8  | 21.6 | 21.9 |      |
| NW-Z1000 4.0.2     | 1000  |  229 ms | 16 | 21.2 | 22.4 |      |
| NW-Z1000 4.0.2     | 1000  |  684 ms | 32 | 20.8 | 22.7 |      |
| NW-Z1000 4.0.2     | 1000  | 2373 ms | 64 | 21.2 | 20.5 |      |


| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| Nexus 5 5.0.1      | 1000  | false   |  8 | 34.9 | 14.9 |      |
| Nexus 5 5.0.1      | 1000  | false   | 16 | 88.0 | 10.5 |      |
| Nexus 5 5.0.1      | 1000  | false   | 32 | 95.2 |  9.0 |      |
| Nexus 5 5.0.1      | 1000  | false   | 64 | 98.2 |  8.7 |      |

| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| Nexus 5 5.0.1      | 1000  |   78 ms |  8 | 23.7 | 23.8 |      |
| Nexus 5 5.0.1      | 1000  |  144 ms | 16 | 22.7 | 24.3 |      |
| Nexus 5 5.0.1      | 1000  |  197 ms | 32 | 25.3 | 21.3 |      |
| Nexus 5 5.0.1      | 1000  |  520 ms | 64 | 20.6 | 26.5 |      |


| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| Nexus 5 5.0.1      | 500   | false   |  8 | 13.1 | 41.4 |      |
| Nexus 5 5.0.1      | 500   | false   | 16 | 42.6 | 20.2 |      |
| Nexus 5 5.0.1      | 500   | false   | 32 | 40.7 | 21.3 |      |
| Nexus 5 5.0.1      | 500   | false   | 64 | 42.2 | 20.7 |      |

| Device             | CHARS | cache   | BS | ms   | fps  | note |
|--------------------|-------|---------|----|------|------|------|
| Nexus 5 5.0.1      | 500   |   57 ms |  8 | 10.3 | 44.1 |      |
| Nexus 5 5.0.1      | 500   |  161 ms | 16 | 12.0 | 44.7 |      |
| Nexus 5 5.0.1      | 500   |  185 ms | 32 | 11.2 | 45.2 |      |
| Nexus 5 5.0.1      | 500   |  934 ms | 64 | 16.7 | 32.8 |      |



