# fancy-cucumber-tables
I have worked on projects that use Cucumber as a test tool instead
of as a requirement collaboration tool. One project had over 400K lines of feature
files to cover 50K lines of Java code. It was awful. The application was message
oriented and every scenario had very large tables that created input messages, verified
database contents, and verified output messages. 

The standard advice is "don't do this"; which is good advice, but not helpful when
you're in the middle of a mess. 

This repo explores some techniques to make working with massive data tables a little
easier and a little easier to understand.



