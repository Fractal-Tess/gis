# Research "WhiteBox GAT"

Whitebox Geospatial Analysis Tools (GAT) is a cross-platform, open-source Geographic Information System (GIS) and remote sensing software package designed for geospatial analysis and data visualization in research and education[^1]. It is developed by members of the University of Guelph Centre for Hydrogeomatics[^1]. Whitebox GAT was initially created as a replacement for the Terrain Analysis System (TAS)[^1].

**Core Functionalities**

- **Analysis Tools:** Whitebox GAT has more than 385 tools for spatial analysis of raster data sets, including cost-distance analysis, buffering, distance operations, weighted overlays, and more[^1]. It is especially good at LiDAR, image processing, and hydrological analysis[^2].
- **Hydrology Tools:** Includes DEM preprocessing, flow direction and accumulation, watershed extraction, and mass flux analysis[^1]. It has been fine-tuned for hydro-geomorphic applications, such as modeling surface drainage patterns, delineating watersheds, and analyzing stream networks[^2].
- **Terrain Analysis Tools:** Capabilities include surface derivatives (slope, aspect, and curvatures), hillshading, wetness index, and relative stream power index[^1].
- **LiDAR Tools:** For editing and viewing LiDAR data, including converting LAS to shapefiles, displaying LiDAR point clouds, creating LiDAR footprints, and interpolating LiDAR into DEM or DSM[^2].
- **Image Processing Tools:** Offers k-means classification, spatial filters, image mosaicing, NDVI, resampling, contrast enhancement, multi-spectral data analysis, classification, and change detection[^1][^4].

**Ease of Use and Learning Curve**

Whitebox GAT is often praised for its consistent design and ease of use[^3]. Its simple and intuitive interface makes it suitable for performing quick analyses, even for users with limited GIS experience[^5]. The toolbar and menu structures are designed for simplicity, with most tools accessed through a toolbox "treeview" structure[^4].

**Data Formats Supported**

The software supports both raster and vector (shapefile) data structures. It also offers extensive functionality for processing laser scanner (LiDAR) data containing LAS files[^1].

**Scalability and Performance**

Whitebox GAT is designed to process large raster datasets[^4]. Several tools use algorithms that perform parallel processing to improve the performance of computationally intensive tasks[^4]. It has been used to process large digital elevation models containing over one billion grid cells[^4].

**Integration Capabilities**

Whitebox GAT is extendable, allowing users to create and add custom tools or plugins using any JVM language[^1]. It also supports scripting using Groovy, JavaScript, and Python[^1]. Plugins can be called from scripts to carry out advanced geoprocessing workflows and task automation[^4].

**Pricing and Licensing**

Whitebox GAT is distributed under the GNU General Public License, making it an open-source software package[^1]. As such, it is available for free[^7].

**Community and Support**

The Whitebox GAT project was initiated as a replacement for the Terrain Analysis System (TAS)[^1]. The software has been translated into 11 languages, with over 21,000 downloads[^2]. Users can request new tools or features via the GitHub repository[^3].

<div style="text-align: center">⁂</div>

[^1]: https://en.wikipedia.org/wiki/Whitebox_Geospatial_Analysis_Tools
[^2]: https://gisgeography.com/whitebox-gat-geospatial-analysis-toolbox/
[^3]: https://www.whiteboxgeo.com/manual/wbt_book/faq.html
[^4]: https://www.gla.ac.uk/media/Media_401757_smxx.pdf
[^5]: https://cdn.serc.carleton.edu/files/NAGTWorkshops/structure/activities/whitebox_gat_tutorial.pdf
[^6]: https://www.youtube.com/watch?v=xvCF71n5tXQ
[^7]: https://gis.stackexchange.com/questions/162299/cost-distance-analysis-with-whitebox-or-other-open-source-gis-software
[^8]: https://jblindsay.github.io/ghrg/Whitebox/
[^9]: https://www.whiteboxgeo.com/manual/wbt_book/intro.html
[^10]: https://www.maplibrary.org/825/best-lidar-data-processing-software-for-terrain-mapping/
[^11]: https://whiteboxr.gishub.org/articles/datasets.html
[^12]: https://www.whiteboxgeo.com
[^13]: https://www.whiteboxgeo.com/geospatial-software/
[^14]: https://blog.gishub.org/whitebox-tutorial
[^15]: https://www.researchgate.net/publication/271205138_The_Whitebox_Geospatial_Analysis_Tools_project_and_open-access_GIS
[^16]: https://www.researchgate.net/profile/John-Lindsay-5/publication/323547863_WhiteboxTools_User_Manual/links/5f569c41299bf13a31aaef0c/WhiteboxTools-User-Manual.pdf
[^17]: https://github.com/jblindsay/whitebox-tools
[^18]: https://www.whiteboxgeo.com/manual/wbt_book/intro.html
[^19]: https://www.researchgate.net/publication/305113628_Whitebox_GAT_A_case_study_in_geomorphometric_analysis
[^20]: https://www.whiteboxgeo.com
[^21]: https://www.youtube.com/watch?v=_03vZLShcbc
[^22]: https://dl.acm.org/doi/abs/10.1016/j.cageo.2016.07.003
[^23]: https://www.researchgate.net/figure/Whitebox-GAT-Graphic-User-Interface-showing-eleven-tools-categories-source_fig2_260182301
[^24]: https://atlas.co/blog/top-10-free-gis-software/
[^25]: https://www.researchgate.net/figure/Whitebox-GAT-Graphic-User-Interface_fig2_260182627
[^26]: https://colab.research.google.com/github/giswqs/whitebox-python/blob/master/examples/whitebox.ipynb
[^27]: https://gis.stackexchange.com/questions/tagged/whitebox-gat
[^28]: https://sourceforge.net/projects/whiteboxgat/
[^29]: https://jblindsay.github.io/ghrg/Whitebox/Help/FileFormatsDescriptions.html
[^30]: https://jblindsay.github.io/ghrg/Whitebox/
[^31]: https://whiteboxr.gishub.org/articles/demo.html
[^32]: https://gis.stackexchange.com/questions/208404/exporting-a-whitebox-gat-raster-to-geotiff-format
[^33]: https://jblindsay.github.io/ghrg/Whitebox/Help/MainHelp.html
[^34]: https://cran.r-project.org/web/packages/whitebox/readme/README.html
[^35]: https://www.whiteboxgeo.com/manual/wbt_book/limitations.html
[^36]: https://pypi.org/project/whitebox/
[^37]: https://whiteboxr.gishub.org/articles/datasets.html
[^38]: https://www.youtube.com/watch?v=xvCF71n5tXQ
[^39]: https://www.whiteboxgeo.com/manual/wbt_book/faq.html
[^40]: https://www.reddit.com/r/gis/comments/16s32ze/should_i_try_whitebox_tools/
[^41]: https://gis.stackexchange.com/questions/156293/how-to-run-a-tool-from-whitebox-gat-in-arcgis
[^42]: https://www.researchgate.net/post/Whitebox-GAT-working-with-big-data
[^43]: https://arxiv.org/abs/2204.00103
[^44]: https://whiteboxr.gishub.org
[^45]: https://www.youtube.com/watch?v=1pUDBuwp1QY
[^46]: https://www.whiteboxgeo.com/manual/wbt_book/qgis_plugin.html
[^47]: https://github.com/ContinuumIO/whitebox-geospatial-analysis-tools
[^48]: https://gis.stackexchange.com/questions/18568/integrating-whitebox-gat-free-and-open-with-arcmap-ui
[^49]: https://wiki.openjdk.org/spaces/flyingpdf/pdfpageexport.action?pageId=25755682
[^50]: https://plugins.qgis.org/plugins/wbt_for_qgis/
[^51]: https://github.com/opengeos/whitebox-python
[^52]: https://portal.opentopography.org/tools/viewTool?toolId=561
[^53]: https://jblindsay.github.io/ghrg/Whitebox/Help/LeastCostAnalysis.html
[^54]: https://groups.google.com/g/whiteboxtools/c/cYvvSiJEPp4
[^55]: https://jblindsay.github.io/WhiteboxTutorials/LCPAnalysis/lcpa.html
[^56]: https://www.whiteboxgeo.com/download-whiteboxtools/
[^57]: https://www.whiteboxgeo.com/wbw-purchase/
[^58]: https://github.com/opengeos/WhiteboxTools-ArcGIS
[^59]: https://gisgeography.com/whitebox-gat-geospatial-analysis-toolbox/
[^60]: https://github.com/cryptolu/whitebox/blob/master/LICENSE.md
[^61]: https://gis.stackexchange.com/questions/428907/map-gully-depth-for-ditches-extraction-whitebox
[^62]: https://groups.google.com/g/whiteboxtools
[^63]: https://www.whiteboxgeo.com/manual/wbt_book/install.html
[^64]: https://whitebox.readthedocs.io/_/downloads/en/latest/pdf/
[^65]: https://gis.stackexchange.com/questions/tagged/whitebox-tools
[^66]: https://groups.google.com/g/whiteboxtools/c/cYvvSiJEPp4/m/UdUiNDAkCQAJ
[^67]: https://www.reddit.com/r/gis/comments/xe1ulb/whitebox_workflows_for_python/
[^68]: https://www.geo.uzh.ch/en/units/h2k/Services/Whitebox-GAT.html
[^69]: https://jblindsay.github.io/ghrg/Whitebox/Help/Welcome.html
[^70]: https://gisday.wordpress.com/2014/10/28/convert-rasters-between-whitebox-gat-and-arcgis/
[^71]: https://github.com/jblindsay/whitebox-tools/blob/master/tool_porting.md
[^72]: https://www.whiteboxgeo.com/manual/wbt_book/supported_formats.html
[^73]: https://www.gla.ac.uk/media/Media_401757_smxx.pdf
[^74]: https://en.wikipedia.org/wiki/Whitebox_Geospatial_Analysis_Tools
[^75]: https://github.com/jblindsay/whitebox-tools/issues/123
[^76]: https://jblindsay.github.io/ghrg/pubs/2016_Lindsay_CGSc.pdf
[^77]: https://gis.stackexchange.com/questions/108950/adding-a-new-tool-plugin-to-whitebox-gat-anyone-else-have-trouble
[^78]: https://github.com/serkan-ozal/whitebox
[^79]: https://www.whiteboxgeo.com/extension-pricing/
[^80]: https://gis.stackexchange.com/questions/162299/cost-distance-analysis-with-whitebox-or-other-open-source-gis-software
