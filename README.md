# CodepathWeek9

## The Honeypot
I deployed the dionaea on my vm. 

## Issues
The instructions on courses.codepath.com are a little dated, so I had to do some research on my own to fully deploy the system. One of the github repos no longer exists, so I had to use a different one. I needed to add in some extra firewall rules to be able to access the admin console. 

## Summary
I had a total number of 28172 attacks. The country with the most attackers varied each day. The first day had USA with the most attackers, and the final day had the Netherlands with the most attackers. The most attacked port was port 8088, and the second most attacked port was 445. There were around 7000 attacks each day.

## Questions
The honeypot is able to determine the origin of the attack from the ip. How useful is this data when an attacker could proxy to another nation?
