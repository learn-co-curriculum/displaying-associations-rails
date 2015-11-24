
# Displaying Associations Rails

## Objectives

Students will be able to:

1. Create a has_many and belongs to association.
2. Build associated data through console (or perhaps seeds).
3. Query for associated data using methods provided by association.
4. Embed association data within views.
5. Iterate over associated data within a view displaying individual instances.

## Notes

Displaying Associated Data
  give posts a category
  category/post resource
  Create a category
  Create a post
  assign a post a category in console
  display the post category in posts#show
  list the posts in a category in category#show

Setup a Post belongs to a Category and a Category has many posts.
RESTful controllers for both resources are available

The README should address building out the Post#show view to display a link_to the category#show and the name of the category. That will require using the belongs to method. To do this walk the user through creating the development data from console (even perhaps seeds?).

Once the post#show is displaying the association data. move onto to displaying the links to each post for a category. show them how to give multiple posts for a category in console/seeds.

standard @category.posts iteration. show the similarity of this loop on posts#index (as in, iterating through a collection of instances is no different if those objects are loaded through an association or thorugh a AR query. That's infact the similarty of a ActiveRecord::CollectionProxy object).
