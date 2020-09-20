# General

* Name files by concept / learning outcome rather than details of example

# 1

* Advantage to passing String.new as opposed to a string literal?
* Let blocks interfering with the 'story' of a test - DRY is less important for testing

# 2

* Unsure about comment about nested order? Appears in written order to me
* Updating implicit subject is slightly confusing
* Less is more - slightly too many ideas
* Probably shouldn't show the wrong way (implicit subject) first

# 3

* Is the compound example recommended or not? Unclear from previous line about not combining tests

# 4

* Predicate method style names (with ?) for hash keys? Haven't seen before. Not necessarily wrong

# 5

* More focused (++) but slightly more info in the top comment.

# 6

* Side rant about rspec, but having eq, eql and equal do three different things is ridiculous
* Lesson good though

# 7

# 8

# 9

* 9 mentions matcher scope but not what that actually is. Within a describe block? just within a block

# 10

* Structure of various components? context, describe, let, subject, custom matcher etc

# 11

* Good conceptually but could be simplified

# 12

* I think this should come much earlier than 12 as a concept. Pretty useful concept that's reaonsably easier to absorb and a good rule of thumb to have in your pocket while testing

* How does using subject work with the AAA pattern? Where should subjects go in their respective blocks?

# 13

* Need a reminder or reference for custom matchers
* If the main goal of this is to show how small methods are easier to test the custom matchers req confuses and obscures this somewhat
* 'In addition, it is unnecessary to test methods that only  contain puts and/or gets.'
=> again really great info that is more relevant to beginners that should probably be highlighted earlier, again like more general conceptual stuff ie private vs public
* Impossible to test is a good idea but i think it's too abstract

# 14

* This info, or  something similar to it should probably be an actual lesson in the testing section
* 'it is possible to add method names to subject...' figured it out but wasn't immediately obivious. Is this conflicting with AAA / story telling of tests?
* Lots of good content but hard to follow at times. Large blocks of comments can be distracting and hide the way tests are supposed to look / be structured

# 15

* Again, some of this kind of info belongs in a lesson rather than a side exercise
* Source? Curious to read more particularly the script / looping script concepts
* Very dense
* .exactly(5).times is new syntax
* Too many concepts, too much new syntax at once, slightly unclear on what the current focus is in the current exercise
* Instance variable get - smelly?
* the part of about method expectations feels important but is confusing.
Trying to explain the difference between stubs and mocks?
