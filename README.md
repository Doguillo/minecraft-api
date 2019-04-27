# minecraft-api [![](https://jitpack.io/v/OvercastNetwork/minecraft-api.svg)](https://jitpack.io/#OvercastNetwork/minecraft-api)

Shared interfaces for the [SportBukkit](https://github.com/OvercastNetwork/SportBukkit) and [BungeeCord](https://github.com/OvercastNetwork/BungeeCord) (OCN fork) APIs

These interfaces can be used to write hybrid code that works with both APIs.
Currently, the following things are implemented, roughly speaking:

  * Plugin interface with lifecycle methods
  * Plugin metadata and lookup
  * Plugin configuration
  * Loggers
  * Online player list/search
  * Getting player name and locale
  * Sending component messages to players/console
  * Very basic permission checking
  * Event listener registration

Possible future additions:

  * Full event system
  * Task scheduler
  * Plugin channels
  * Server configuration (name, port, etc)
  * Commands
  * Scoreboard
  * Tab list

```xml
  <repository>
      <id>jitpack.io</id>
      <url>https://jitpack.io</url>
  </repository>
```

```xml
<dependency>
    <groupId>com.github.OvercastNetwork</groupId>
    <artifactId>minecraft-api</artifactId>
    <version>master-SNAPSHOT</version>
</dependency>
```
