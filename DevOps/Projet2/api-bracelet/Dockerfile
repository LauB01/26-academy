FROM python:3

ADD __main__.py /

RUN pip install pystrich

RUN touche requirements.txt

CMD [ "python", "./__main__.py" ]
