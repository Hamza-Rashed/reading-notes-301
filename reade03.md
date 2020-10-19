# What is Mustache?

The first thing to learn is that Mustache is NOT a templating engine. Mustache is a specification for a templating language. This specification can be found here, but don't read that just yet. You're not ready yet.

The idea is, that you write templates that adhere to the Mustache specification, that then can be compiled / rendered to create an output.

## What's a Templating Language and what's it for?

Let's say you want to send the same email to 100 people, except you want to personalize the salutation with their respective first names. You could replace the first name by some placeholder:

``` Dear *|FNAME|* ```

I hearby blablabla ...

Here I have invented (=stolen it from Mailchimp) a syntax for a placeholder: *|FNAME|*

The mustache syntax looks a bit different. This case would be covered by the following template:

Dear {{fname}}

I hearby blablabla ...

![](https://i.ytimg.com/vi/Ehp-55yISo0/hqdefault.jpg)

# what is flex box ??
For a long time, the only reliable cross browser-compatible tools available for creating CSS layouts were things like floats and positioning. These are fine, and they work, but in some ways they are also rather limiting and frustrating.

The following simple layout requirements are either difficult or impossible to achieve with such tools, in any kind of convenient, flexible way:

    Vertically centering a block of content inside its parent.
    Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
    Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

As you'll see in subsequent sections, flexbox makes a lot of layout tasks much easier. Let's dig in!

``` section {display: flex} ```

![](https://miro.medium.com/max/2732/1*HFAEJvVOq4AwFuBivNu_OQ.png)
