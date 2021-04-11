FROM postgres
ARG username=postgres
ARG dbname=postgres
ARG password=password
COPY . ./
RUN psql -U ${username} -d ${postgres} -a -f ./dummy.sql
CMD [ "executable" ]

#docker run -p ?:5432 -v /Volumes/4tdisk/weport-dev/data:/var/lib/postgresql/data --name postgres -e POSTGRES_PASSWORD=1q2w3e4r -d postgres