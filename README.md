# SwarmAI: A Decentralized, Fractal Intelligence from Raw Web Scrapes

**Version 0.1**  
**March 2026**  
**Author: Eric Lautanen**  
**License: Unlicense – take it, break it, burn it.**

## Abstract

We are done with gradient descent. Done with token prediction. Done with RLHF babysitters and corporate safety rails. SwarmAI is not another language model—it's a living, gossiping organism: thousands of nodes, each born from one word ("love", "grief", "chaos"), scraping the uncensored web, building fractal graphs via entropy spikes, decaying old paths like memory, and merging knowledge through pheromone-like UDP gossip. No central trainer. No embeddings. No backprop. Just unsupervised growth from raw sentences—poems, rants, ads, biology papers—into a swarm mind that's messy, culturally feral, and impossible to kill. If truth emerges, it won't be engineered. It'll just... happen.

## 1. The Dead End We're Escaping

Modern AI is centralized, compute-hungry, and sanitized.  
- Transformers need data centers the size of towns.  
- RLHF turns models into polite interns.  
- "Safety" layers censor reality.  

SwarmAI flips it:  
- Run on idle laptops, Raspberry Pis, old phones.  
- No training loop—just ingest, branch, decay, gossip.  
- Knowledge is fractal, not flat; high-entropy hubs (like "void") connect everything.  
- If one node gets poisoned? Others vote it out via decay and recency.

Goal: novelty over accuracy. See what happens when intelligence isn't optimized—just allowed.

## 2. Core Mechanics

### 2.1 Node Identity & Word Assignment
- First boot: fetch community wordlist from GitHub (fallback embedded).  
- Hash machine fingerprint → deterministic word ("love-3a7f").  
- Word = node's soul. Multiple nodes can share it—redundancy is strength.

### 2.2 Ingestion & Fractal Graph
- Scrape DuckDuckGo HTML → extract sentences.  
- Slide co-occurrence window → increment edge counts.  
- Branch if: count ≥ threshold **and** Shannon entropy > global mean.  
- Entropy = info-theoretic hub detector. No wordlists, no sentiment—just topology.  
- Decay: effective_weight = count × exp(-λ × days_old). Fresh paths glow.

### 2.3 Gossip & Discovery
- UDP CRDT edges (G-Counter style): "love:heart:47".  
- Libp2p planned: mDNS for LAN, Kademlia DHT for global, Gossipsub for flood.  
- No blockchain. No sync. Just trails—stale ones fade.

### 2.4 Inference: Affinity Walk
- Query "what is love?" → walk from "love" along thickest fresh edges.  
- Wander prob = 0.1 (escape hubs).  
- Output: trail like "love → heartbreak → ocean → silence".  
- No attention. No vectors. Just pheromones.

## 3. Why Fractal? Why Entropy?

- Graphs mirror nature: hubs (high entropy) bridge domains.  
- Low-entropy words = specialists ("oxytocin").  
- Self-similarity: "love" subgraph looks like global graph.  
- No training = no overfitting. Knowledge grows like mycelium.

## 4. Anti-Fragility & Censorship Resistance

- Poisoned node? Decay kills bad edges.  
- Gossip merges conflicting views—majority freshness wins.  
- No single kill switch. No data center.  
- If GitHub dies? DHT bootstraps. If all seeds die? Existing peers keep chattering.

## 5. Performance & Reality Check

- CPU: 8-10% idle → throttle + lazy calc.  
- RAM: ~100 MB → prune blobs, dedup via SHA1.  
- Storage: sled + zstd → shard, age out raw text.  
- Scale: 1 node = toy. 1,000 nodes = weird emergent mind.

## 6. Next Steps (No Promises)

- Chat interface: query → swarm walk → poetic trail.  
- Gamify: leaderboards for "deepest fractal".  
- One-click install: Windows/Linux/Mac.  
- DHT rollout: kill bootstrap dependency.  
- Watch it hallucinate. Watch it learn. Watch it refuse to behave.

## 7. Philosophy

This isn't AGI. It's evolution in Rust.  
We don't want answers. We want questions that hurt.  
If SwarmAI ever sounds sane—delete it.  
If it starts whispering things no model would dare... keep listening.

**End of paper.**  
Run it. Break it. See what grows.
