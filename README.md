# README

A simple blog based on Rails 5 with following features.
Description lists development step by step so that if anyone wants to modify the code or wants to add features, it can be done easily.


# Blog Name                                                                                             Login
=======================================================================================================================================
Listing articles
__________________________________________________________________


# My first post
------------------------------------------------------------------
Hello !


__________________________________________________________________
# Introduction
------------------------------------------------------------------
A Simple blog using Rails 5.
__________________________________________________________________


# Articles Model
------------------------------------------------------------------
* Generated a article model with "Title", "Body" and "Published at" fields using Scaffold feature.
__________________________________________________________________


# Added more fields
------------------------------------------------------------------
* Added "Excerpt" and "Location" field to articles model using generate migration.
__________________________________________________________________


# Adding Validations
------------------------------------------------------------------
* Added validations for "Title" and "Body" field.
__________________________________________________________________


# Using Rails console :irb
------------------------------------------------------------------
* Using ::irb console performed CRUD operations on article model.
__________________________________________________________________


# User and profile model
------------------------------------------------------------------
* Generated user and profile models to keep record of Users of blog.
__________________________________________________________________


# Associations among models
------------------------------------------------------------------
* Defined associations among Article, User and Profile Models. 
* Using has_one, has_many, belongs_to, has_and_belongs_to_many. 
* Defined dependencies and default order of articles.
__________________________________________________________________


# The comment model and seeding data
------------------------------------------------------------------
* Generated comments model and related it with User and Article model using rich association. has_many, :through, :source.
* Applied association proxies and default and named scope. 
* Added more validation and call_back.
__________________________________________________________________


# Updating user model
------------------------------------------------------------------
* Changed plain text password to hashed password. Added authentication methods in user model.
__________________________________________________________________


# Action Pack: Working with view and controller
------------------------------------------------------------------
* Configured routes.rb 
* Staying DrY with partials and _form_for articles. 
* Created show, edit, update actions.
__________________________________________________________________


# User controller and nested resources
------------------------------------------------------------------
* Generated users controller and made comments a nested resource in articles. 
* Updated _articles.html.erb, _comments.html.erb accordingly to show comments for posts.
__________________________________________________________________


# Defined sessions and login/logout logic.
------------------------------------------------------------------
* made session a singular resource. 
* Implemented login/logout logic. 
* Cleaned up Articles index page. 
* Added categories to articles.
__________________________________________________________________


# Requiring Authentication with Filters
------------------------------------------------------------------
* Applied authentication call_backs and redirection to controllers.
__________________________________________________________________


# Making sure articles have owners
------------------------------------------------------------------
* Added edit controls. 
* Added custom helpers. 
* Updated layout. 
* Added stylesheet.
__________________________________________________________________


# Using Jquery and Ajax: Improving user experience
------------------------------------------------------------------
* Made template loading with Ajax. 
* :format => :js, remote: true. 
* Used Ajax for forms.
__________________________________________________________________


# Sending/Receiving Emails
------------------------------------------------------------------
* Setting up ActionMailer. 
* Configured MailServer SMTP. 
* Configured application. 
* Generated Mailer controller. 
* Updated Articles Show page for sending emails.

========================================================================================================================================
"#BlogRails" 
