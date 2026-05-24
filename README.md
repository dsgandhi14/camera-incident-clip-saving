# camera-incident-clip-saving

## Introduction
Dear Netradyne Team, after some research about Netradyne's product suite, I have decided to apply my system design skills to solve a specific problem that I figured you would have encountered (and potentially solved). The purpose of this architecture doc is to help you understand how I think about system architecture when given a problem statement.

## Problem Statement
Video recording from multiple vehicle cameras of a fleet monitoring system needs to be saved to cloud only when an incident (indicated by AI Model) occurs. This methodology helps to optimize bandwidth used by each node (Edge AI Camera) and storage space on server.

## Solution
The following system is designed to save the previous 10 seconds of video and next 10 seconds of video when an incident occurs on a specific camera.


