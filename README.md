### Howitzer
---
https://github.com/strongqa/howitzer

```
gem install howitzer
howitzer new <PROJECT NAME> --cucumber
howitzer new <PROJECT NAME> --rspec
howitzer new <PROJECT NAME> --turnip

rake -T

bundle update howitzer
bundle exec howitzer update
```

```ruby
bank_account_add.feature
bank_account_delete.feature
user_signup.feature
user_signup_invited.feature
user_login.feature

Given the user navigation to the home page
And enters "username" in the "username" field
And enters "password" in the "password" filed
When the user clicks on the login button
Then the user is logged in

Given the user is logged in
And is on the home page

Then /^the users? should receive an email$/ do |item_count|
  item_count.to_i.times {...}
end

Then /^the users? shouild receive an email$/ do
end

And /^once the files? (?:have|has) finished processing$/ do
end

When /^(?:I|they) create a profile$/ do
end
```

```
```
