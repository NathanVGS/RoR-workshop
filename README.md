# Get Rolling on (Ruby on) Rails

- Type of Challenge: `Learner Workshop`
- Duration: `3 hours`

## Learning objectives
- Install Ruby, Rails
- Setup your first project
- Learn the basics of Ruby on Rails through building a simple weblog
  - Learn your way around the file structure
  - Learn to use the MVC layer of Ruby on Rails
  - Learn to use the routing component
  - Learn about RubyGems
  - Learn about HTTP handling
  

## The Mission
In this workshop, I would like to guide you through the first steps of learning Ruby on Rails by building a weblog together. You will run into some familiar concepts like the MVC model, HTTP requests, routing and templates, and will also work with a virtual database that will store all the information you are adding to your web server. 

For Lamarr, all of this should remind you very much of Symfony. For Giertz, I will try to help you as much as I can where needed, but will always try to supply enough documentation for you to find your way as well.

### Step 1: Install Ruby and Rails (10 minutes)

#### Installing Ruby

It's always worth checking if your computer came with Ruby preinstalled, or maybe you at some point installed it and never touched it again. You can do so by typing the following, usual code in your terminal: 

```
ruby -v
```

If this returns a message similar to:

```
ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-linux]
```
... Then you're set! Otherwise, you can follow this link for the different installation methods depending on your operating system:
https://www.ruby-lang.org/en/documentation/installation/

For us Linux/Ubuntu users, i'll include the very simple terminal command you will need:

```
$ sudo apt-get install ruby-full
```

#### Installing Rails

Next up, we need to install Rails itself, as it will allow us to generate a plethora of things that have been prebuilt for us, which will help us set up our own weblog without much difficulty. For that, I will also include a link to an external source:

http://guides.railsgirls.com/install

Follow the steps for your specific system all the way up to having installed Rails. You do not need to install any text editors anymore, since you either decided to install RubyMine or chose to work with your own editor of choice. 

If you did not install RubyMine, but still wish to, you can follow the link below this line. Just log in with your JetBrains credentials and download it for free:

https://www.jetbrains.com/ruby/promo/?gclid=CjwKCAjwzvX7BRAeEiwAsXExoxwQlLse8C3ll7BnBb5O54LiAW-2PT_ROQ3skOHt3u6QSkEKoaXpnxoCtWwQAvD_BwE

### Step 2: Starting our project and navigating the directories

Now that we have Ruby, Rails and a suitable text editor, we can start by setting our own directories and subsuequently navigate the directories from Ruby on Rails as well.

- First use the terminal to navigate to the directory you want to store your project in.
- Once there, use the following command to generate the main files for your project:

```
rails new yourProjectName
```

I suggest you use a name like rubyBlog, blogger, or something that will remind you what the project was all about in a few weeks ;) 

Now, let's move on to setting up our repository online and connecting it to this directory. Go to your own github and make a new repository, but do not initialize it with a README.md.

Next, navigate into your new Rails project and initialize your git using the ```git init ``` command.

