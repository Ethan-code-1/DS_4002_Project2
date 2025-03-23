# DS_4002_Project2 (wip)

Authors: Seble Alemu (cnd3ru@virginia.edu), Janna Serrao	(jhs5gq@virginia.edu), Ethan Ogilvie (ebo4dq@virginia.edu)

Project Topic: Predictive Value of PE Ratio on 3,5,10 Year S & P Returns

- Using the Shiller Data daily record of the US Stock market, we examined the potential relationship between PE ratio and stock market annual returns over intervals of multiple years.
<h2>Section 1: Software and Packages</h2>
<b>Software:</b> Rivanna OnDemand or Vscode <br>
<b>Platform:</b> Jupyter Notebook<br>
<b>Packages:</b> you will need to install the following packages if they are not already available
 <table>
  <tr>
    <th>Package</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>numpy</td>
    <td>math operations, store data as an array</td>
  </tr>
  <tr>
    <td>pandas</td>
    <td>clean + process + explore data</td>
  </tr>
   <tr>
    <td>statsmodels</td>
    <td>Form time series models + evaluate time series parameters
</td>
  </tr>
   <tr>
    <td>matplotlib</td>
    <td>create plots</td>
  </tr>
   <tr>
    <td>seaborn</td>
    <td>create plots</td>
  </tr>
   <tr>
    <td>xlrd</td>
    <td>read microsoft excel files</td>
  </tr>
   <tr>
    <td>Skit-learn</td>
    <td>to form predictive model and test it</td>
  </tr>
</table> 

<h2>Section 2: Documentation Tree</h2>

View via <a href = "https://miro.com/app/board/uXjVLk8cn0k=/?share_link_id=967850119871">this link! </a>

<h2>Section 3: Instructions to Reproduce Results</h2>

1. Download Needed Scripts and Data:

Create a folder in your hard drive to store files locally for this project (a suggested folder name is “stock_data”). Once the folder is made, go to the DATA folder of this repository and download the original_data.xls. This data files is modified to already calculate the PE ratio, which is Price/Earnings for a given month. 

  
2. Running the Analysis script.

Go to the SCRIPTS folder from this repository. Download the file [SCRIPTS/final_data_analysis.ipynb] and save to the custom folder you created for this project. Open the file in your choice code editing software (we recommend using Vscode or using UVA Rivanna OnDemand to run Jupyter Notebook). Take note of libraries you may not have installed, they are listed in the first code chunk.  See the table above for the names of the necessary packages to install. Once libraries are installed, run the first code chunk to make sure you have all libraries needed. Before continuing, check the file path assigned to the objects “df.” This is how the script recognizes your dataset. Make sure the filepath matches the path saved locally on your computer. If the script is saved to the same folder as the data files, you should only need to have the string of the filename. Furthermore, scroll to the third code chunk under the section commented as "#Date format is inconsistent so lets make the formatting better and recognized as a date data type." The last parameter of the line sets the Date data type format to recognize the year and month, but this can sometimes bring issues depending on the platform you are using. If you run into errors, remove the format parameter.  After you have checked this, run the next code chunk, as well as the rest of the code chunks in the file. 

As results load, take time to review the comments in the code to understand each step. At the end of the file are the figures, which you can find blown up as individual images in the OUTPUT folder of this repository.


3. Review the Results

You can evaluate the success of your results by checking the figures produced with those stored in the OUTPUT folder. If you are confused by the variables analyzed in the final predictor model results, which only came from review dataset, please check the Data Appendix in the DATA folder.

Questions? Error messages? Concerns? Feel free to contact the authors! Our emails are found at the top of this file.

