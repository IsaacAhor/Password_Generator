# [Project 1 (Python):](https://isaacahor.github.io/Porfolio/)
1. This is an automated uncrackable password generator 
2. Contains all alphanumeric characters and special characters
3. Maximum length of password is 12
4. The code generates a distinct password at each print

### import random
    <import random>
### gather all characters within peremeter
    <lower = 'abcdefghijklmnopqrstuvwxyz'>
    <upper = lower.upper()>
    <symbols = '!@#$%^&*()_+?><:;+='>
    <numbers = '1234567890'>
    <allchar = lower + upper + symbols + numbers>

### set password length
    <length = 12>

### loop through each character
    <password = ''>
    <for _ in range (length):>
          <password = ''.join([password, random.choice(allchar)])>
    <print(password)>

