FROM python:3.6.4-alpine

LABEL io.whalebrew.name 'yapf'
LABEL io.whalebrew.config.working_dir '/workdir'
WORKDIR /workdir

RUN pip install yapf==0.20.1

ENTRYPOINT ["yapf"]
CMD ["--help"]
