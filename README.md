# FILTER-MS-DATAFRAME  

Filter MS DataFrame on elements and number of elements.  


Create library of 'accepted' elements/ For example:       d = {'C':0, 'H':0, 'O':0, 'N':0, 'S':0}  
Indicate max elements:                                    if d['C']>0 and d['H']>0 and d['O']<=1 and d['N']<=1 and d['S']<=1 and len(d)==5:  
  
The last condition len(d)==5 indicates that no other elements may be present; only CHONS.  

REMARK: The directory d should always start with double string elements such as Cl, Br, Si, followed by single string elements suchs as C, H, N, etc.  
Example: d = {'Cl':0, 'Br':0, 'C':0, 'H':0}  


