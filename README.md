class NihonTyper = {
joint = ''
typed_words = []
ru = 'ル'
characters_list  = raw_input("Type your character combination here.. ")
index = len(characters_list)
for item in characters_list:
 
    while item != " ":
        joint = joint + item
        break
    while item == " " or index == 1:

        typed_words.append(joint)
        joint = ""
        break
    index -= 1
   
for item in typed_words:
    while item == "ru":
        print(ru)
        break
print(len(characters_list))
print(typed_words)
print(joint)
 }
