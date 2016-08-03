# LINKED LIST
### definition
   - `collection of nodes`
      - nodes in a singly linked list have two attributes
         - one attribute contains the value of the node
         - the other attribute is a reference to the next node

  - nodes in a doubly linked lists have three attributes
      - an attribute that contains has the node value
      - an attribute that references the next node
      - and one that references the previous node


### singly lists basic operations
- `insert`
   - link of node before new node is changed to point to the new node
   - new node link is set to the node of the previous node was pointing to before insertion


- `remove`  
   -  link of the node before the removed node is redirected to point to the node the removed node is pointing to pointing to


### doubly linked lists basic operations
- `insert`
   - next link of node before new node is changed to point to new node
   - previous link of new node points to node before new node
- `remove`
   - next link of previous node is changed to point to

### other operations
- `find`

- `display`
