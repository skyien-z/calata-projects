VSCode [https://marketplace.visualstudio.com/items?itemName=catalalang.catala]

opam pin catala-lsp git+https://github.com/CatalaLang/catala-language-server.git

Catala code must be placed in ticks ```catala and ended with end ticks: ```.
This will trigger automatic syntax highlighting. You will not see this syntax highlighting if you do not place code in ticks.

show the compilation to different languages:
catala scopeland pl_beverage_tax.catala_en
catala dcalc pl_beverage_tax.catala_en
catala lcalc pl_beverage_tax.catala_en

run a catala script:
catala interpret --scope Test --disable-warnings pl_beverage_tax.catala_en
