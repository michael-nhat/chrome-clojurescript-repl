
load file lay tu localhost 8000 >> cho vao the script<src = url></src>
va de browser tu goi

minh cung lam nhu the
tao ra script element va append vao do
va goi su kien append khi co message (qua port connection ws/localhost )

project clj kia chi de build code ra chay roi load, mien la no ra javascript

1 tao send function trong clj-server
client addon nhan request eval se lay js chunk append to script (browser seem run it imidiaately)

##### todo
    v- https://stackoverflow.com/questions/33093833/display-complete-dependency-tree-with-leiningen
        check deps tree for cider nrepl
    update cider nrepl see what happend
    create hot eval-append-script

check deps, recursive search in : ~/m2/

wget -r -np -nH --cut-dirs=3 -R index.html https://mirror.nju.edu.cn/clojars/dom2edn/
lein localrepo install ./dom2edn/dom2edn/0.1.0/dom2edn-0.1.0.jar dom2edn/dom2edn 0.1.0
