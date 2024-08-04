# Ruby syntax

## puts - 用來顯示任何東西

```ruby
foo = "Hello World!"
puts foo # Hello World!
```
## Array

### size - 顯示陣列大小

```ruby
foo = ["one", 2.0, 3]
puts foo.size # 3
```

### insepect - 轉換物件為人看得懂的字串

```ruby
foo = ["one", 2.0, 3]
puts foo.inspect # ["one", 2.0, 3]
```

### 流程控制if else

```ruby
foo = 100

if foo > 100
  puts "big"
elsif foo == 100
  puts "medium"
else
  puts "small"
end
# medium
```