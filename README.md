# F1_recompute

## Step followed to evaluate DDP_parsing :

Steps should be followed within the DDP_parsing code (obtained from git repo)

1- Build `stac_test_for_infer.txt` from stac_test.json and save to `data` folder

2- Download model from https://drive.google.com/file/d/1ytLubJSWP1eeZDpQekWkWmJ1D0ODCvou/view and save to `saved_models` folder

3- Run modified `main_infer.py` to get model outputs

4- Run `f1_ddparsing_recompute.ipynb`

For counting variables `cnt_golden`, `cnt_pred` and `cnt_golden` refer to lines 744 to 761 in model.py of Shi and Huang : https://github.com/shizhouxing/DialogueDiscourseParsing/blob/c2f1c43dfb07b62decd8ab8bd05466f46167aed4/Model.py#L510 
