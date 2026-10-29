# Legacy Launcher

This build was created from the source archive in this directory.

## References

- Source repository: https://github.com/Deluxeg4/legacylauncher.git
- Project website: https://llaun.ch/en

## License

See [LICENSE.txt](LICENSE.txt). The source archive's included notice describes
the source as being for reference and says it is “All rights reserved.” No
GPL-3.0 license grant is included in that archive, so this project does not
claim that the upstream source is GPL-3.0 licensed.

## Build

With Java 21 and Gradle installed, build the runnable bootstrap JAR with:

```sh
./gradlew :bootstrap:bootJar
```

The resulting JAR is written to `bootstrap/build/libs/`.
