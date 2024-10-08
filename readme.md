# {{PROBLEM}} Class Design Recipe

As a user
So that I can keep track of my music listening
I want to add tracks I've listened to and see a list of them.


## 1. Describe the Problem

the user would like to track what they've listened to and see a list of everything

## 2. Design the Class Interface

```python
# EXAMPLE
class my_playlist():
    def __init__(self):
        #playlist = store a playlist
    
    def add_to_playlist(self, music):
        #takes argument and adds it to the list

    def list_playlist(self):
        #returns a list of the music on her list
``` 


```python
def test_for_my_playlist_is_init():

    #test if class is an instance


def test_if_add_to_playlist():

    #call add to playlist
    #then checks if the playlist has been updated


def test_return_playlist():
    #test to see if we can return the updated list 
```