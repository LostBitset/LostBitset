```clojure
(def me { ;; Hi there!
          ::pronouns ["he" "him"]
          ::interests #{ ;; I don't understand physics, but I still think it's cool.
                        "Programming" "Molecular Biology" "Physics" "Conlangs" "Birdwatching"}
          ::learning #{ ;; i mi nelci la .zeg. je la .lojban. je lo ponbau
                        ;; i ku'i mi tepsne la .tenplyt.
                       "C++" "Zig" "日本語" "la .lojban."})
          ::enjoys #{ ;; I listen to synthwave and J-pop too, but mostly chiptune. 
                     "アニメと漫画" "Chiptune" "D&D" "Hobby electronics"} ;; Exploded Arduino Count: 1
          ::languages { ;; Rewrite it in Rust!
                       ::awesome #{"Rust" "Clojure" "Julia" "Go" "Haskell"}
                       ::awesome-sometimes #{"Python" "Scala" "C" "Elixir"}
                       ::questionable-at-best #{"Java" "JS" "GLSL" "Finnmark"}} ;; Only GLSL has a good excuse.
          ::current-setup [ ;; i use arch btw
                           "Artix" "LXQt" "BSPWM" "Neovim"]}]} ;; I use runit as my init system
```

<!-- Hey, you read the source! Here's a free cookie. 🍪 -->
