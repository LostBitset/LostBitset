```clojure
(def me { ;; Hi there!
          ::pronouns ["he" "him"]
          ::interests #{ ;; I don't really understand physics, but I still think it's cool.
                        "Programming" "Physics" "Conlangs" "Birdwatching"}
          ::learning #{ ;; SAT solvers are just awesome.          (           physics rn          )
                       "AVR Assembly" "C++" "SAT Solving" "日本語" "something something resistivity"})
          ::enjoys #{ ;; I listen to a fair amount of synthwave and J-pop too, but mostly chiptune. 
                     "アニメと漫画" "Chiptune" "D&D" "Hobby electronics"} ;; Exploded Arduino Count: 1
          ::languages { ;; Rewrite it in Rust!
                       ::awesome #{"Rust" "Clojure" "Julia" "Haskell"}
                       ::awesome-sometimes #{"Python" "Scala" "Go" "C" "Elixir"}
                       ::questionable-at-best #{"Java" "JS" "GLSL" "Finnmark"}} ;; Only GLSL has a good excuse.
          ::current-setup [ ;; i use arch btw
                           "Artix" "LXQt" "BSPWM" "Neovim"]}]} ;; I use runit as my init system
```

<!-- Hey, you read the source! Here's a free cookie. 🍪 -->
