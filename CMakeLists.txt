PROJECT(structured-prediction-problem-archive NONE)
cmake_minimum_required(VERSION 2.8)
SET(LATEX_OUTPUT_PATH build)
INCLUDE(UseLATEX.cmake)

add_latex_document(main.tex
    INPUTS 
    introduction.tex 
    mrf.tex 
    figures/grid-mrf.tex
    multicut.tex 
    figures/multicut.tex 
    lifted-multicut.tex
    figures/lifted-multicut-1.tex
    figures/lifted-multicut-2.tex
    asymmetric-multiway-cut.tex
    figures/asymmetric-multiway-cut.tex
    lifted-disjoint-paths.tex
    figures/lifted-disjoint-paths.tex
    figures/graph-matching.tex
    graph-matching.tex
    multi-graph-matching.tex
    cell-tracking.tex
    shape-matching.tex
    discrete-tomography.tex
    bottleneck-mrf.tex
    BIBFILES literature.bib
    IMAGE_DIRS images
    )
