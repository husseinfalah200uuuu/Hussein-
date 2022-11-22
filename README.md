FROM husseinfalah200uuuu/husseinfalah200uuuu:slim-buster

#clonning repo 

RUN git clone https://github.com/husseinfalah200uuuu/Hussein-

#working directory 

WORKDIR /root/husseinfalah200uuuu

# Install requirements

RUN pip3 install --no-cache-dir -r requirements.txt

ENV PATH="/home/husseinfalah200uuuu/bin:$PATH"

CMD ["python3","-m","husseinfalah200uuuu"]
