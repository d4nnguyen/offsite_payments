# THIS IS A CUSTOM GEM USED FOR VBA-TICKET A PROJECT OF SAIGON SILICON STRAITS

# Offsite Payments
[![Build Status](https://travis-ci.org/activemerchant/offsite_payments.svg?branch=master)](https://travis-ci.org/activemerchant/offsite_payments)
[![Code Climate](https://codeclimate.com/github/activemerchant/offsite_payments/badges/gpa.svg)](https://codeclimate.com/github/activemerchant/offsite_payments)

Offsite Payments is an extraction from the ecommerce system [Shopify](http://www.shopify.com). Shopify's requirements for a simple and unified API to handle dozens of different offsite payment pages (often called hosted payment pages) with very different exposed APIs was the chief principle in designing the library.

It was developed for usage in Ruby on Rails web applications and integrates seamlessly
as a Rails plugin. It should also work as a stand alone Ruby library, but much of the benefit is in the ActionView helpers which are Rails-specific.

Offsite Payments has been in production use (originally as part of the [ActiveMerchant](https://github.com/activemerchant/active_merchant) project) since June 2006. It is maintained by the [Shopify](http://www.shopify.com) team, with much help from an ever-growing set of contributors.

## Installation

### From Git

From git:

    git clone https://github.com/d4nnguyen/offsite_payments.git

### From RubyGems

Installation from RubyGems:

    gem install offsite_payments, git: 'https://github.com/d4nnguyen/offsite_payments.git'

Or, if you're using Bundler, just add the following to your Gemfile:

    gem 'offsite_payments', git: 'https://github.com/d4nnguyen/offsite_payments.git'

[API documentation](http://www.rubydoc.info/github/activemerchant/offsite_payments/master).

## Misc.

- This library is MIT licensed.
- We will gladly accept contributions. See **CONTRIBUTING.md** for more information.
