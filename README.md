# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

<!-- Notes from posts/show.html.erb -->

<!-- <%= render partial: "comments/comment", collection: @post.comments %> -->
<!-- 'collection' assigns current element to local var with same name as partial -->

<!-- <%= render partial: "comments/comment", collection: @post.comments, as: :comment %>    -->
<!-- assigns each @post.comment to :comment local variable -->


<!-- <% @post.comments.each do |comment| %>
       <%= render partial: "comments/comment", locals: {comment: comment} %>
     <% end %> -->
<!-- "comments/comment" because it looks in posts folder by default. 'locals:' establishes local variables for comment objects -->
