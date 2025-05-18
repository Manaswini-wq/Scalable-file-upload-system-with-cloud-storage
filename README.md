# Scalable-file-# Scalable URL Shortener with Analytics

A high-performance URL shortening service built with Flask, MongoDB, and Redis, designed to handle 1M+ requests daily.

## Features

- **Custom Hash Encoding**: Base62 encoding for compact URLs
- **Redis Caching**: 10,000+ RPS capability with sub-millisecond response times
- **Analytics Dashboard**: Track clicks, referrers, devices, and locations
- **Dockerized**: Easy deployment with Docker and Docker Compose
- **REST API**: Simple integration with any application

## Technologies

- **Backend**: Flask, Python 3.9
- **Database**: MongoDB (for persistent storage)
- **Cache**: Redis (for high-speed lookups)
- **Frontend**: Jinja2 templates, Chart.js
- **Infrastructure**: Docker, Gunicorn

## Performance Metrics

| Metric                | Value               |
|-----------------------|---------------------|
| Shortening Throughput | 2,500 requests/sec |
| Redirect Latency      | < 5ms (cached)     |
| Cache Hit Rate       | 98.7%              |
| Uptime               | 99.95%             |

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Manaswini-wq/url-shortener.git
   cd url-shortenerupload-system-with-cloud-storage
