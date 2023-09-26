# GitHub Docs Example

## Writing Good Documentation

### Step 1 - Using Codeblocks.

Codeblocks in markdown make it very easy for **tech** people to _copy_, _paste_, _share_ code.

A good __Cloud Engineer__ uses _**Codeblocks**_ whenever possible.

Because it allows others to copy and paste their code to replicate or ***research issues***.

in order to create codeblocks in markdown, you need to use three backticks (right above the tab key)

- example using codeblocks with with single quotations is incorrect (')

'''
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end
'''


* example using codeblocks with backticks which is correct (`)

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end
```

+ You should attempt to apply syntax highlighting to your codeblocks

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
# Test the factorial function
puts "Factorial of 5 is #{factorial(5)}"
end
```

+format to add image to you GFM by using ![]()

![pictorial summary of devops tools](https://github.com/bta001/GitHub-docs-example/assets/125939272/3a682b4a-8823-4eda-bd0a-226f3da24782)

- to resize image
<img width="200px" src="https://github.com/bta001/GitHub-docs-example/assets/125939272/3a682b4a-8823-4eda-bd0a-226f3da24782" />


- good cloud engineers use codeblocks for both code and errors that appear in the console.

> here is an example for using a codeblock for an error that appears in bash.

```bash
# Create a simple Ruby function that raises an error
def divide_by_zero
  5 / 0
end

# Call the function, which will raise a ZeroDivisionError
begin
  divide_by_zero
rescue ZeroDivisionError => e
  puts "An error occurred: #{e.message}"
end
```

## Step 3 - Use Github Flavored Markdown Task list

Github extends Markdown to have a list where you can check off items <sup> [3] </sup>

- [x] Finish step 1
- [ ] Finish step 2
- [x] Finish step 3
- [ ] Finish step 4

## Step 4 - Use emojis (optional)
Github Flavoured Markdowns (GFM) supports emojis shortcodes
Here are some examples

| Name  | Shortcode | Emoji |
| Cloud  | ':cloud:' | :cloud: |

| Name  | Shortcode | Emoji|
| ------------- | ------------- | ------------- |
| Cloud  | `:cloud:` | :cloud: |



## References 
1. [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images) <sup> [1] </sup>
1. [GFM Emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) <sup> [2] </sup>
1. [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup> [3] </sup>
1. [Writing on GitHub](https://docs.github.com/en/get-started/writing-on-github)
