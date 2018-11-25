berlhg.pdf: berlhg_context.tex berlhg.tex
	lualatex berlhg.tex

berlhg_context.tex: berlhg.md
	pandoc -f markdown -o berlhg_context.tex -t latex berlhg.md
