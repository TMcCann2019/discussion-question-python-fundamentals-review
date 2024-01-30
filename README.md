# Discussion Questions: Python Fundamentals Review

## Instructions

Take 30 minutes and answer the following questions together with your group.
Take turns playing around with the code provided in a Python shell or `ipdb`.

## Questions

1 . What does the below function return?

```python
def greet(name):
  print(f"Hello, {name}")

greet("Steven") #=> ?
```

"Hello Steven"
returns nothing

2 . What does this function return?

```python
def love_this_veggie(vegetable):
  if vegetable == "broccoli":
    return "Nah, thanks"
  else:
    return "I love it!"
```
If the vegetable is broccoli, it will return Nah, thanks. Otherwise it will return I love it

3 . How would you produce a new list all of the words that start with the letter "a" from the below list?

```python
fruit = ["apple", "pear", "face", "champagne", "palm tree", "aardvark", "pineapple"]

a_words = [word for word in fruit if word.startswith("a")]
```

4 . Write a function that takes in an argument of a sentence and returns the
number of words in the sentence

```python

def word_count(sentence):
  return len(sentence.split(" "))
  pass

word_count("Hi, isn't this a great and interesting sentence??")

 # => 8
```

5 . What will the following function return?

```python
def friendly_greeting(name=None):
  name = name or "friend"
  print(f"Hey there, {name}")
```

Will return an error since name = None and wont return anything as there is no return

6 . What will the following `print`?

```python
best_animal = "cat"
favorite_animal = best_animal
print(favorite_animal)
# => ?
```
"Cat"

7 . What will the following `print`?

```python
def my_favorite_animal():
  return "cat"


best_animal = my_favorite_animal

print(best_animal)
```
will print my_favorite_animal since best_animal is not equal to the function of my_favorite_animal

8 . What error, if any, will the following code raise?

```python
"Blink" + 182
```

Type Error since you cant concatenate a string with integers

9 . How would you `print` out any and all foods that are delicious?

```python
foods = {
  "pie": "delicious",
  "broccoli": "not delicious",
  "carrots": "not delicious",
  "apples": "delicious",
  "peanut butter": "delicious"
}
```

10 . Delete all elements of the `foods` dict that are _not_ delicious.

11 . What is the return value of this function?

```python
character_names = ["Daenerys Targaryen", "Jon Snow" ,"Arya Stark", "Tyrion Lannister", "Sansa Stark", "Cersei Lannister", "Margaery Tyrell"]

def downcase_all(list_of_strings):
  for one_string in list_of_strings:
    one_string.lower()
  
```
wont return anything as doesnt have an return function but if you do return one_string.lower() it will return everything lower cased

12 . Write a function that `print`s out a random Agent Cooper quote.

```python
cooper = {
    "name": "Dale Bartholomew Cooper",
    "co-workers": ["Diane", "Sheriff Harry S. Truman"],
    "favorite_drink": "Coffee",
    "quotes": ["Damn fine cup of coffee", "Diane...", "This must be where pies go when they die", "That's what you do in a town where a yellow light still means slow down, not go faster.", "Every day, once a day, give yourself a present", "I have no idea where this will lead us, but I have a definite feeling it will be a place both wonderful and strange."]
}
```
