```clojure
(def me { ;; Hi there!
          ::pronouns ["he" "him"]
          ::interests #{ ;; I don't really understand physics, but I still think it's cool.
                        "Programming" "Physics" "Conlangs" "Birdwatching"}
          ::learning #{ ;; Templates will forever remain nightmare fuel....
                       "AVR Assembly" "C++" "日本語" "something something resistivity"})
          ::enjoys #{ ;; Exploded Arduino Count: 1
                     "アニメと漫画" "Chiptune" "D&D" "Hobby electronics"}
          ::languages { ;; Rewrite it in Rust!
                       ::awesome #{"Rust" "Clojure" "Julia" "Haskell"}
                       ::awesome-sometimes #{"Python" "Scala" "C" "Elixir"}
                       ::questionable-at-best #{"Java" "JS" "GLSL" "Go" "Finnmark"}} ;; Only GLSL has a good excuse.
          ::current-setup [ ;; i use arch btw
                           "Artix" "LXQt" "Neovim"]}]} ;; I use runit as my init system
```

<!-- Hey, you read the source! Here's a free cookie. 🍪 -->
