# taildir

## Requirements

- inotifywait

On ubuntu install with

```sh
sudo apt-get install inotify-tools
```

## Usage

Example:

$ `taildir /var/logs/ | grep -iP '(error|fatal|critical)'`