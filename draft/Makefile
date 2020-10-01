all: trees.svg trees.png

trees.svg: trees.gv
	dot -Tsvg trees.gv -o trees.svg

trees.png: trees.gv
	dot -Tpng trees.gv -o trees.png

clean:
	rm -f trees.svg trees.png
