all: prb5.pdf note5.pdf 
prb5.pdf: prb5.dvi
	dvipdfmx prb5.dvi
prb5.dvi: prb5.tex prb.eps
	platex prb5.tex
note5.pdf: note5.dvi
	dvipdfmx note5.dvi
note5.dvi: note5.tex fig4.eps fig5.eps fig6.eps fig7.eps fig8.eps fig9.eps fig10.eps fig11.eps fig12.eps fig13.eps
	platex note5.tex
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
fig9.eps: Figs/fig9.svgz
	inkscape -z -f Figs/fig9.svgz -E fig9.eps 
fig10.eps: Figs/fig10.svgz
	inkscape -z -f Figs/fig10.svgz -E fig10.eps 
fig11.eps: Figs/fig11.svgz
	inkscape -z -f Figs/fig11.svgz -E fig11.eps 
fig12.eps: Figs/fig12.svgz
	inkscape -z -f Figs/fig12.svgz -E fig12.eps 
fig13.eps: Figs/fig13.svgz
	inkscape -z -f Figs/fig13.svgz -E fig13.eps 

prb.eps: Figs/prb.svgz
	inkscape -z -f Figs/prb.svgz -E prb.eps 


