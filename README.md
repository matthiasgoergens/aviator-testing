# Aviator Merge Queue Testing

Test repo for evaluating [Aviator MergeQueue](https://www.aviator.co/merge-queue) batching behaviour.

## Setup

1. Install Aviator GitHub App on this repo
2. CI workflow has a deliberate 60s sleep to simulate a slow build
3. Queue multiple PRs and observe batching
