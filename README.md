# serval-message-relay
Simple MeshMS to SMS relay for Serval Mesh

This repository contains scripts to poll a servald instance for new incoming
MeshMS messages, and for each to use TextMagic's API to send an SMS to each
phone one a list. It should be easy to adapt to other SMS service providers.

The scripts also generate an HTML page summarising all messages processed,
that could be used as a simple and crude user interface to see what messages
are received by this station.

The overall goal of these scripts is to provide a very simple and light
weight system for a "message operations centre" on a Serval Mesh network,
to allow messages to a central location to be received and processed.
This could be used, for example, to allow an isolated community to be able
to send messages to specific phones in the outside world for various
purposes.  For all but the most trivial of applications, more would be
required.
