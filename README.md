# Social Media Database

A C++ social media-like implementation, allowing users to create accounts, make posts, follow other users, react to messages, and view their feeds.

1. **Account Class (Account.hpp, Account.cpp):**
   - Represents user accounts with a username and password.
   - Users can create posts, view posts, follow other users, and update their posts.
   - Each account maintains a list of posts and accounts they are following.

2. **Post Class (Post.hpp, Post.cpp):**
   - Represents individual posts made by users.
   - Each post has a title, body, timestamp, and the username of the account that made the post.
   - Users can update their posts and view post details.

3. **General Class (General.hpp, General.cpp):**
   - Derived from the Post class, representing general posts.
   - Allows users to react to posts with different types of reactions (like, dislike, laugh, wow, sad, angry).
   - Provides functionality to display reactions to a post.

4. **LinkedList Class (LinkedList.hpp, LinkedList.cpp):**
   - Represents a linked list data structure used for managing lists of posts.
   - Provides functionality for insertion, removal, traversal, and sorting of elements in the list.

5. **Network Class (Network.hpp, Network.cpp):**
   - Manages a network of user accounts.
   - Allows adding, removing, and searching for accounts.
   - Provides functionality to populate the network from a file, manage feeds, and interactions between accounts.

## Getting Started

Download and run in your preferred IDE. Project isn't compiled into a single application so it's more or less just written code that just does the features as described but nothing else. This project is more of a simplified simulation of a social media application.





