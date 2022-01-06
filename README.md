ls - Papkanin icindeki fayllara baxmaq ucun
git init - islediyim papkanin icinde git yaratmaq ucun
git status - hal hazirda olan deyisikleri gosterir(Modified, untracked, new files)
git add .  veya git add index.txt - fayllari stage area-a gondermek ucun
git rm --cached .  veya git rm --cached index.txt - fayllari stage areadan silmek ucun
git log --oneline - olan butun butun commitlerin siyahisini cixardir
git reset --hard commitId - hemin id - si olan commite geri donur ondan sonra olan butun commitleri silir
git reset --soft commitId - hemin id-si olan commite geri donur lakin hemin commitde olan fayllar stage areada qalir
git branch -a - branchlerin siyahisini cixardir
git branch test_branch - test_branch adinda yeni branch yaradir
git checkout test_branch - test_branch-a kecid etmek ucun
git branch -D test_branch - branchi silmek ucun
git merge test_branch - Tutaq ki biz hansi bir brancdeyik(checkout master). Ve bu branch-e test_branch-i birlesdirmek isteyirik.
git push link master - remote repositerinin linkine master branchini push etmek
git remote add origin link - Istifade qaydasi rahat olsun deye remote repositerinin linkini ad(origin) qoyuruq.
git clone link - her hansi bir remote repositerideki olan proyekti kopyalamaq ucun
git fetch origin --> git merge origin/master - Evvelce fetch edir sonra ise onu master branch-ni birlesdirir
git pull origin master -- remote repositeride olan deyisikleri localdaki master branch-ine merge edir
git touch .gitignore - basalarinin gormemeli oldugu fayllarin adlarini bu faylin icinde qeyd edirik. Meslen index.txt
