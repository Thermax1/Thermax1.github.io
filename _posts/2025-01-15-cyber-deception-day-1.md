---
layout: post
title: Antisyphon Training's Active Defense & Cyber Deception Day 1 - My Thoughts 
subtitle: Highlights of what I learned
thumbnail-img: /assets/img/colorful-laptop.jpg
cover-img: /assets/img/day-1-cover.jpg
tags: [Cyber, Defense, Antisyphon Training]
comments: true
author: Anthony Munoz
---

## Active Defense and Cyber Deception Day 1

Welcome to my short blog series about me taking Antisyphon Training's Active Defense and Cyber Deception class. My goals for this series is as follows:

1. Accountability for myself to take notes and pay attention.
2. Have proof that I learned something.
3. Have fun

### Hour 1

First and foremost, John Strand has a great presentation attitude. You can tell he's into what he's talking about, talks about it well, and really makes this 4-hour class a breeze.

The first thing I learned about was <a href="https://engage.mitre.org" target="_blank"> MITRE ENGAGE.</a> The official site says that MITRE Engage is a framework for planning and discussing engagement operations to achieve your cybersecurity goals. Basically, don't just throw up a firewall and call it a day.

Then, I finally learned what **Active Defense** and **Cyber Deception** mean.

- Active Defense: In simple terms, use techniques/tools to deny your enemy more ground. In an active defense scenario, they're already inside.
- Cyber Deception: A calculated process where one deceives attackers.
  - Make your enemy WORK harder, giving more time to detect them and potentially stopping them.

Sadly, cyber deception isn't in NIST (yet) so its most likely not going to be part of an organization's compliance requirements. What does this mean? It means organizations don't use it.

So, why do we care about cyber deception? The analogy John Strand said of *"think poison, not venom"* is what struck me. Let the enemy create their own demise. The more time they're fumbling around in your network due to your preparation, the better chance they finally trip something that allows you to detect and respond to the threat.

### Hour 2

After our state-mandated 10-minute break, we go off into hour 2. My favorite part of this hour is learning that SANS has a robots.txt page. I guess you can also call it a "disallow" page. Essentially, don't try poking into anything listed on that, otherwise, your IP (and you) will be blacklisted off the site.

<figure>
  <img src="/assets/img/trash-throw-day-1.jpg" alt="Trash Symbol sign">
  <figcaption>This will be you if you mess with SANS, man</figcaption>
</figure>

I also learned that we've been using the same terminology forever. It started with patching, firewalls, anti-malware, etc. Then we moved on Next-Gen firewalls, Next-Gen anti-malware. As of 2024, we now have the newest buzzword: **AI**. AI-Antivirus. AI-firewalls. The point of trying to be made is that security is still pretty reactionary by nature.

A pop quiz for those that are still here. What malware should you be most afraid of? John Strand thinks it's any malware that is able to remain persistent. As someone who wants to work in cybersecurity, I'll cede to his authority in this one. Sounds like a major headache. Malware that never leaves. Some hacker is able to create a user account in your system and goes from there. Geez. that sucks.

### Hour 3

The main thing learned here is SEGMENTATION, baby. Everybody and their mom should segment internal networks. First, assume you're going to get compromised, because you are. So, you get hacked, the enemy is in. In a non-segmented scenario (AKA happens way too much) the attacker is able to pivot from one compromised system to the next, until your network is taken over. Attacks such as Pass-the-Hash and Security Token Access(SAT) succeed in environments such as this.

Knowing this, you should treat your internal network (that should be segmented) as hostile. A good rule is to make sure that your internal system firewalls should act like a coffee shop. We've all logged into Starbucks or maybe a mall's Wi-Fi. No inbound traffic is allowed, alerts get generated, and only Admin networks get any exception, as they should. Your HR department shouldn't have any reason to have its subnet talk to the software engineers (If I understood what was being said earlier).

### Hour 4

Lab time! I will write this up later. 