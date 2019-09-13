---
layout: post
title: Introducing PacketStream's ProxySampler
---

PacketStream, the world’s first residential proxy network powered by peer-to-peer technology, widely-known for our reliable service and innovative tools that help our clients achieve business success through automation. 

Recently, we added another CLI tool to our arsenal – ProxySampler. 

ProxySampler is an open-source Command Line Interface (CLI) tool that can be used to test proxies and measure their health and performance. 

Proxies are essential elements in business automation. Thus, you must constantly monitor the speed and reliability of their infrastructure.

While there are hordes of online proxy checkers, most of them only check whether proxies are working or not. 

ProxySampler has several features that enable you to do so much more than this.


## What can ProxySampler do?

If you’re utilizing residential proxies for your business automation solutions, ProxySampler can help you optimize their use. 

Through this tool, you can do the following: 

### 1.	Check the performance and health of proxy tunnels.

ProxySampler enables you to test both massive lists and one-off proxies. It facilitates more efficient monitoring of multiple proxy servers and sends alerts when certain conditions arise.

### 2.	Get metrics on the performance of residential proxies.

PacketStream customers can optimize their residential proxies using ProxySampler. 

As part of our automation tooling, ProxySampler provides metrics on which residential proxy sessions are performing more reliably so that users can prioritize those specific sessions.

### 3.	Monitor the health of proxy tunnels.

ProxySampler is used internally at PacketStream as part of our infrastructure monitoring toolset. 

Through this tool, we can monitor the health of our proxy tunnel. This tool can also trigger alerts whenever something seems off.

## How do I use ProxySampler?

ProxySampler is quite easy to use. It contains very few cli arguments for configuration. All you need to do is provide the proxy server, port, and author information. 

ProxySampler then tests the proxy tunnel and returns information about the response codes and response times.

You can use ProxySampler to:

* Test a single PacketStream residential proxy with a US exit IP. JSON output
  
* Test a list of PacketStream residential proxies from a file. JSON output

## Where do I get ProxySampler?

To learn more about ProxySampler and how to install it, go to [https://github.com/packetstream/proxysampler](https://github.com/packetstream/proxysampler).

To get more information about PacketStream, visit our website at [packetstream.io](https://packetstream.io/). 
