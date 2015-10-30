# clara-tools

Experimental tooling for exploring and working with Clara-based rulesets.

See the [clara-rules project](https://github.com/rbrush/clara-rules)
for details on Clara.

## Usage

```clojure
(require
 '[clara.tools.ui :as ui]
 '[clara.rules :as rules])

(def my-session (rules/mk-session))

;; Show facts in a clara session in your browser
(ui/show-session my-session)

;; Show the logic graph in your browser
(ui/logic-graph '[namespace.where.your.rules.live])
```

## License

Copyright © 2014 Ryan Brush

Distributed under the Eclipse Public License, the same as Clojure.
