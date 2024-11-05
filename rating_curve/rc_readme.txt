Cite the data and article as Patidar et al., 2024: Patidar, G., Indu, J. & Karmakar, S. ExtendinG SUb-DAily River Discharge data over INdia (GUARDIAN). Sci Data 11, 1155 (2024). https://doi.org/10.1038/s41597-024-03923-8

Here are the details of the different columns in the RC file

file_name: the file name of the station
N_m: number of data used to generate monsoon RC
NSE_m: NSE value during validation of monsoon discharge
RMSE_m: RMSE value during validation of monsoon discharge

algo_m: which algorithm is used to generate monsoon discharge, 1 (represents poly 2), 2(represents cubic)
m_poly_(p1,p2,p3): represents coefficient for poly2 algorithm for monsoon discharge
m_n3_(p1,p2): represents coefficient for cubic algorithm for monsoon discharge

N_nm: number of data used to generate non-monsoon RC
NSE_nm: NSE value during validation of non-monsoon discharge
RMSE_nm: RMSE value during validation of non-monsoon discharge

algo_nm: which algorithm is used to generate non-monsoon discharge, 1 (represents poly 2), 2(represents cubic)
nm_poly_(p1,p2,p3): represents coefficient for poly2 algorithm for non-monsoon discharge
nm_n3_(p1,p2): represents coefficient for cubic algorithm for non-monsoon discharge

name: CWC station name
lat: latitude
lon: longitude
