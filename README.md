# CI628-PongServer
A simple server for multiplayer com.almasb.fxglgames.pong.

### Run pre-built binary

1. Go to [Releases](https://github.com/AlmasB/CI628-PongServer/releases)
2. Download and unzip `ci628server-win.zip` on a Windows machine.
3. In the unzipped directory, go to `bin` and run `Start-CI628server.bat`.

### Build

**You do not need to modify the server code, but if you wish to, please see below**

In [IntelliJ Community Edition](https://www.jetbrains.com/idea/):

1. File -> New -> Project from existing sources
2. Select Maven 
3. Run server from PongApp

Note: make sure that Project Structure -> Modules uses Java level 17.
