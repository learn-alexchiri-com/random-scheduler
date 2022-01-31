### Random Kubernetes scheduler

Just a fork from https://github.com/martonsereg/random-scheduler where I changed some things to play around with this example.

This is a custom kubernetes scheduler that can be used for tutorials.
It's not intended for production usage.

The scheduler watches pods and binds them to random nodes, then emits "Scheduled" events.