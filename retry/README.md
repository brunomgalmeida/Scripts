# retry

retries the command for **N** times, waiting for **S**s between each retry.
Default delay is 1s.

## Usage

$ `retry 3 lsa`

Repeat the execution of the command `lsa` up to 3 times

$ `retry 3 10 lsb`

Repeat the execution of the command `lsa` up to 3 times, but waits 10s between each attempt.
