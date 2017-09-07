FROM percona:5.7
RUN apt-get update && apt-get install -y --no-install-recommends python python-mysqldb && rm -rf /var/lib/apt/lists/*
CMD ["mysqld"]