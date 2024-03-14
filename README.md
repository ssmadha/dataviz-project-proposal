# Data Visualization Project

## Data

The data I propose to visualize for my project are interactions between different genes highlighting transcript specific differences. This will include transcript expression data as well as an alternative splicing impact factor score. Data and data generation methodology can be found [here](https://github.com/ssmadha/DNA_binding_IF).


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Are there differences in the interaction patterns for specific genes and their specific transcripts between tissues?
 * Does loss of transcription factor (TF) DNA binding domains influence the expression of target genes? Does another TF compensate?
 * Does the ASIF score provide a more nuanced view than expression levels for evaluating TF functionality?

## Sketches

(insert one or more hand-drawn sketches of interactive visualizations that you imagine)
(describe each sketch - how is the data visualized, what are the interactions, and how do these relate to the questions/tasks)

Below is an overall idea. I would like to show an overall network graph displaying protein-protein interactions between genes. The edges are protein-protein interactions would be colored by the ASIF score, which is related to how much the functionality is possible. The nodes are specific transcription factors. Clicking on one node should bring up its DNA-binding targets in a secondary viewpane. Zooming/brushing should zoom on certain parts of the graph of interest.
![Overall_sketch](https://github.com/ssmadha/dataviz-project-proposal/assets/20583362/3c11f670-383e-4c06-a014-a2cfb1509be9)

In the zoomed version (threshold of some arbitrary zoom level), individual transcripts of the genes should show up within their overall gene circles.
![Zoom_sketch](https://github.com/ssmadha/dataviz-project-proposal/assets/20583362/5fc89d3e-311a-442c-ad18-b0b679fc1ca0)

## Prototypes

I’ve created some different types of visualizations of this data. 

This shows the ASIF scores of two tissues on a scatter plot.
[![image](https://github.com/ssmadha/dataviz-project-proposal/assets/20583362/bdb676c6-77f1-4b30-b4cd-fad6102f96ec)](https://vizhub.com/ssmadha/e26f61e5c21f48938f52e71e46d074f7)

This shows a view of multiple scatter plots between different tissues.
[![image](https://github.com/ssmadha/dataviz-project-proposal/assets/20583362/2c5e4a33-32c3-438d-8011-4a4b6ff86c6e)](https://vizhub.com/ssmadha/a192b6d1dacb46ebbaa60da6a2dedf55)

This shows an overall heatmap comparing ASIF scores between tissues.
[![image](https://github.com/ssmadha/dataviz-project-proposal/assets/20583362/b05fb3a0-89a2-4596-b981-e5d9be0f670a)](https://vizhub.com/ssmadha/defb6702cd044d0582851b2ad82f85bb)


## Open Questions

I am not sure how best to visualize a between-tissue comparison. Side-to-side is possible, but maybe some other ways may be easier to interpret?

## Milestones

(for each week, estimate what would be accomplised)
