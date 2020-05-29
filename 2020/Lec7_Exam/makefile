all: exam.pdf ans.pdf
exam.pdf: exam.dvi
	dvipdfmx -p a4 exam.dvi
exam.dvi: exam.tex fig1.eps fig2.eps fig3.eps fig4.eps
	platex exam.tex 
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps 
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps 
fig3.eps: Figs/fig3.svgz
	inkscape -z -f Figs/fig3.svgz -E fig3.eps 
fig4.eps: Figs/fig4.svgz
	inkscape -z -f Figs/fig4.svgz -E fig4.eps 

ans.pdf: ans.dvi
	dvipdfmx -p a4 ans.dvi
ans.dvi: ans.tex fig1ans.eps fig2ans2.eps fig2ans.eps fig2ans3.eps fig2ans4.eps fig3ans.eps fig4ans.eps fig5ans.eps
	platex ans.tex
#	fig4ans.eps fig5ans.eps fig6ans.eps
fig1ans.eps: Figs/fig1ans.svgz
	inkscape -z -f Figs/fig1ans.svgz -E fig1ans.eps 
fig2ans2.eps: Figs/fig2ans2.svgz
	inkscape -z -f Figs/fig2ans2.svgz -E fig2ans2.eps 
fig2ans.eps: Figs/fig2ans.svgz
	inkscape -z -f Figs/fig2ans.svgz -E fig2ans.eps 
fig2ans3.eps: Figs/fig2ans3.svgz
	inkscape -z -f Figs/fig2ans3.svgz -E fig2ans3.eps 
fig2ans4.eps: Figs/fig2ans4.svgz
	inkscape -z -f Figs/fig2ans4.svgz -E fig2ans4.eps 
fig3ans.eps: Figs/fig3ans.svgz
	inkscape -z -f Figs/fig3ans.svgz -E fig3ans.eps 
fig4ans.eps: Figs/fig4ans.svgz
	inkscape -z -f Figs/fig4ans.svgz -E fig4ans.eps 
fig5ans.eps: Figs/fig5ans.svgz
	inkscape -z -f Figs/fig5ans.svgz -E fig5ans.eps 

