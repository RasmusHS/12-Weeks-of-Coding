# 12 Weeks of Coding
This repo is meant as a catalogue of projects I’m going going to make over the span of a 12 week period. \
One of the points is to start learning a new language, which will be Go in this case. \
I've chosen to start off these 12 weeks with getting introduced to Go. \
There aren't any particular reason for why I went with Go other than some of the buzz around it. 

# Use of AI
For these projects I'm using Anthropics Claude Opus 4.6 model. \
The AI has been instructed to provide guidance, and sources/docs for myself to research, rather than direct answers, while only providing examples when asked to. \
I have, so far, felt that this has been decent for picking up a new language, Go in this case. \
There has been a single case where I ran late on a project, where I told claude to be direct along with its usual guidance (week 4). \
Outside of that I've leaned on my own experience, knowledge and intuition to judge claude's answers.

# Projects

## Week 1 - Pomodoro Timer (Go)
**Link:** [https://github.com/RasmusHS/Week1-Pomodoro-Timer](https://github.com/RasmusHS/Week1-Pomodoro-Timer) \
To introduce myself to Go I've chosen to make a CLI based pomodoro timer. 
- **Summary:** A pomodoro timer is a technique to help maintain/improve ones own productivity. 
- **What I've touched on during this project:** Go syntax, Go's module system, goroutines, channels, pointers, JSON serialization, struct tags, and CLI flags.

## Week 2 - HTTP Health Checker (Go)
**Link:** [https://github.com/RasmusHS/Week2-HTTP-Health-Checker](https://github.com/RasmusHS/Week2-HTTP-Health-Checker) \
This 2nd Go project is meant to get myself deeper into concurrency and goroutines. 
- **Summary:** A concurrent command-line tool written in Go that continuously monitors the health of a list of URLs. It performs HTTP GET requests in parallel, reports status codes, response times, and up/down status in a formatted table, and repeats on a configurable interval. 
- **What I've touched on during this project:** Concurrent HTTP requests, goroutines with semaphores, WaitGroups, continuous monitoring.

## Week 3 - Log Aggregator & Search Tool (C#)
**Link:** [https://github.com/RasmusHS/Week3-LogAggregator](https://github.com/RasmusHS/Week3-LogAggregator) 
- **Summary:** A CLI tool that aggregates log files from multiple sources and formats, merges them by timestamp, and outputs a unified, searchable log stream.
- **What I've touched on during this project:** File I/O, text parsing with regex, data normalization, and priority queue-based merge sorting in C#.

## Week 4 - Git Repo Stats Tool (Go)
**Link:** [https://github.com/RasmusHS/Week4-Git-Repo-Stats-Tool](https://github.com/RasmusHS/Week4-Git-Repo-Stats-Tool) 
- **Summary:** A simple CLI tool that analyzes a local Git repository and produces statistics: commits per author, activity over time, file churn (most-edited files), and average commit size.
- **What I've touched on during this project:** Process execution in Go, text parsing, data aggregation, and tabular output.

## Week 5 - Reverse Proxy with YARP (C#)
**Link:** [https://github.com/RasmusHS/Week5-Reverse-Proxy](https://github.com/RasmusHS/Week5-Reverse-Proxy) 
- **Summary:** A configurable reverse proxy using Microsoft's YARP library.
- **What I've touched on during this project:** Reverse proxy with YARP, logging middleware with Serilog, basic authentication and authorization.

## Week 6 - Container Image Inspector (Go)
**Link:** [https://github.com/RasmusHS/Week6-Container-Image-Inspector](https://github.com/RasmusHS/Week6-Container-Image-Inspector)
- **Summary:** CLI tool that inspects Docker/OCI container images directly from a registry, without requiring Docker to be installed. It pulls image manifests, lists layers with their sizes, and displays the Dockerfile commands that created each layer.
- **What I've touched on during this project:** OCI Distribution Spec registry HTTP API, auth token flows and header parsing, Gzip decompression and tar archive reading, Idiomatic Go project structure, Formatted CLI output

## Week 7 - Infrastructure-as-Code Config Generator (C#)
**Link:** [https://github.com/RasmusHS/Week7-Infrastructure-as-Code-Config-Generator](https://github.com/RasmusHS/Week7-Infrastructure-as-Code-Config-Generator)
- **Summary:** A CLI tool that generates Docker Compose files, Traefik routing labels, and Cloudflare Tunnel service definitions from a simplified YAML schema describing your homelab infrastructure.
- **What I've touched on during this project:** YAML deserialization, validation pipelines, code generation

## Week 8 - Peer-to-Peer File Transfer (Go)
**Link:** [https://github.com/RasmusHS/p2pft](https://github.com/RasmusHS/p2pft)
- **Summary:** Peer-to-peer CLI file transfer with end-to-end TLS, resumable transfers, and a tiny relay that brokers the introduction but never sees the bytes.
- **What I've touched on during this project:** TCP/UDP networking, NAT traversal, goroutine-based concurrency, and streaming integrity verification.

## Week 9 - Secrets Manager with Encrypted Storage (C#)
**Link:** [https://github.com/RasmusHS/M0useySecrets](https://github.com/RasmusHS/M0useySecrets)
- **Summary:**
- **What I've touched on during this project:** 
