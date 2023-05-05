### preparation
```ruby
  5.times do
    data = []
    (1..10).each do |index|
      data << { name: SecureRandom.hex(8), age: index }
    end

    User.insert_all(data)
  end
```
