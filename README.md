# Setup
Navigate to ct-test-52 or ct-test-60 then `bundle install`

# Run

Start web process and cloudtaker daemon with:
```
foreman start
```

Launch console with `rails c` then:
```ruby
ExampleJob.perform_later('foo')
```
