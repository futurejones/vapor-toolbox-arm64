<img 
	 src="https://github.com/futurejones/vapor-toolbox-arm64/blob/master/vapor_logo.png" 
	 height="176" 
	 alt="Vapor" 
    >

# A web framework for Swift
### Vapor Toolbox for Arm64 / AArch64
Vapor is a web framework for Swift. It provides a beautifully expressive and easy to use foundation for your next website, API, or cloud project.  

More info on the Vapor project available here:-
#### Github - [Vapor Source](https://github.com/vapor/vapor)  
#### Communty - [Vapor Developers](http://vapor.team/)
#### Docs - [Read the Docs](https://docs.vapor.codes/4.0/)

Vapor Toolbox for arm64 gives you quick and easy installation on Ubuntu/Debian Arm64 systems.  
Download direct from the [Release](#) page or use the [Swift-Arm](https://packagecloud.io/swift-arm/release) package repo.

### Installation
* Add the Swift-Arm package repo
```bash
curl -s https://packagecloud.io/install/repositories/swift-arm/release/script.deb.sh | sudo bash
```
* Install Swift and Vapor
```bash
sudo apt install swift-lang vapor
```
* Test Swift
```bash
~$ swift --version
Swift version 5.2.4 (swift-5.2.4-RELEASE)
Target: aarch64-unknown-linux-gnu

```
* Test Vapor
```bash
~$ vapor --help
Usage: vapor <command>

Vapor Toolbox (Server-side Swift web framework)

Commands:
       build Builds an app in the console.
       clean Cleans temporary files.
      heroku Commands for working with Heroku
         new Generates a new app.
         run Runs an app from the console.
  supervisor Commands for working with Supervisord
       xcode Opens an app in Xcode.

Use `vapor <command> [--help,-h]` for more information on a command.

```
