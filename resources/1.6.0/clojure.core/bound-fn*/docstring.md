Returns a function, which will install the same bindings in effect as in
  the thread at the time bound-fn* was called and then call f with any given
  arguments. This may be used to define a helper function which runs on a
  different thread, but needs the same bindings in place.