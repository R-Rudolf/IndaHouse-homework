# About

Creating a simple blog webpage with the pyp yii framework

# Capabilities

## Two tables: posts and categories

Collumns for posts:  id, title, lead, content, deleted (boolean), created_at (datetime), category_id (fk)
Collumns for categories: id, name

## Operations

 - Full CRUD operation support for both tables.
 - Listing calabilities for both. (only not "deleted" posts)
 - Search option for post titles.

When deleting a post, only the 'deleted' collumn will be changed.

Will have welcome page with listing all posts, but only with 'title' and 'lead'.
Will have a post view page

# Page summary

 - welcome_page		with post excerpts
 - post_view		with all details
 - category_editor	: Create new, Delete, Read all fields, Edit editable collumns
 - post_editor		: --||--
 - category_list	...
 - search_page		for post titles
  - Using the same listing capabilities as the welcome page (if possible)
