# Forked from 
(https://github.com/firstlutfi/data_magic?ref=https://githubhelp.com) because of Faker updates and Data Magic not being maintained.  Forked to keep accessibility.

## How to Use

Update your Gemfile to

````ruby
gem 'centric_data_magic'
````
Then run 
````ruby
bundle install
````
Any other configuration is exactly same as the original gem.

NOTE:
If you have previously used older version of Faker, I suggest you to install [rubocop-faker](https://github.com/koic/rubocop-faker) to automatically update from positional arguments to named arguments.

## New & Updated Generator

Here is a list of the new and updated methods:

| new methods added | updated methods | replaced methods |
| --- | --- | --- |
| color_hex | job_title<sup>1</sup> | title |
| color_name | 
| number(digits=5, leading_zero=true) |
| decimal(before_decimal=5, after_decimal=3) |
| merge(separator='_', [first_name, city, number(digits=3)]) |
| date_between(from='01/01/2021', to='31/01/2021', format='%d/%m/%Y') |

<sup>1</sup> In newer version of Faker, Faker::Name.title is changed to Faker::Job.title

## Copyright

Copyright (c) 2012-2021 [Jeffrey S. Morgan](https://github.com/cheezy/data_magic). See LICENSE for details.
