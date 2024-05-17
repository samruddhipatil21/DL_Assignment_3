# DL_Assignment_3

**->Running the file:(wandb)**  
1.) To run using wandb kindly comment the code at the end, and uncomment the run_sweep() function and also the sweep config and sweep init line.        
2.) We need to also ucomment the lines in run epochs methods which involve wandb.log and wandb.login right at the start      

**->Running the file:(argparse)**    
1.) To run using wandb kindly comment the code at the end, and uncomment the lines starting from parser=argparse.parser() till the start of run_sweep() function.   
2.) For running the argparse successfully on the localmachine we need to change the path locations in the load data function.

**->Kindly change the path of the dataset in the load data function in order to run the files.**  
Note: To print test result or accuracy kindly print the return values recieved in parameter accu, res  
1.) accu contains the test accuracy given by our model  
2.) res contains all the predicted labels  

## Instructions to run the non_attention file: 
- Run the given file in the sequence order of all the cells.
- Run all the functions in the sequence.
- In last, after the 'main' function, run the cell below it if wanted to run on default configuration for a single run.
- In case, if sweep is required to run, then run the cell with 'sweep_config' dictnionary and then run the cell below it containing sweepid. 
- In order to create the prediction.csv file run the cell with function 'infer' and the one below it to call the 'infer'.
- It would generate a csv file with name 'prediction.csv' which contains Input English word, Output Hindi word & Target Hindi word in separate columns for all the test dataset words. 



## Instructions to run the attention file:
- Run the given file in the sequence order of all the cells.
- Run all the functions in the sequence.
- In last, after the 'main' function, run the cell below it if wanted to run on default configuration for a single run.
- In case, if sweep is required to run, then run the cell with 'sweep_config_attn' dictnionary and then run the cell below it containing sweepid. 
- In order to create the prediction_attention.csv file run the cell below sweepid cell to call the 'infer'.
- It would generate a csv file with name 'prediction_attention.csv' which contains Input English word, Output Hindi word & Target Hindi word in separate columns for all the test dataset words. 
