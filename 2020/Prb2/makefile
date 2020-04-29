all:ans2.pdf report2.pdf

ans2.pdf: ans2.dvi
	dvipdfmx -p a4 ans2.dvi
ans2.dvi: ans2.tex fig1ans.eps fig2ans.eps fig3ans.eps fig4ans.eps fig5ans.eps
	platex ans2.tex

fig1ans.eps: Figs/fig1ans.svgz
	inkscape -z -f Figs/fig1ans.svgz -E fig1ans.eps 
fig2ans.eps: Figs/fig2ans.svgz
	inkscape -z -f Figs/fig2ans.svgz -E fig2ans.eps 
fig3ans.eps: Figs/fig3ans.svgz
	inkscape -z -f Figs/fig3ans.svgz -E fig3ans.eps 
fig4ans.eps: Figs/fig4ans.svgz
	inkscape -z -f Figs/fig4ans.svgz -E fig4ans.eps 
fig5ans.eps: Figs/fig5ans.svgz
	inkscape -z -f Figs/fig5ans.svgz -E fig5ans.eps 

report2.pdf: prb2.pdf
	mv prb2.pdf report2.pdf
prb2.pdf: prb2.dvi
	dvipdfmx prb2.dvi
prb2.dvi: prb2.tex fig1.eps fig2.eps
	platex prb2.tex 
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps 
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps 


