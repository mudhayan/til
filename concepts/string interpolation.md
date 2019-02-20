# String Interpolation:

String interpolation is when you evaluate a string using placeholders. When evaluated, the placeholders will be replaced with values. You can use this to build a sentence (NLG) as opposed to concatenation.

Example in Ruby:
```Ruby
employee1 = ["Majora", "Carter", 90000, true]
puts "#{employee1[0]} #{employee1[1]} makes #{employee1[2]} a year."
```
