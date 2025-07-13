# This is the State of Artificial Speech Today

## Current Solutions

### Voice Prosthesis
[View Voice Prosthesis State](https://drive.google.com/file/d/1EjtT3OkSbqxznwgjxbiLoBjMxN2qiCe1/view?usp=drivesdk)

### Electrolarynx
[View Electrolarynx State](https://drive.google.com/file/d/1EczeOOBIwngx5oHyzh7eK3IvV_FUtL4N/view?usp=drivesdk)


## Problem

Adults who lose speech ability after stroke or vocal cord surgery face significant communication barriers. Existing solutions provide poor speech quality and user experience, leading to social isolation and reduced quality of life.

**Current solutions are antiquated, invasive, and fail to meet users' fundamental need for natural communication.**

## Solution

Create **Resonance**, an AI-prosodic generator that translates laryngeal muscle signals into prosodic vibrations. User's mouth and lip movement become filters, transforming these vibrations into audible, natural sounding speech.

## USP of Resonance

1. **Non-invasive** - No surgical procedures required
2. **Gets better with usage** - Adaptive learning improves performance over time  
3. **Affordable** - Cost-effective compared to device and surgery costs
4. **Empowers self-expression** - Enables natural communication and social interaction

### Architecture Overview
```
Laryngeal Muscle Signals → Sensors → Neural Network → Actuator → Prosodic Vibrations → User's Mouth/Lips → Natural Speech
```



## Why Build It?

### i. Business POV
High CLTV. Customers of existing solutions reported 7+ years of usage, paid. In plain english -- loyal customers who will use it till their demise.

### ii. Positioning POV

Established distribution networks and sales pipelines already exist providing clear market access.

### iii. Technical POV
Grounded human-machine interface deployment while maintaining biological autonomy. Each user interaction generates unique, real-time data that continuously improves our ML models with minimal computational resources. This foundational technology platform opens pathways for expansion into other stuff.

### iv. Impact POV
Just watch [this](https://youtu.be/oHm4zF3UJ9k?si=sPd-liJK62vrfVq_) & imagine them instead talking about you. **This is after prosthesis, they paid 5-digit USD with 3-4 digit USD in continuity care every year.**

### v. Personal POV
Reduces role of chance in postmodern human life. (challenges god?)


## Stats & Market Size

**Primary Market: Laryngectomy**
- At least 200,000 new laryngectomy userbase generated every year annually (immediate market)
- XXMn already living with it
- Users report 7+ years of continuous, paid usage (high CLTV)

**Secondary Market: Neurological Speech Impairment**
- 30-40% Stroke patients → Speech Impaired
- ~11Mn new stroke cases annually (70% increase since 1990)

**Annual Incidence (Other Conditions)**

● **Intubation-related laryngeal injury** - ~50% of ICU intubees experience injury

● **Tracheostomy complications** - Voice-affecting complications in ~20–40% of cases

● **Nerve injury in thyroid surgery** - 0.3–3% transient; up to ~1% permanent

● **Voice impact post-head/neck cancer** - ~50% survivors report dysfunction

● **Burns & inhalation injuries** - 16–60% face long-term vocal effects

● **Blunt airway trauma** - ~0.3–5% incidence in trauma patients

● **Stroke-related dysarthria** - Affects a large share of ~11M strokes/year globally

**Conservative TAM: $2.5B+ annually**


### Hypothesis

Electrolarynx already works on vibration --> Speech (so this part is out of doubt) 

Reason it is bad is because of fixed frequency (80-150Hz). 

To reason phoneme patterns and generate dynamic frequency (80-300Hz) work for more natural and rythmic speech?

If Yes --> AI can be deployed to reason haptic enviornment and deliver output using actuators.

If No --> Someone can control frequency using Resistance, but that is boring and tough to scale and not doable. 

