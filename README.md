
import os,time,platform
os.system('clear')
print('[•] Checking Updates...')

print('<------------------------------------>')

print(f'{red}[•]Checking Your Phone Version....!! ')
green = ('\033[1;32m')
white = ('\033[1;37m')
red = ('\033[1;31m')
blue= ('\033[1;39m')
yellow=('\033[1;38m')

print('<------------------------------------>')

print(f'{red}[•]Hello....!')

green = ('\033[1;32m')
white = ('\033[1;37m')
red = ('\033[1;31m')
yellow=('\033[1;38m')

print(f'{white}[•]<------------------------------------√')


name=input(f'{yellow}[•] what is your name{green}:')

print(f'{red}[•] Your name is  '   +      name : )
green = ('\033[1;32m')
white = ('\033[1;37m')
red = ('\033[1;31m')
blue= ('\033[1;39m')
yellow=('\033[1;38m')

name=input(f'{white}[•] what is your region (or) country : ')


print(f'{red}[•]Your region (or) country is  '   +    name : )

print('<------------------------------------>')

bit = platform.architecture()[0]
if bit=='64bit':
    print(f'{red}[•] Join My Facebook Account {red}')

os.system('xdg-open https://www.facebook.com/AungZinMin.2006//')

