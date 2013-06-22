# Description

Installs [avahi](http://avahi.org/) the zeroconf software.

# Usage

Include `avahi::default` recipe in the `run_list`.

To disable the avahi-daemon set the attribute like so:

```
  default['avahi']['disable-service'] = true
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## To Do

* Ensure support on other platforms (RHEL/Arch).
