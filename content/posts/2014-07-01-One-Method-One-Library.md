---
title: 'One Method, One Library'
date: 2014-07-01 12:51:45
tags:
---

Date: 1 July 2014
Author: Stephanie 

# Day 2 - One Method, One Library

Today Jen, Wale and Stephanie worked with Mike McCormick. We spent some
time brainstorming about which library to work with first.

We decided to go with net/http. Users can get URI info with net/http using
the 'get' method. There is a class method and an instance method.

Using a person and a gender as a metaphor, We created a Person class and defined a gender method. Each person instance has a gender which we made flexible. We worked within that idea and explored the difference between class methods and an instance methods.
    class Person

      def gender
        @gender
      end

      def gender=(new_gender)
        @gender = new_gender
      end

      def self.create
          new
      end

    end

![Person Class](/attachments/010714-person-class-notes.jpg)

=======
