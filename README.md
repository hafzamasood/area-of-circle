area-of-circle
==============

#!/usr/bin/python
pi = 3.14159265

choice = input('Enter Choice [1 or 2]:')
choice = int (choice)

if choice == 1:
  radius = input('Enter x:')
  area = ( radius ** 2 ) * pi
  print 'The Area is=', area

if choice == 2:
  side = input('Enter x:')
  area = side ** 2
  print 'The Area is=', area
