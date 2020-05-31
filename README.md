# Understanding_Ethereum_via_Graph_Analysis_TOIT

The files stores the data to construct the graph in paper.

After compress the basic graph edge data, the size is over 8GB. While it is over 20GB without compression.
So we upload the basic graph edge data to Baidu Cloud, and you can get data by this URL https://pan.baidu.com/s/1w2B-zeK1CT8hIPy0p-swXg, 
and the password is n3x0.
No password for compression, if this URL is disabled, please contact us.

The subfolders are stored in 'net.zip' file that name one, two, and three is the alias for MFG, CCG, and CIG.
There are 39 files in each subfolder that results corresponding to the graph edge data in each checkpoint.
In the edge data files, data format is 'fromaddress#toaddress#weight' in every line.
To decrease the size for these edge data files, we replace the ethereum address with serial number and store the mapping information in alladdress which is compressed as 'alladdress.zip', you can understand the data format  in easily.

If you use this data and/or code, please cite the following paper. Thanks!

 
Ting Chen, Zihao Li, Yuxiao Zhu, Jiachi Chen, Xiapu Luo, John Chi-Shing Lui, Xiaodong Lin, Xiaosong Zhang, "Understanding Ethereum via GraphAnalysis", ACM Transactions on Internet Technology (TOIT) 20.2 (2020): 1-32.

@article{chen2020understanding,
  title={Understanding Ethereum via Graph Analysis},
  author={Chen, Ting and Li, Zihao and Zhu, Yuxiao and Chen, Jiachi and Luo, Xiapu and Lui, John Chi-Shing and Lin, Xiaodong and Zhang, Xiaosong},
  journal={ACM Transactions on Internet Technology (TOIT)},
  volume={20},
  number={2},
  pages={1--32},
  year={2020},
  publisher={ACM New York, NY, USA}
}
