## nonnull
[![Build Status](https://travis-ci.com/pine/nonnull.svg?branch=master)](https://travis-ci.com/pine/nonnull)
[![Download](https://api.bintray.com/packages/pinemz/maven/nonnull/images/download.svg)](https://bintray.com/pinemz/maven/nonnull)

:police_car: Simple JSR-305 nonnull annotations

## Requirements
- Java 8 or later

## Getting started
The library is published to jcenter.

```gradle
repositories {
    jcenter()
}

depepdencies {
    implementation "moe.pine:nonnull:$latest_version"
}
```

## Annotations
- NonNull
- NonNullApi
- NonNullFields
- Nullable

## Development
### Test

```
$ ./gradlew clean check
```

### Upload Maven Central

```
$ ./gradlew clean publish
```

## License
Unlicense
