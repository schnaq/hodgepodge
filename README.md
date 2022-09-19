# hodgepodge

An idiomatic ClojureScript interface to local and session storage.

This is a fork of [funcool.hodgepodge](https://github.com/funcool/hodgepodge).

Makes working with local- and sessionStorage easy. Checks if localStorage is
available. The original repository assumes that the localStorage is available,
but fails with an exception if the user has blocked its usage.

Import it in your deps.edn:

```clojure
{:deps
  {schnaq/hodgepodge {:git/url "https://github.com/schnaq/hodgepodge.git"
                      :sha "<SHA of latest commit>"}}}
```

**Documentation**: https://funcool.github.io/hodgepodge/
