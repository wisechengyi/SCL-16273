Show the scalafmt plugin can pick up the configuration from `<VCS root>/.scalafmt.conf`

1. In IntelliJ, install scalafmt plugin
2. File -> Open, select `<VCS root>/examples/`. NOTE: not `<VCS root>`.
3. Open `WelSpec.scala`
4. Code -> reformat with scalafmt. Nothing should change.
5. Change `maxColumn` in `<VCS root>/.scalafmt.conf` from 100 to 20
6. Repeat step 4, and `WelSpec.scala`'s width would be changed, showing that `<VCS root>/.scalafmt.conf` was respected.
