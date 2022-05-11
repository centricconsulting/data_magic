# Pre-Req 
- have account at Rubygems 

# Build 
- change [centric_data_magic.gemspec](centric_data_magic.gemspec) information as needed 
- change [lib/data_magic/version.rb](lib/data_magic/version.rb) version 
- run `gem build centric_data_magic` to build the new gem should get output like
```bash 
  Successfully built RubyGem
  Name: centric_data_magic
  Version: 1.2.2
  File: centric_data_magic-1.2.2.gem
```
- make note of the filename 

# Push 
- Run `gem push centric_data_magic-1.2.2.gem` using filename from above 