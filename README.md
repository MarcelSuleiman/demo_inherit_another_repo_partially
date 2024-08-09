```sh
mkdir final_test
cd final_test
git init
git remote add -f origin https://github.com/MarcelSuleiman/demo_cherry_pick_clone.git
git config core.sparseCheckout true
echo "AAA/" >> .git/info/sparse-checkout
git pull origin main
git config core.sparseCheckout false
```
