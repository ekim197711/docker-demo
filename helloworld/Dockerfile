FROM alpine
WORKDIR /my_application
RUN touch myfile.txt ; \
touch otherfile.txt
COPY echo_hello_once.sh myapp.sh
ENTRYPOINT [ "sh", "-c", "/my_application/myapp.sh"]