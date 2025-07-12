# python34
Inner values
def greet(text):
    def inner(name):
        return f"{text},{name}!!!!!!"
    return inner
hi=greet('Hello')
print(hi('SIDDU'))
