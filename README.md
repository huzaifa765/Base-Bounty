# BaseBounty

A decentralized bounty protocol built on Base.

## Overview
Post ETH-backed bounties for tasks, let anyone claim them,
and approve completion to release funds automatically on-chain.

## Features
- Post bounties with ETH locked in contract
- Multiple claimers per bounty
- Poster approves best submission
- Auto ETH transfer on approval
- Deadline-based cancellation with full refund

## Contract
- Network: Base Mainnet
- Address: `0x56b387a14ba15db88c90aa848f755243a468946d`
- Verified on Basescan

## How It Works
1. Poster creates bounty with ETH + description + deadline
2. Anyone claims the bounty (registers intent)
3. Poster approves best claimer → ETH transfers automatically
4. If deadline passes with no approval → poster cancels + gets refund

## Tech Stack
- Solidity ^0.8.20
- Base Mainnet
