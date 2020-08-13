From  python:2.7-slim   
WORKDIR  /app
ADD ./src/app.py  /app     
RUN pip  install -r  requirements.txt        
EXPOSE 80                         
ENV  NAME World                
CMD["python","app.py"]         
