# clojure_hello_world_5_diff_ways

1) from terminal:
  clj -e '(println "Hello World!")'

2) in repl:
  clj
  (println "Hello World!")

3) create hello.clj file with (println "Hello World!") and run it as script:
  clj hello.clj  

4) create hello/src.hello.clj with:
  (ns hello) 
  (defn -main "HelloWorld entry point"
    []
    (println "Hello World!)) 
  && cd hello && clj -m hello

5) with Leinigen:
  lein new app helloleiningen
  &&
  cd helloleiningen
  &&
  lein run\
  or\
  clj -m helloleiningen.core
