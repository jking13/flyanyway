# FlyAnyway
FlyAnyway - High availability Elasticsearch mapping migrations made easy

## Purpose
Dealing with mapping migrations in a high throughput, high availability system is really hard. The suggested migration patterns (https://www.elastic.co/blog/changing-mapping-with-zero-downtime) are a matter of what you're willing to sacrifice, whether that be resiliency in deployments, uptime, performance, or data loss. The goal of this library is to minimize as many sacrifices as possible, while at the same time providing a migration automation system that allows for rapid and consistent development.

## Project status
Just started! My plan for the project is to initially support spring w/ java 8 and elasticsearch 5, but this can be expanded down the line depending on interest. 
