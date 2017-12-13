FROM madderle/basic-stack:latest

RUN pip install tweepy pymongo


#Change port to 8888 so dont conflict with other jupyter server for data analysis
CMD jupyter-notebook --no-browser --port 9999 --ip='*' --allow-root
