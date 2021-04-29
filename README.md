# capstone21-1
capstone project

## related privious research paper
https://arxiv.org/pdf/2005.00691.pdf

## paper git hub
https://github.com/wangpf3/Commonsense-Path-Generator

## convei lab modified (trouble shooting version) git hub code
https://github.com/min942773/path_generator

## baseline 
https://github.com/leedhn/capstone21-1/blob/main/baseline_csqa_Roberta.ipynb
+ make baseline with Roberta


## run mnli 
https://github.com/leedhn/capstone21-1/blob/main/run_mnli.ipynb
+ run mnli with question|answer and generated path
+ path generator가 만들어낸 path와 question-answer 페어 간 관련도 측정
+ contradict/ neutral+contradict 이 path에 대해 screening 진행

#### mnli result example
https://github.com/leedhn/capstone21-1/blob/main/except_dump_train_result.csv

## modify pickle file (hidden representation)
https://github.com/leedhn/capstone21-1/blob/main/make_pickle.ipynb
+ contradict -> zero padding
+ contradict -> _isa_ padding
+ contradict&neutral -> zero padding
+ contradict&neutral -> _isa_ padding

## path screening result
![스크린샷 2021-04-12 오후 5 39 54](https://user-images.githubusercontent.com/69630288/116567437-95bc1880-a942-11eb-81ee-36199379d045.png)

유의미한 차이를 발견할 수 없었다.

#### contradiciton_isa
<img width="700" alt="스크린샷 2021-04-29 오전 1 21 35" src="https://user-images.githubusercontent.com/69630288/116567793-e9c6fd00-a942-11eb-8203-f7ea3d7fcb12.png">


#### contradiction_zeros
<img width="700" alt="스크린샷 2021-04-29 오전 1 22 41" src="https://user-images.githubusercontent.com/69630288/116567810-edf31a80-a942-11eb-85bc-a9a0842f5f5a.png">


#### entailment_zeros
<img width="700" alt="스크린샷 2021-04-29 오전 1 23 18" src="https://user-images.githubusercontent.com/69630288/116567817-efbcde00-a942-11eb-9bd5-ca5b869bdff3.png">




## GPT error extended result
<img width="542" alt="스크린샷 2021-04-29 오후 10 54 06" src="https://user-images.githubusercontent.com/69630288/116562189-eaa96000-a93d-11eb-846d-8ac3a4b03b08.png">

## modify dataset 
