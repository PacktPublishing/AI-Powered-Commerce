# AI-Powered Commerce 

<a href="https://www.packtpub.com/data/ai-powered-commerce?utm_source=github&utm_medium=repository&utm_campaign=9781803248981"><img src="https://static.packt-cdn.com/products/9781803248981/cover/smaller" alt="AI-Powered Commerce " height="256px" align="right"></a>

This is the code repository for [AI-Powered Commerce ](https://www.packtpub.com/data/ai-powered-commerce?utm_source=github&utm_medium=repository&utm_campaign=9781803248981), published by Packt.

**Building the products and services of the future with Commerce.AI**

## What is this book about?
Commerce.AI is a suite of artificial intelligence (AI) tools for commerce, trained on over a trillion data points, to help brands build next-gen products. If you want to be the best commerce player on the block, using AI is a must. 

This book covers the following exciting features:
- Find out how machine learning can help you identify new market opportunities.
- Understand how to use consumer data to create new products and services.
- Use state-of-the-art AI frameworks and tools for data analysis.
- Launch, track, and improve products and services with AI.
- Rise above the competition with unparalleled insights from AI.
- Turn customer touchpoints into business wins.
- Generate high-conversion product and service copy.

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/180324898X) today!


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
s = df['Reviews']
df['Reviews'] = df['Reviews'].astype(str)
df = df[df['Reviews'] == s]
df[['polarity', 'subjectivity']] = df['Reviews'].apply(lambda Text: pd.Series(TextBlob(Text).sentiment))
```

**Following is what you need for this book:**
This AI book is for AI developers, data scientists, data product managers, analysts, and consumer insights professionals. The book will guide you through the process of product and service innovation, no matter your pre-existing skillset.

With the following software and hardware list you can run all code files present in the book (Chapter 1-12).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 3, 4, 5, 8 | Python, Jupyter Notebook | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781803248981_ColorImages.pdf).

### Related products
* Learn Amazon SageMaker - Second Edition  [[Packt]](https://www.packtpub.com/product/learn-amazon-sagemaker-second-edition/9781801817950?utm_source=github&utm_medium=repository&utm_campaign=9781801817950) [[Amazon]](https://www.amazon.com/Learn-Amazon-SageMaker-developers-scientists-dp-1801817952/dp/1801817952/ref=mt_other?_encoding=UTF8&me=&qid=)

* IBM Cloud Pak for Data  [[Packt]](https://www.packtpub.com/product/ibm-cloud-pak-for-data/9781800562127?utm_source=github&utm_medium=repository&utm_campaign=9781800562127) [[Amazon]](https://www.amazon.com/dp/1800562128)



## Get to Know the Author
**Andy Pandharikar**
is the CEO and founder of Commerce.AI. His previous start-up was acquired by the Flipkart group, which later was acquired by Walmart for $16B. Prior to that, Andy held various product and engineering positions at Cisco. He has an M.S. in management science and engineering from Stanford University and has an executive degree from Harvard Business School.

**Frederik Bussler**
 is a consultant and analyst, with experience across innovative AI platforms such as Commerce.AI, Obviously.AI, and Apteo, as well as investment offices such as Supercap Digital, Maven 11 Capital, and Invictus Capital. He has featured in Forbes, Yahoo, and other outlets, and has presented for audiences including IBM and Nikkei.

