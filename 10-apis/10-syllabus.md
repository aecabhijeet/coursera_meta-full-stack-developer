# Syllabus

## Module 1 REST APIs

Get to know RESTful API development.
15 videos, 15 readings
Video: Introduction to the course
Video: How are APIs used in the real world?
Discussion Prompt: What do you hope to learn?
Reading: Course syllabus
Reading: Working with labs and exercises in this course
Reading: How to be successful in this course
Video: What you know about HTTP
Reading: HTTP methods, status codes and response types
Video: RESTfulness
Ungraded Plugin: Connecting the Dots: REST and CRUD
Video: Naming conventions
Reading: Good routes versus bad routes
Video: Essential tools for API development
Reading: Installing VS Code
Reading: Setting up tools and environment
Video: Create a Django Project using pipenv
Reading: Optional: Creating a Django project (steps and code)
Reading: Exercise: Know your tools
Graded Assignment: Self review: Know your tools
Graded Assignment: Knowledge Check: Introduction to APIs
Reading: Additional resources
Video: REST best practices
Video: Security and authentication in REST API
Video: Access control
Reading: Authentication versus authorization
Graded Assignment: Knowledge check: Principles of API development
Video: Book List API project
Video: Organizing an API project
Reading: Consequences of a poorly designed API project
Reading: XML and JSON response types
Ungraded Plugin: Planning Your First API
Ungraded Lab: Exercise: Your first API
Reading: Solution: Your first API
Graded Assignment: Self review: Your first API
Video: Debugging your API
Video: Browser tools and extensions for API development
Reading: Mock APIs
Video: Module summary: REST APIs

module 1 material
Graded: Module quiz: REST APIs

## Module 2 Django REST framework

Use the Django REST framework to create APIs efficiently, then learn to serialize your database models and convert, validate and render data.
12 videos, 8 readings
Video: What is the Django REST framework (DRF)?
Video: Installing and setting up DRF
Video: Better API view with decorators
Reading: Different types of routing in DRF
Reading: Generic views and ViewSets in DRF
Video: Function and class-based views
Video: Django debug toolbar
Video: Restaurant menu API project with DRF
Ungraded Lab: Convert booklist API project to DRF
Reading: Solution: Convert booklist API project to DRF
Graded Assignment: Self review: Convert booklist API project to DRF
Graded Assignment: Knowledge check: Introduction to DRF
Reading: Additional resources
Video: Serializers
Video: Model serializers
Video: Relationship serializers
Reading: Other types of serializers in DRF
Video: Deserialization and validation
Video: Renderers
Reading: Different types of renderers
Ungraded Lab: Exercise: Restaurant menu API using serialization
Reading: Solution: Restaurant menu API using serialization
Graded Assignment: Self review: Restaurant menu API using serialization
Video: Module summary: Django REST framework
Reading: Additional resources

module 2 material
Graded: Module quiz: Django REST framework

## Module 3 Advanced API development

Control access to your APIs, and put systems in place to ensure you maintain their health.
11 videos, 9 readings
Ungraded Plugin: Preparing for Advanced API Features
Video: Filtering and searching
Video: Ordering
Reading: Importance of data validation
Reading: Data sanitization
Video: Pagination
Reading: More on filtering and pagination
Video: Caching
Ungraded Lab: Exercise: Restaurant menu API - filtering, ordering
Reading: Solution: Restaurant menu API - filtering, ordering and searching
Graded Assignment: Self review: Restaurant menu API - filtering, ordering and searching
Graded Assignment: Knowledge check: Essential API tasks
Reading: Additional resources
Video: Token-based authentication in DRF
Video: User roles
Video: Setting up API throttling
Reading: API throttling for class-based views
Video: Introduction to Djoser library for better authentication
Video: Registration and authentication endpoints with JWT
Video: User account management
Reading: Exercise: User account management
Reading: Solution: User account management
Graded Assignment: Self review: User account management
Video: Module summary: Securing an API in Django REST framework
Reading: Additional resources

module 3 material
Graded: Module quiz: Securing an API in Django REST framework

## Module 4 Final project assessment

Practice and reflect on the skills you learned in this course.
4 videos, 4 readings
Video: Course recap: APIs
Reading: About the final assessment
Video: Project introduction
Reading: Project structure and API routes
Video: Creating models
Reading: Peer-review solution
Discussion Prompt: What challenges did you encounter when building your restaurant API?
Video: Course wrap up
Discussion Prompt: Reflect on learning
Reading: Next steps

module 4 material
Graded: Little Lemon API project
Graded: Final graded quiz: APIs


# 10.1.4

This course introduces you to API development on a foundational level. You will delve deeper into the processes and concepts behind APIs and their infrastructure. 

For instance, you will learn how to build APIs with the Django Rest Framework(DRF). But since DRF is primarily a toolkit built on top of the Django framework, this course assumes that you have a good understanding of basic Django concepts. Like how to work with views, models, and templates. To get the most out of this course, it is a good idea to review these basic concepts in the Django Web Framework course by Meta. 

In this course, each week intends to equip you with the knowledge and skills needed to drive you toward a better understanding of API development. 

Week 1: Rest APIs
In the first week, you will start with an overview of how APIs are used in the real world and a refresher on HTTP and HTTPS before you cover the basics of REST architecture and RESTful APIs. 

After completing the lesson items, you will be able to:

Identify the key characteristics, benefits and uses of REST APIs

Create API routes according to correct naming conventions and best practices

Explain the principles of authentication in a REST API

Differentiate between authentication and authorization

Explain the API request lifecycle

Create a basic API and organize an API project

Explain different types of API output, like JSON and XML

Use various tools for API development

Week 2: Django REST framework
In the second week, you will learn how to use the Django REST framework to create APIs efficiently, and then you will learn to serialize your database models, convert, validate and render data.

After completing the lesson items, you will be able to:

Install and set up the Django REST framework in VS Code

Test APIs straight from the browser using the API view decorator

Use function and class-based views to create API endpoints efficiently

Serialize database models using different types of serializers 

Validate input data and then map it to a model using the validation and deserialization process in DRF

Render API output as JSON and XML data using different types of renderers

Use throttling and caching to optimize and protect your API

Create a basic API project using DRF

Debug your APIs using the debug toolbar 

Week 3: Advanced API development
After familiarizing yourself with the Django REST framework and how to use it, you will focus on more advanced API development. You'll learn more about controlling access to your APIs and how to implement searching, ordering, filtering and pagination to optimize your APIs.

After completing the lesson items, you will be able to: 

Use token-based authentication to optimize access to your APIs for authenticated clients

Implement API throttling to control how often anonymous and authenticated users can access your APIs

Explain different ways to implement caching to save API infrastructure resources

Prevent users from doing anything outside of their privileges using an authorization layer

Implement search, ordering, filtering and pagination to allow client applications to get access to specific data via your APIs

Week 4: Graded assessment
In the final week, you'll apply the skills you gained from the course to create and test a Little Lemon restaurant API project with features like order placement and role-based APIs. You will then move on to complete the final graded assessment. After that, you will have the opportunity to reflect on the course content and review the learning path. 

After completing the project, you will be able to: 

Develop an API project with Django and DRF for an online ordering application for the Little Lemon restaurant 

Create APIs to register, assign and authenticate different user roles

Create a suitable database schema for the online ordering application 

Create API endpoints with CRUD operations in the database

Use filtering, sorting and pagination to optimize the output of your APIs

Enforce user authentication, role-based operations, and throttling to specify and limit access to your APIs for different user roles