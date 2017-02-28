# FoodFunction.py
# A functional Subway Sandwhich
''' purpose of the function: make code more readable, reuse multiple times, write shorter code
'''

def add_and_cook():
    print('Select bread')
    print('Selct Cheese')
    print('Put it in the toaster')
    print('Take it out')
def make_chickensandwhich(ingredient):
    add_and_cook()
    chickensandwhich= 'a {} chicken sandwhich'.format(ingredient)
    return chickensandwhich
def make_sandwhich(ingredient):
    add_and_cook()
    turkeysandwhich = 'a tasty sandwhich'
    return turkeysandwhich
def fancy_chickensandwhich(*ingredients):
    add_and_cook()
    chickensandwhich = ' a fancy chicken sandwhich with {} ingredients'.format(len(ingredients))
    return chickensandwhich
# make some regular chicken sandwhich
    print(make_chickensandwhich('cheese'))
    print(make_chickensandwhich('sauce'))

# make a fancy chicken sandwhich
print(fancy_chickensandwhich('chicken','cheese','lettuce','tomato',' peppers'))
