
all: prb4.pdf note4.pdf

prb4.pdf: prb4.dvi
	dvipdfmx prb4.dvi
prb4.dvi: prb4.tex prb.eps
	platex prb4.tex
note4.pdf: note4.dvi
	dvipdfmx note4.dvi
note4.dvi: note4.tex fig1.eps fig2.eps fig3.eps fig4.eps  fig5.eps fig6.eps fig7.eps fig8.eps
	platex note4.tex

prb.eps: Figs/prb.svgz
	inkscape -z -f Figs/prb.svgz -E prb.eps 
fig1.eps: Figs/fig1.svgz
	inkscape -z -f Figs/fig1.svgz -E fig1.eps 
fig2.eps: Figs/fig2.svgz
	inkscape -z -f Figs/fig2.svgz -E fig2.eps 
fig3.eps: Figs/fig3.svgz
	inkscape -z -f Figs/fig3.svgz -E fig3.eps 
fig4.eps: Figs/fig4.svgz
	inkscape -z -f Figs/fig4.svgz -E fig4.eps 
fig5.eps: Figs/fig5.svgz
	inkscape -z -f Figs/fig5.svgz -E fig5.eps 
fig6.eps: Figs/fig6.svgz
	inkscape -z -f Figs/fig6.svgz -E fig6.eps 
fig7.eps: Figs/fig7.svgz
	inkscape -z -f Figs/fig7.svgz -E fig7.eps 
fig8.eps: Figs/fig8.svgz
	inkscape -z -f Figs/fig8.svgz -E fig8.eps 


