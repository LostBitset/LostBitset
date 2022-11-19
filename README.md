```clojure
(def me { ;; Hi there!
          ::pronouns ["he" "him"]
          ::interests #{ ;; I don't understand physics, but I still think it's cool.
                        "Programming" "Molecular Biology" "Physics" "Conlangs" "Birdwatching"}
          ::learning #{ ;; Japanese and zig are cool too. Templates are nightmare fuel.
                       "C++" "Zig" "日本語"})
          ::enjoys #{ ;; I listen to synthwave and J-pop too, but mostly chiptune. 
                     "アニメと漫画" "Chiptune" "D&D" "Hobby electronics"} ;; Exploded Arduino Count: 1
          ::languages { ;; Rewrite it in Rust!
                       ::awesome #{"Rust" "Clojure" "Haskell" "Elixir"} ;; This is Clojure by the way
                       ::awesome-sometimes #{"Python" "Scala" "Julia" "C"}
                       ::questionable-at-best #{"Java" "GLSL" "Finnmark"}} ;; Only GLSL has a good excuse.
          ::current-setup [ ;; i use arch btw
                           "Artix" "LXQt" "BSPWM" "Kakoune"]}]} ;; I use runit as my init system
```

<!-- Hey, you read the source! Here's a free cookie. 🍪 -->
