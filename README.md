# **chinese_pdf_divider**

Package url in pypi: https://pypi.org/project/chinese-pdf-divider/  

## **Parameter and output**

### Input: 
* **filename**: the path of file which you want to divide.
* **remove_b_list**: default is 'False' whan you are not dividing csr report. If you are dividing csr report, change to 'True'. 
* **output_path**: default is the path of input file.

### Output: 
* Output filename: {filename}_divided.csv
* If successfully divide, print {filename} finished dividing in terminal

## **How to use**
1. Download the package
    <pre><code>pip install chinese_pdf_divider</code></pre>
2. Import it
    <pre><code>from chinese_pdf_divider.pdf_divider import pdf_divider</code></pre>
3. Use it
    <pre><code>pdf_divider('OOO.pdf')</code></pre>