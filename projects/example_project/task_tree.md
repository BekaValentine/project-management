# Task Tree

The task tree is the decomposition of the project into goals, and their dependencies. So for instance, if your goal is to have a cool hackable payphone, you might want to decompose that into a dependency on having a payphone, having software to run the phone, etc.

You can build the task tree as you go, you don't need to have it all fleshed out immediately. You can also include in the task tree meta-level things such as "determine what options are available" or even "determine next steps".

The task tree is just a sketch of things, and it can always be revised, but it may also make sense to produce new task trees when very large revisions are necessary, so that you can also document the nature of that change.

The following is now an example of a task tree. Notice that we're using the hierarchy of the tree to convey that the parent node in the tree can be completed by doing all of the child nodes as given. Also, we're using sequencing to convey that some things must be done before something else, but this isn't absolutely necessary. It's useful to track the before-after relationship, but sometimes there aren't strict orderings on when you have to do things, and it's useful to note that too. With markdown, you can do this to some degree by using ordered and unordered lists. Other options are to use graph visualizations. Here, we're using header structure with implicit order, so that we can make notes and keep track of information.

Notice how we're using information in the headers to indicate the state of that task. This makes it easy to track progress and determine next steps.

## STARTED: Build a hackable payphone
### STARTED: Build
#### STARTED: Build the physical object
##### DONE: Determine what kind of phone to acquire

Should we buy a whole payphone, try to assemble one from parts, cobble something together that is vaguely payphone like but also highly custom??

##### DONE: Acquire relevant components

Components currently stored in Storage Locker C.

#### DELEGATED: Build the software object

Delegation (<some_useful_reference_name>): waiting for Asterisk dev to respond to a question: <link>

Delegating should only be used for things that project contributors are not responsible for, i.e. things outside the project that you're waiting on. If a contributor can do the thing themself, then it should not be a delegation but instead just another task in the task tree.

If there are a large number of delegations like this, it's useful to track them in the `delegations.md` file.

##### Determine what kind of software design we want
##### Write software to run the phone
### Deploy
#### Determine installation location and needs

Candidate locations: X, Y, Z.

##### Visit X
##### Visit Y
##### Visit Z

Bottom Liner: Alice

Z can only be visited during so-and-so hours on such-and-such dates. Alice has a calendar item and notification to do so.

#### Transport and install
### Testing
#### Does the phone work as built?
#### Does the software work?
#### Does the software work on the phone?

Probably can't really test this until the phone is tested, but if we can simulate the phone, then that should suffice?

#### Does the phone work in its intended location?
