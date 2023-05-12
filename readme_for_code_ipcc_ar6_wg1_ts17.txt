##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is R code to produce IPCC AR6 WGI Figure 17
# Creator: Sönke Zaehle, Max Planck Institute for Biogeochemistry, Jena, Germany
# Contact: szaehle@bgc-jena.mpg.de 
# Last updated on: April 8th, 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: Plotting_Script.R: This script plots the climate feedback parameters for various feedbacks by several publications in the peer-reviewed literature, as derived in Chapter 5-7, AR6 WG1. All feedback parameters are read from files deposited on CEDA as Zaehle, S.; Naik, V.; Lunt, D. (9999): Technical Summary of the Working Group I Contribution to the IPCC Sixth Assessment Report - data for Figure TS.17 (v20221111). NERC EDS Centre for Environmental Data Analysis, date of citation. https://catalogue.ceda.ac.uk/uuid/c0d4d44aca4e490086df7e5f8f4463a3
# - Input data: files containing data for Panel a-c (panel_a.csv, panel_b.csv, panel_c.csv, 
# - Output variables: none
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: v1
# - Landing page to access the software: dot:10.5281/zenodo.7575605 
# - Operating System: Tested on MacOS, should run on Linux, Windows.
# - Environment required to compile and run: R 
#  ----------------------------------------------------------------------------------------------------
#
#  License: Apache 2.0
# ----------------------------------------------------------------------------------------------------
# How to cite: Zaehle (2021): Technical Summary of the Working Group I Contribution to the IPCC Sixth Assessment Report - plotting script for Figure TS.17 (this DOI, date of citation)
#
# When citing this code, please include both the code citation and the following citation for the related report component:
When citing this dataset, please include both the data citation below (under 'Citable as') and the following citation for the report component from which the figure originates:
Arias, P.A., N. Bellouin, E. Coppola, R.G. Jones, G. Krinner, J. Marotzke, V. Naik, M.D. Palmer, G.-K. Plattner, J. Rogelj, M. Rojas, J. Sillmann, T. Storelvmo, P.W. Thorne, B. Trewin, K. Achuta Rao, B. Adhikary, R.P. Allan, K. Armour, G. Bala, R. Barimalala, S. Berger, J.G. Canadell, C. Cassou, A. Cherchi, W. Collins, W.D. Collins, S.L. Connors, S. Corti, F. Cruz, F.J. Dentener, C. Dereczynski, A. Di Luca, A. Diongue Niang, F.J. Doblas-Reyes, A. Dosio, H. Douville, F. Engelbrecht, V. Eyring, E. Fischer, P. Forster, B. Fox-Kemper, J.S. Fuglestvedt, J.C. Fyfe, N.P. Gillett, L. Goldfarb, I. Gorodetskaya, J.M. Gutierrez, R. Hamdi, E. Hawkins, H.T. Hewitt, P. Hope, A.S. Islam, C. Jones, D.S. Kaufman, R.E. Kopp, Y. Kosaka, J. Kossin, S. Krakovska, J.-Y. Lee, J. Li, T. Mauritsen, T.K. Maycock, M. Meinshausen, S.-K. Min, P.M.S. Monteiro, T. Ngo-Duc, F. Otto, I. Pinto, A. Pirani, K. Raghavan, R. Ranasinghe, A.C. Ruane, L. Ruiz, J.-B. Sallée, B.H. Samset, S. Sathyendranath, S.I. Seneviratne, A.A. Sörensson, S. Szopa, I. Takayabu, A.-M. Tréguier, B. van den Hurk, R. Vautard, K. von Schuckmann, S. Zaehle, X. Zhang, and K. Zickfeld, 2021: Technical Summary. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 33−144, doi:10.1017/9781009157896.002.

Zaehle, S.; Naik, V.; Lunt, D. (9999): Technical Summary of the Working Group I Contribution to the IPCC Sixth Assessment Report - data for Figure TS.17 (v20221111). NERC EDS Centre for Environmental Data Analysis, date of citation. https://catalogue.ceda.ac.uk/uuid/c0d4d44aca4e490086df7e5f8f4463a3

########################################################################