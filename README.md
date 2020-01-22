# httplogger
simple php server writing logs received via HTTP GET to error_log

## Usage

1. Start the server usng `run.sh`
2. Include HTTP GET calls to the code you want to instrument with the URL `http://127.0.0.1:8888/log.php?message=yourfancylogmessage`
