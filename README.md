# meteor-newcomer

Meteor is more fun with React, and [tutorial][tutorial] is a great place to start learning both Meteor and React.

[tutorial]: https://www.meteor.com/tutorials/react/creating-an-app

## Tools

- WebStorm 11.0.1
  - be sure to [_Download_ TypeScript definition file for React][download-ts-definition] (so WebStorm does not complain about attribute `className` which is not _allowed here_)
  - and switch JavaScript language version to _JSX Harmony_
  - Want to have introspection on used packages? Read [Importing Meteor Packages][importing-meteor-packages] section carefully.

[download-ts-definition]: http://blog.jetbrains.com/webstorm/2015/10/working-with-reactjs-in-webstorm-coding-assistance/
[importing-meteor-packages]: https://www.jetbrains.com/webstorm/help/using-meteor.html#d245970e538

## Running on mobile

- Following all instruction does not result in `meteor run andoird` to work, installing system image helps.
  - To fix it, run `andoird sdk` and install _Intel x86 Atom_64 System Image_ for required SDK Platform.
  - Then create AVD using `android avd`.  

## Structure and CLI tools

- http://meteortips.com/first-meteor-tutorial/structure/

## Routing

- https://github.com/iron-meteor/iron-router
- https://www.okgrow.com/posts/flow-router-migration-guide

## Package Development

- https://atmospherejs.com/i/publishing
- https://themeteorchef.com/recipes/writing-a-package/

## Stay at the top

- Subscribe to https://twitter.com/zubkou/lists/meteor
