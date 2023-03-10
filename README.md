# SkipList-based Priority Queue
SLPQ is a concurrent priority queue based on skiplists that is (almost) entirely generated by ChatGPT. I needed one for a project of mine and thought, given my sheer laziness and unwillingness to learn and write one myself, it would be a great opportunity to test out ChatGPT.

## Features
- Templated Key/Value priority queue
- Uses skiplists for faster insertion/deletion
- A C++ header only implementation
- Thread safe
- Fine grained mutex locking, on a per skip list element basis. Although in the beginning I wanted a lock-free version, ChatGPT could not get a lock-free implementation that was actually thread safe, no matter how much I tried.

## License
I asked ChatGPT if code generated by it had a license. Its answer was the following:
```
As a language model created by OpenAI, I do not have any license or intellectual property rights over the code I generate. You are free to use, modify, and distribute the code as you wish, subject to any legal restrictions or applicable open-source licenses. If you're going to post it on Github, it's a good idea to include a license with the code so others know what they can and cannot do with it.
```
So this code is licensed under the MIT license.