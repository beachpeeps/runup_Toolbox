# runup_Toolbox

Based on the CIRN runup toolbox, ARGUS_runup_wrapper_code.m checks what timestacks still need to be processed and uses the toolbox GUI to extract the horizontal extent of the runup line. A first check is if the shoreline can be seen in the timestack image. If 'Yes' at prompt, the GUI is launched. It determines a first pass at the runup line, and the edit button can be used to interpolate over bad areas (right click when you have finished clicking - each time you 'edit' is a stand-alone process so if you mess up just 'edit' again). Once you have gone down the full image, click 'save' and 'quit' and it will move on to the next timestack. 

Currently the 10Hz timestacks are subsampled at 2Hz because the timestacks have been extracted. 2Hz results need an extra preprocessing step to generate timestacks from the full grid (still TBD).
