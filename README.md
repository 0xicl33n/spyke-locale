
1) Create a new file in the `locale` folder called ` profile.lang.yml`, an example would be `profile.jp.yml`
2) Copy the contents of `profile.en.yml` to your new file
3) Fill it like this:
3) **Do not change my keys**, the keys are like `profile_help:`. Just replace the english with your text

This format is called YAML. I highly recommend picking up a text editor that preserves my tabs and spacing. Notepad++ is good enough, if youre that invested in doing this of course. 


```yaml
jp:
  example_1: your shit goes here
  
  example_multiline: |
  
    if it is multiline do this
    the | is very important if youre doing multiple lines, be sure and match my tabs
    
  example_2: you should be able to understand how this works
```


To submit your translation, make a pull request or upload your file to pastebin and ping me on discord
