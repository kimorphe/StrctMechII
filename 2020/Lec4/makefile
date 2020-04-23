note4.pdf: note4.dvi
	dvipdfmx note4.dvi
note4.dvi: note4.tex fig1.eps fig2.eps fig3.eps fig4.eps 
	platex note4.tex
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps 
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps 
fig3.eps: Figs/fig3.svgz
	inkscape -z -f Figs/fig3.svgz -E fig3.eps 
fig4.eps: Figs/fig4.svgz
	inkscape -z -f Figs/fig4.svgz -E fig4.eps 


