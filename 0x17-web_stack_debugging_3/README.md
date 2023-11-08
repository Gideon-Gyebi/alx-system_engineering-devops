# 0x17-web_stack_debugging_3

## Concepts
For this project, we expect you to look at these concepts:

1. Web Server
2. Web stack debugging
3. Background Context


When debugging, sometimes logs are not enough. Either because the software is breaking in a way that was not expected and the error is not being logged, or because logs are not providing enough information. In this case, you will need to go down the stack, the good news is that this is something Holberton students can do :)

Wordpress is a very popular tool, it allows you to run blogs, portfolios, e-commerce and company websites… It actually powers 26% of the web, so there is a fair chance that you will end up working with it at some point in your career.

Wordpress is usually run on LAMP (Linux, Apache, MySQL, and PHP), which is a very widely used set of tools.

The web stack you are debugging today is a Wordpress website running on a LAMP stack.

## Requirements General
1. All your files will be interpreted on Ubuntu 14.04 LTS
2. All your files should end with a new line
3. A README.md file at the root of the folder of the project is mandatory
4. Your Puppet manifests must pass puppet-lint version 2.1.1 5.without any errors
5. Your Puppet manifests must run without error
6. Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
7. Your Puppet manifests files must end with the extension .pp
8. Files will be checked with Puppet v3.4

## More Info
Install puppet-lint
1. $ apt-get install -y ruby
2. $ gem install puppet-lint -v 2.1.1