# Surya

## Hacking

### Cyber

  - python3 code for openAI API call
    ```python
      def PrintVowels(s):
      d={}
      v=['a','e','i','o','u']
      for char in s:
          if char in v:
              if char in d.keys():
                  d[char]=d[char]+1
              else:
                  d[char]=1
      for k,v in sorted(d.items()):
          print("{} alphabets occur for {}".format(k,v))

      s=input("Enter the sentence:")
      PrintVowels(s)
    ```

    ```bash
      sudo apt-get install python3-openAI

1. kali linux download from [kali.org](https://kali.org)
2. vbox
