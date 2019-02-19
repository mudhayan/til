# 2019-2-18

Getter Methods: return the variable

Seter Methods: set the variable 

```Ruby

## method example
def first_name=(input_name)
  @first_name = input_name
 end
end

## idiomatic Ruby example to set a new variable
employee.first_name = Bob
```

Instances in Ruby: 


String interpolation: is the process of evaluating a string literal containing one or more placeholders, yielding a result in which the placeholders are replaced with their corresponding values. You can use this to build a sentence (as opposed to concatenation). 

Example in Ruby:
```Ruby
employee1 = ["Majora", "Carter", 90000, true]
puts "#{employee1[0]} #{employee1[1]} makes #{employee1[2]} a year." 
```

This is how to create an SSH key and add it to GitHub: 

1. Create a public and private ssh key in `~/.ssh` by running: `ssh-keygen -t rsa -b 4096 -C "github_email_address"`
2. Run the following and verify that you receive "Agent PID ###": `eval "$(ssh-agent -s)"`
3. Add the identiy to your keychain by runing: `ssh-add ~/.ssh/name_of_your_private_key`
4. Add the public key to your clipboard by running: `pbcopy < ~/.ssh/id_rsa.pub`
5. Github > Settings > SSH and GPG Keys > New SSH Key > paste your key the in Key Field and add Title to identify device (i.e. Personal Computer, Work Computer, etc.) > Add SSH key

Sublime Shortcuts:

1. Run code in sublime `cmd + b`
2. Create multiple cursors `cmd + d`

