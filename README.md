# Rend

Rend is an open source project aimed at porting over various PHP Zend Framework components into Ruby.

## Description
Rend is a meta-gem which currently includes (depends on) the following gems:

* [rend-core](https://github.com/veloper/rend-core)
* [rend-acl](https://github.com/veloper/rend-acl)
* _Expect this list to grow..._


Each of these gems can be installed separately and actived in isolation with the gem command. This allows one to pick and choose which Rend components they would like to use in their projects or gems.

Conversely, one can simply include all available Rend components by installing this gem.

## Installation

    $ gem install rend

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Licensing

* All ported Ruby code and assoicated 'Rend' gems are under a simple [New-BSD License](http://dan.doezema.com/licenses/new-bsd).
* Original PHP code is licensed under [Zend's New-BSD License](http://framework.zend.com/license/).
    * This license can be found in `./ZEND_FRAMEWORK_LICENSE.txt`

## Acknowledgements
* This project is **not** associated with, or endorsed by, Zend Technologies USA, Inc., nor any of its contributors.
* Rend's modular design was heavily influced by [RSpec](https://github.com/rspec/rspec) approach.