﻿
## Examples

```
kafkescli --help
kafkescli consume --help
kafkescli consume hello
kafkescli produce hello world
kafkescli produce hello "world of cli kafka"
echo "hello world of kfk" |kafkescli produce hello
kafkescli consume hello --metadata --webhook https://myendpoint.example.com
```
