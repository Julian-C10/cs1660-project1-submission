FROM asap397/git
WORKDIR /app 
COPY requirements.txt /app
RUN pip3 install -r requirements.txt --no-cache-dir
#RUN apt-get install -y xterm
COPY . /app 
ENTRYPOINT ["python3"] 
CMD ["app.py"]
