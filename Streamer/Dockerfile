FROM madderle/basestack:latest

RUN pip install tweepy
RUN pip install pymongo

#Change port to 8888 so dont conflict with other jupyter server for data analysis
CMD jupyter-notebook --no-browser --port 9999 --ip='*' --allow-root
