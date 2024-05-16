1. change the name of "partBrain_*.inp" included in CCI_depth2mm_velo*_pos*_*.inp
2. open .inp file in ABAQUS, enter 'load' module, create new boundary condition for fixed brain region (lower half brain), fix U1.
3. change the velocity in boundary condtion.
4. change time period in step according to velocity. 
5. write new .inp file.
6. change line 7~8 and line 22 in "assembly.inp" for different impact positions.
7. change file name and job name of "CCI_depth2mm_velo*_pos*_*.inp"