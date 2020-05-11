#all: exam.pdf ans.pdf
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

#ans.pdf: ans.dvi
#	dvipdfmx -p a4 ans.dvi
#ans.dvi: ans.tex fig1ans.eps fig2ans.eps fig3ans.eps fig4ans.eps fig5ans.eps fig6ans.eps
#	platex ans.tex
#fig1ans.eps: fig1ans.svgz
#	inkscape -z -f fig1ans.svgz -E fig1ans.eps 

