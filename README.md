# Peer-to-Peer Video Call

A simple peer-to-peer video calling project. I built to understand how real-time video communication works in the browser using **WebRTC**.

## What I Built

I built a browser-based video call where one side captures video from the local camera and establishes a direct peer-to-peer connection with another peer.The project handles the WebRTC connection, video streaming, ICE candidates, and connection/disconnection states.

The basic flow is:

Local Camera -> getUserMedia() -> WebRTC Peer Connection -> Offer / Answer -> ICE Candidates + STUN -> Peer-to-Peer Connection -> Remote Video 

## What I Learned

- How WebRTC establishes peer-to-peer connections
- How getUserMedia() provides camera streams
- How SDP offers and answers work
- How ICE candidates are exchanged
- How STUN helps with network discovery
- How remote media tracks are received
- How browsers handle real-time video communication

## Project Goal

I built this project to get hands-on experience with WebRTC, peer-to-peer networking, real-time video streaming, and browser media APIs.
