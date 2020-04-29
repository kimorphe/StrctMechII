all:ans1.pdf report1.pdf
ans1.pdf: ans1.dvi
	dvipdfmx -p a4 ans1.dvi
ans1.dvi: ans1.tex fig1ans.eps fig2ans.eps fig3ans.eps
	platex ans1.tex
fig1ans.eps: Figs/fig1ans.svgz
	inkscape -z -f Figs/fig1ans.svgz -E fig1ans.eps 
fig2ans.eps: Figs/fig2ans.svgz
	inkscape -z -f Figs/fig2ans.svgz -E fig2ans.eps 
fig3ans.eps: Figs/fig3ans.svgz
	inkscape -z -f Figs/fig3ans.svgz -E fig3ans.eps 

report1.pdf: prb1.pdf
	mv prb1.pdf report1.pdf
prb1.pdf: prb1.dvi
	dvipdfmx prb1.dvi
prb1.dvi: prb1.tex fig1.eps
	platex prb1.tex 
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps 


