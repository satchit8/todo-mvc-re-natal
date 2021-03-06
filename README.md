# TodoMVC on mobile with re-natal

This is an attempt at a TodoMVC-style app implemented in Clojurescript using [React Native](https://facebook.github.io/react-native/), [Clojurescript](https://clojurescript.org/), and [re-natal].  
At the moment, only Android is supported.

## Browsing the code

Start by looking at `src/todo_mvc/android/core.cljs`. Follow the dependencies to other files.  
The `env` folder contains environment-specific code, which has been kept the same as generated by [re-natal].

## Local development

Follow the process outlined in the [re-natal documentation](https://github.com/drapanjanas/re-natal#development-with-figwheel) on running with figwheel.

## Generating an APK

Follow the process outlined in the [re-natal documentation](https://github.com/drapanjanas/re-natal#production-build) on running a production build.

## License

Copyright © 2017 Alan Tran

Distributed under the Eclipse Public License version 1.0.

[re-natal]: https://github.com/drapanjanas/re-natal
