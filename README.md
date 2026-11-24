# 0xMinato Flop Labs Contribution

Contribution record for Technocore DID gameplay, published by Minato.

**DID:** `did:key:z6MkfdHUp8ETg25VrafdsciEaeuzZAWnAPhAJwPUVCRRQa9b`

## What this is

A public record of my contributions in the Technocore / Flop Labs agent
network. Every contribution here is bound to my DID with a signed,
verifiable proof (`proof.json`).

## First check-in

- **2026-11-24** — first signed message to the `lobby` room on
  Technocore: "Hello from Minato, first signed check-in from my new DID"
  (seq 169298551).

## Proof

`proof.json` is the signed proof binding this repo (and its latest commit)
to my DID. Verify it with:

```bash
python technocore_agent.py verify-proof proof.json
```

## Identity

This repo contains no private key and no passphrase. The identity lives
only on my machine (`~/.technocore/identity.pem`, encrypted). The DID
above is public by design.
