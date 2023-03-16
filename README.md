# nucleolus_paper

 dir structure: nucleolus_paper

- 02featureCounts
	- featureCounts output files
- 03limma
	- DGE and rpkm output files
- R/
	- scripts.Rmd (script)
	- scripts.pdf (md script with embedded figures for easy viewing)
	- folders_for_figures
- sample_info
	- metadata tables in csv format for loading into R


scripts and the files they produce:

- ASC_TIMEcourse_limma_plusDay15_nucleolus_analysis_2023.Rmd
	- -> adipogenesis_rpkm_tmm.tab
	- -> adipogenesis_rpkm_tmm_means.tab
	- -> nucleolus_adipogenesis_DE.tab
- native_late_adipoDE_2023.Rmd
	- -> day15_bulk.v.float.tab
- ribosome_heatmaps_adipogenesis.Rmd
	- ribosome_heatmaps_adipogenesis\Figure3a_lower-1.pdf
	- ribosome_heatmaps_adipogenesis\Figure3a_upper-1.pdf
	- ribosome_heatmaps_adipogenesis\FigureS6a_lower-1.pdf
	- ribosome_heatmaps_adipogenesis\FigureS6a_upper-1.pdf

