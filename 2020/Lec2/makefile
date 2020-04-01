note2.pdf: note2.dvi
	dvipdfmx note2.dvi
note2.dvi: note2.tex fig1.eps fig2.eps fig3.eps fig4.eps
	platex note2.tex
fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps 
fig2.eps: fig2.svgz
	inkscape -z -f fig2.svgz -E fig2.eps 
fig3.eps: fig3.svgz
	inkscape -z -f fig3.svgz -E fig3.eps 
fig4.eps: fig4.svgz
	inkscape -z -f fig4.svgz -E fig4.eps 
#fig5.eps: fig5.svgz
#	inkscape -z -f fig5.svgz -E fig5.eps 
#fig6.eps: fig6.svgz
#	inkscape -z -f fig6.svgz -E fig6.eps 
#fig7.eps: fig7.svgz
#	inkscape -z -f fig7.svgz -E fig7.eps 
#fig8.eps: fig8.svgz
#	inkscape -z -f fig8.svgz -E fig8.eps 


