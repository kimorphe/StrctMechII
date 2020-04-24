all: note3.pdf prb3.pdf

note3.pdf: note3.dvi
	dvipdfmx note3.dvi
note3.dvi: note3.tex fig5.eps fig6.eps fig7.eps fig8.eps fig3.eps \
	fig6_1.eps fig6_2.eps fig8_1.eps fig8_2.eps fig7_1.eps \
	fig9.eps fig10.eps fig11.eps fig12.eps
	platex note3.tex

prb3.pdf: prb3.dvi
	dvipdfmx prb3.dvi
prb3.dvi: prb3.tex prb.eps
	platex prb3.tex


prb.eps: Figs/prb.svgz
	inkscape -z -f Figs/prb.svgz -E prb.eps 
fig3.eps: Figs/fig3.svgz
	inkscape -z -f Figs/fig3.svgz -E fig3.eps 
fig5.eps: Figs/fig5.svgz
	inkscape -z -f Figs/fig5.svgz -E fig5.eps 
fig6.eps: Figs/fig6.svgz
	inkscape -z -f Figs/fig6.svgz -E fig6.eps 
fig6_1.eps: Figs/fig6_1.svgz
	inkscape -z -f Figs/fig6_1.svgz -E fig6_1.eps 
fig6_2.eps: Figs/fig6_2.svgz
	inkscape -z -f Figs/fig6_2.svgz -E fig6_2.eps 
fig7.eps: Figs/fig7.svgz
	inkscape -z -f Figs/fig7.svgz -E fig7.eps 
fig7_1.eps: Figs/fig7_1.svgz
	inkscape -z -f Figs/fig7_1.svgz -E fig7_1.eps 
fig8_1.eps: Figs/fig8_1.svgz
	inkscape -z -f Figs/fig8_1.svgz -E fig8_1.eps 
fig8_2.eps: Figs/fig8_2.svgz
	inkscape -z -f Figs/fig8_2.svgz -E fig8_2.eps 

fig9.eps: Figs/fig9.svgz
	inkscape -z -f Figs/fig9.svgz -E fig9.eps 
fig10.eps: Figs/fig10.svgz
	inkscape -z -f Figs/fig10.svgz -E fig10.eps 
fig11.eps: Figs/fig11.svgz
	inkscape -z -f Figs/fig11.svgz -E fig11.eps 
fig12.eps: Figs/fig12.svgz
	inkscape -z -f Figs/fig12.svgz -E fig12.eps 
