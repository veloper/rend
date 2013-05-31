# Rend

Rend is an open source project aimed at porting over various PHP Zend Framework components into Ruby.

## Description
Rend is a meta-gem which currently includes (depends on) the following gems:

* `rend-core`
* `rend-acl` -- _[Zend_Acl](http://framework.zend.com/manual/1.12/en/zend.acl.html)_
* _Expect this list to grow..._


Each of these gems can be installed separately and actived in isolation with the gem command. This allows one to pick and choose which Rend components they would like to use in their projects or gems.

Conversely, one can simply include all available Rend components by installing this gem.

## Installation

Add this line to your application's Gemfile:

    gem 'rend'

... and then execute:

    $ bundle

Or install it manually using:

    $ gem install rend

## Usage

See the wiki, or individual gem projects, for information on how to use them.

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

#### Important Excerpt from the Zend's New-BSD License...
> Neither the name of Zend Technologies USA, Inc. nor the names of its
> contributors may be used to endorse or promote products derived from this
> software without specific prior written permission.

**TO BE CLEAR:** This project is in **no-way** associated with, or endorsed by, Zend Technologies USA, Inc. or any of its contributors.