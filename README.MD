# License plate recognition 🔎
### EASYOCR 
I've used easyocr library on English and Persian license plates and handwritings.  
You can see the result in easyocr.ipynb file.  
### DTRB
As you see, the results of easyocr are not desirable, so I used this repository  
https://github.com/clovaai/deep-text-recognition-benchmark instead to get better results for recognizing license plates  
  
|Iteration| Train loss | Valid loss | Best accuracy |
|---------| -------- | --------     | -------- |
|4500|   0.008   |0.53        | 80.662 |



### Dataset  
The data of this repository https://github.com/mut-deep/IR-LPR is used for training and validation  

### Usage  
1 - Run DTRB.ipynb file to get the best model   
2 - Put your images in demo_image folder and run the Test cell to test the model  

## Result of DTRB  
<table>
  <tr>
    <td><img src="test_images\lp1.jpg" alt="Image 1"></td>
    <td><img src="test_images\lp2.jpg" alt="Image 2"></td>
    <td><img src="test_images\lp3.jpg" alt="Image 3"></td>
    <td><img src="test_images\lp4.jpg" alt="Image 4"></td>
    <td><img src="test_images\lp5.jpg" alt="Image 5"></td>
  </tr>
  <tr>
    <td>71q14712 </td>
    <td>48q69342</td>
    <td>57u82374</td>
    <td>66l16773 </td>
    <td>73v96442 </td>
  </tr>
   <tr>
    <td>q = ق </td>
    <td>q = ق</td>
    <td>u = ص</td>
    <td>l = ل</td>
    <td>v = و</td>
  </tr>
</table>








