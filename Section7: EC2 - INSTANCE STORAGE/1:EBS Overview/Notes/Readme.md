# EBS VOLUME

# WHAT IS AN EBS VOLUME?

## An EBS (Elastic Block Store) VOLUME is a NETWORK drive you can attatch to your instances while they run

## It allows your instances to persist data , even after their termination

## They can only be mounted to one instance at a time(at the CCP level)

## They are bound to a specific availibility zone

## Analogy : Think of them as a "network USB stick"

## Free teir: 30 GB of free EBS storage of type General Purpose(SSD) or Magnetic per month

[![Slide 1](../Slides/Slide1.png)](../Slides/Slide1.png)

# EBS VOLUME

## Its a network Drive(i:e Not A Physical Drive)

### It uses the network to communicate the instance, which means there might be a bit of latency

### It can be detached from an EC2 instance and attached to another one quickly

## Its locked to an Availibility Zone(AZ)

### An EBS VOLUME in us east 1a cannot be attached to us east 1b

### To move a volume across you first need to sanpshot it

## Have a provisioned capacity
