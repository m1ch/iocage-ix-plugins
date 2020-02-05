# iocage-ix-plugins
Official iXsystems iocage plugins for [FreeNAS](http://www.freenas.org), [TrueOS](https://www.trueos.org) and [FreeBSD](http://www.freebsd.org)

Plugin Json files are added to this repo, along with a respective icon in icons/

When a plugin is made 'official' it should be added to the INDEX json and
it will appear in iocage's plugin listing

# Create a plugin
[FreeNAS-Docu: create a plugin](https://www.ixsystems.com/documentation/freenas/11.3-RELEASE/plugins.html#create-a-plugin)

# Installing Plugins

## Using Local File
```
iocage fetch -P /the/path/to/jenkins.json ip4_addr="re0|192.168.0.100" -n jenkins
```

## Pulling from Internet
```
iocage fetch --plugins --name "jenkins" ip4_addr="igb0|192.168.0.91"
```
