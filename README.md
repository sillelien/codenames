codenames
=========

A sample bash script to convert hex values (such as commit ids) to codenames

    Usage ./names.sh <hex-value>

The hex-value should be 12 characters or more.

# Why would I use this?

To give meaningful and easy to remember names for commits, so that they can be used as codenames for releases. super-sized-wallaby is easier to remember than 4c33c6c7b7826063cd7d75b943057b5e5872661a.

# How random is this?

190 adjectives * 29 adverbs * 842 nouns = 4,639,420 combinations

Add your own nouns, adjectives and adverbs to increase the number of possibilities.

# Can I contribute?

Sure, the rules are as follows:

  1. All adverbs should be were possible West Coast Hip :-) Think Bill and Ted -> Point Blank -> Silicon Valley
  2. Adjectives must be positive, we're using these for releases so words like 'dank', 'messy' etc. don't really work well
  3. Nouns should be *cool* - yeah you figure out what cool means - things like llama, kitteh, cake are good, things like car, office, bucket aren't.


Oh yeah and this is a quick and dirty hack so no validation or fancy stuff yet. But really do you need it for something this simple :-)


