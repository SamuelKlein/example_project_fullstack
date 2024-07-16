FROM python:3

RUN useradd -ms /bin/bash python

USER python

# CMD [ "tail", "-f", "/dev/null" ]

WORKDIR /home/python

CMD ["sh", "/home/python/backend/start.sh"]