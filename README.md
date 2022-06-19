# OCDViT
Oral Cancer Detection using Vision Transformer


Oral lesions are mouth ulcers or sores, which may be painful. They can include abnormal cell 
growth and rare tongue and hard-palate (roof of mouth) disorders. These can be caused due to 
an array of reasons, ranging from, infections, blisters, fever or is manifested as a form of oral 
cancer. This research will revolve around the onset of oral lesions caused due to cancer.

Oral cancer is cancer that develops in the tissues of the mouth or throat. Most develop in the 
squamous cells found in your mouth, tongue, and lips. It is a commonly found form of cancer, 
affecting almost 1 in every 60 men. It is also one of the most commonly found cancers in India 
which contributes to one-fourth of the total indices. Many a times the cancer might manifest in 
the form of “oral lesions”, as mentioned above.

Due to the widespread nature or oral cancer in India as well as worldwide, cancerous oral 
lesions require a rigorous treatment procedure, carried out in time to prevent it from being fatal. 
This is where the need for the project stems from. Automating the procedure to detect cancerous 
lesions and classify them according to their stage can prove to be an immense boost to the 
research and solution to dealing with oral cancer. The machine trained to a suitable accuracy
will not only save time by computing information and imaging much faster than an individual, 
but also eliminate the margin of human error, so as to provide near perfect accuracy every time. 

The project uses Vision Transformers (ViT), as the primary model that is trained on the 
provided dataset, with a comparative study of other image classification methods to show the 
difference in accuracy between all the methods, so as to select an optimal best methodology to 
go forward researching for the classification of oral lesions. The disparity on a pure transformer 
is to marry a transformer to a CNN front end. The usual ViT stem leverages a 16*16 
convolution with a 16 stride
CNN turns basic pixels into a feature map. Later, the feature map is translated by a tokenizer 
into a sequence of tokens that are then inputted into the transformer. The transformer then 
applies the attention technique to create a sequence of output tokens. Eventually, a projector 
reconnects the output tokens to the feature map.

The results (prediction accuracy) that was obtained for the vision transformer and other 
methods in the comparative study are as follows:
● ViT: 98.8 percent accuracy of 5 epochs
