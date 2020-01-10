# Mattermost server nop plugin

This plugin has empty implementations of all the hooks available to
mattermost server plugins.

It is meant for testing purposes only.

Build your plugin:
```
make
```

This will produce a single plugin file (with support for multiple architectures) for upload to your Mattermost server:

```
dist/com.example.my-plugin.tar.gz
```

The tools package generates an empty implementation of defined hooks. To run the generator,
after updating the mattermost server dependency, run:
```
make generate
```
