FROM python
RUN pip install flask
COPY  ./static /home/devasc/MidtermProject_G12/static/
COPY  ./templates /home/devasc/MidtermProject_G12/templates/
COPY  test1.py /home/devasc/MidtermProject_G12/
EXPOSE 8080
CMD python3 /home/devasc/MidtermProject_G12/test1.py
