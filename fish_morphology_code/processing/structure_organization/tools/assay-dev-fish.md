### Global structure organization and local structural alignment features

- `CellId`: Unique id that indentifies the FOV and the cell mask label
- `napariCell_ObjectNumber`: Unique id that indentifies the label of cell segmentation in the fov
- `Age`: Cells age
- `result_image_path`: Z Stack with data produced by assay-dev
- `original_fov_location`: Path to raw data
- `Total_Area`: Number of pixels in cell mask
- `Frac_Area_Background`: Fraction of cell area classified as background
- `Frac_Area_DiffuseOthers`: Fraction of cell area classified as diffuse and others
- `Frac_Area_Fibers`: Fraction of cell area classified as fibers
- `Frac_Area_Disorganized_Puncta`: Fraction of cell area classified as disorganized puncta
- `Frac_Area_Organized_Puncta`: Fraction of cell area classified as organized puncta
- `Frac_Area_Organized_ZDisks`: Fraction of cell area classified as organized z disks
- `Prob_DiffuseOthers`: Average probability of a pixel inside the cell to be classified as diffuse and others
- `Prob_Fibers`: Average probability of a pixel inside the cell to be classified as fibers
- `Prob_Disorganized_Puncta`: Average probability of a pixel inside the cell to be classified as disorganized puncta
- `Prob_Organized_Puncta`: Average probability of a pixel inside the cell to be classified as organized puncta
- `Prob_Organized_ZDisks`: Average probability of a pixel inside the cell to be classified as organized z disks
- `IntensityMedian`: Median of GFP signal in cell mask
- `IntensityIntegrated`: Integrated GFP signal in cell mask
- `IntensityMedianBkgSub`: Median of GFP signal in cell mask with background subtracted (10% percentile
- `IntensityIntegratedBkgSub`: Integrated GFP signal in cell mask with background subtracted (10% percentile
- `Maximum_Coefficient_Variation`: Maximum value of the coefficient of variation obtained from correlation plots
- `Peak_Height`: High of the highest peak in the correlation plots
- `Peak_Distance`: Distance in pixels in which the maximum of the highest peak occurs
- `Peak_Angle`: Angle in degrees for which we observe the highest correlation value