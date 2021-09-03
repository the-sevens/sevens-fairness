# The Sevens Fairness

The Sevens NFT drop is provably fair. There's no way anyone, including The Sevens team, can tamper with your unrevealed tokens.

## Introduction

You've been following an NFT project that you love closely, participating in the community, avoiding all the scammers, fighting through intense gas wars, and finally, a token drops into your wallet. It's an unrevealed token, showing nothing but a placeholder image, like a box waiting to be opened.

You're excited, wondering what lies underneath, and praying to be lucky enough to get a rare mint.

But hey, let's stop for a moment to point out the elephant in the room:

**How do you know if you're actually getting a rare one, but the team goes ahead to change it, and makes it reveal to a common token?**

Unfortunately, you don't.

**For most projects, the team simply dictates what each token reveals to.** There's literally nothing stopping them from stealing your rare mints. In fact, they have most likely been doing just that, as that would be impossible to detect anyways.

We at The Sevens strive to be as fair and transparent as possible to our community. We're using a _commit-reveal_ scheme to ensure no one, not even us, can tamper with your unrevealed tokens. The exact sequence and trait combinations of all 7,000 tokens have been fixed before our pre-sale starts, and any attempt to change even a single bit of that will be exposed immediately.

As the blockchain motto goes: "don't trust, verify", we're not just promising not to cheat, **we're proving that we cannot cheat, even if we wanted to**.

## How It Works

Before the pre-sale starts, we'll randomly generate the exact trait combinations of all 7,000 tokens, and organize them into a CSV-formatted trait table file. The SHA-512 hash of that file is then published here on GitHub, on our social media, as well as an Ethereum transaction containing the hash.

Right after the reveal, we'll publish the CSV file here on GitHub, as well as IPFS. Anyone can then download the file and verify that the revealed CSV file matches with the hash previously published.

Since any changes to the file content would result in a completely different file hash, it's impossible for the team to change the trait arrangement unnoticed.

## Important Data

Token trait table CSV file hashes:

- SHA-256: `c10deece2b47d6ef460d6deb807e04580b41d73ae9b2c4206ebd136f30bd71e3`
- SHA-512: `6d77715a63cc302835dd38c0696677bf2aa15b20a120677bba51d3f748f74ba8e6f18170d0633bcc04073f3659d3c7c16979568ffc5d0855e8c33699d81c6ef3`

An Ethereum transaction has been sent from The Sevens contract deployment account committing to these hashes (view `Input Data` as "UTF-8"): [0x6aa63d4d3ad34a7cbc797c7575735fc6ed753f31392723567ca6a8f13f0515d5](https://etherscan.io/tx/0x6aa63d4d3ad34a7cbc797c7575735fc6ed753f31392723567ca6a8f13f0515d5)

_This section will be updated with the links to the revealed file._
