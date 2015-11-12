# meteor-newcomer

Meteor is more fun with React, and [tutorial][tutorial] is a great place to start learning both Meteor and React.

[tutorial]: https://www.meteor.com/tutorials/react/creating-an-app

## Tools

- WebStorm 11.0.1
  - be sure to [_Download_ TypeScript definition file for React][download-ts-definition] (so WebStorm does not complain about attribute `className` which is not _allowed here_)
  - and switch JavaScript language version to _JSX Harmony_

[download-ts-definition]: http://blog.jetbrains.com/webstorm/2015/10/working-with-reactjs-in-webstorm-coding-assistance/

## Running on mobile

- Following all instruction does not result in `meteor run andoird` to work, installing system image helper.
  - To fix it, run `andoird sdk` and install _Intel x86 Atom_64 System Image_ for required SDK Platform.
