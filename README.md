# Library-manager
About :
This software manages many aspects of a university library system, including cataloging, search, circulation, and waiting list. The interface must be dekstop based, and the server needs to be hosted on the localhost.
A librarian must be able to manage the catalog of the books.

. A book item contains at least the following properties
   1. Book ID
   2. Name
   3. Price
   4. Publisher
   5. Pages
   6. Edition

. A librarian must be able to search, add, update, and delete books.
   1. Search capability needs to function as a superset of search features to be described below for patrons.  
   2. The minimal feature to add for search is the capability to search for books created or updated by a particular librarian.  
   3. Update and deletion must be able to work together with search, i.e., a librarian must have the capability to find a book through search, then decide to update/delete it.
   4. A book cannot be deleted if it’s checked out by a patron.
   5. Deleting a book also removes the waiting list for it, if there is any.
   
   
   The project plan  includes
* The platform and technology choices (Netbeans, MySQL, phpMyadmin etc)
* Division of work with feature owner specified
* Milestones with expected dates
