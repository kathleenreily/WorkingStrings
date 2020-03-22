# WorkingStrings
# working with strings

trees = ['leaves', 'trunk', 'branches']
first_word = trees[0] 
print("the first word are '{}.'".format(first_word))
# when called, this prints:
the first word are 'leaves.'

# lists and strings(using index)

list_2 = [114, 16, 'pavemment', 'colorado']
second_two = list_2[2:3]
print(second_two)
# when printed you see:
['pavemment']

# strings and conditional logic (using lists)
words = ['apples', 'pears', 'tomatoes', 'berries']
def fruits(color):
  for i in color:
    if color == 'red':
      return 'apple or tomato'
    elif color == 'blue':
      return 'berries'
    else:
      return 'pears'
fruits('red')
# when printed you see:
'apple or tomato'

# strings and for loops (using lists):

list_items = ['andrea', 'people', 'sasha', 'elephant']
def longest_word(list_of_words):
  words = 0
  for i in list_of_words:
    if len(i) > words:
      words = len(i)
  return words
longest_word(list_items)
# when printed you see:
8








