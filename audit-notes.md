# About this project

This is the part of the Cyfrin security and auditing course
It is the first part of it where I review the code to improve/find vulnerabilities in security

The essence of the project is that only an owner can set and retrieve a password

# Attack vulnerabilities

It seems indeed that the test for the first function is only looked into the part that an owner can set the password
Yet, it does not check in the test if a non-owner can set the password

Other (major) issue is that the password is not secure because it is stored on chain.

//need to add @audit
