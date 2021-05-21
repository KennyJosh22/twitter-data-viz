# Twitter Data Interactive Visualization with Python Plotly

Please open this link to view the interactive plots:
https://nbviewer.jupyter.org/github/KennyJosh22/twitter-data-viz/blob/main/Remesh.ipynb

**Python Version used in the notebook:** Python 3.7.7

**Audience Engagement Definition:**

- Defined by the number of likes for the tweet. I think it makes perfect sense that the audience will engage in the tweets by liking or not liking the tweets. 
- I was thinking on using the number of retweets as well, but I think most accounts do not typically retweet as often as they like tweets.


## Installation


Cloning a github repository into your local machine can be found here [Clone repo](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository#cloning-a-repository-using-the-command-line). 


For a local installation, make sure you have [Python 3.7.7](https://www.python.org/downloads/release/python-377/) installed and run this cmd in your bash/linux terminal:

    $ pip install notebook


## Usage - Running Jupyter notebook

### Running in a local installation

Launch with:

    $ jupyter notebook


Then you can open the Jupyter notebook cloned from this repo and run the cells.




## If you encounter this error when reading json using json.loads

### urllib.error.URLError: <urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1049)>

- If you're using macOS go to Macintosh HD > Applications > Python3.7 folder (or whatever version of python you're using) > double click on "Install Certificates.command" file.



