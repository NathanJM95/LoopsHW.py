int_float_list = []
str_list = []

def list_maker(new_element):
    if new_element == isinstance(my_input, (int, float)):
        int_float_list.append(new_element)
    if new_element == isinstance(my_input, str):
        str_list.append(new_element)

my_input = ["Hello"]
list_maker(my_input)
my_input = 8.8
list_maker(my_input)
my_input = 6
list_maker(my_input)
my_input = ["Goodbye"]
list_maker(my_input)

print (int_float_list)
print (str_list)
