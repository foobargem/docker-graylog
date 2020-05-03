# docker-graylog

## How to use

* clone
    ```
    $ git clone https://github.com/foobargem/docker-graylog.git
    $ cd docker-graylog
    ```

* edit docker-compose.yml
    ```
    $ cp docker-compose.yml.example docker-compose.yml
    ```
    * replace `GRAYLOG_HTTP_EXTERNAL_URI`

* run
    ```
    $ docker-compose up -d
    ```
