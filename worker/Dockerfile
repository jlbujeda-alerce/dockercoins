FROM python:3.7@sha256:73a597b7d59365de6744ba4d92876915e9da127334c1fc713f45a1eb704f0d69

RUN pip install redis
RUN pip install requests

FROM scratch

COPY --from=0 / /
