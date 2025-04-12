READ ME.. 
#########################################################################################################
#### X
##### cleaned A1c_dataset_E 
##### shape: (3520, 36)
##### includes:
### IN CASE CSV does not save factors, use these commands
X_factors = ['ALQ111', 'SMQ020', 'DPQ010', 'DPQ040', 'DPQ050', 'DPQ060', 'DMDBORN', 'DMDEDUC', 'DMDMARTX']
X[X_factors] = X[X_factors].astype('category')
###########################################################################################################



  Index(['DR1TKCAL', 'DR1TPROT', 'DR1TCARB', 'DR1TSUGR', 'DR1TFIBE', 'DR1TTFAT',
       'DR1TSFAT', 'DR1TMFAT', 'DR1TPFAT', 'DR1TCHOL', 'DR1TVB12', 'DR1TVC',
       'DR1TMAGN', 'DR1TCAFF', 'DR1TSODI', 'DR1TALCO', 'DR1_320Z', 'DMDBORN',
       'RIDRETH', 'RIAGENDR', 'DMDEDUC', 'DMDMARTX', 'INDFMPIR', 'BPXOSY',
       'BPXODI', 'BMXBMI', 'BMXWAIST', 'ALQ111', 'PAD680', 'PAD790Q', 'SMQ020',
       'SLD012', 'DPQ010', 'DPQ040', 'DPQ050', 'DPQ060'],
      dtype='object')

