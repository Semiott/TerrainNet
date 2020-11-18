# Summary
Post Pandemic Climate Conservation System using Quadratic Voting Verifiers

# Overview
- Quadratic Voting for Climate Conservation
- Quadratic Voting Verifiers using Cryptography

# Concepts

## Quadratic Voting

Quadratic Voting is the mathematically optimal way to vote in a democratic community, where votes express the degree of your preferences, not just direction. 

## Inspiration

The UNFCCC secretariat (UN Climate Change) is the United Nations entity tasked with supporting the global response to the threat of climate change.  UNFCCC stands for United Nations Framework Convention on Climate Change. The Convention has near universal membership (197 Parties) and is the parent treaty of the 2015 Paris Agreement. Election and appointment of members for positions on bodies under the Convention, Kyoto Protocol and Paris Agreement take place annually during the Climate Change Conferences. Regional groups and constituencies nominate candidates to these bodies.  Parties are urged to meet the goal of gender balance on these bodies. Please find further details about the current election process in the following page in UNFCC website.

https://unfccc.int/process-and-meetings/bodies/election-and-membership

As we can see, this process is highly archaic and arcane. It does not address the asymmetries in the contributions from climate change causing countries and concerns of the countries suffering from climate change in a reflective and responsive manner. We need an architectural and algorithmic change in the election and voting process. This is why I am suggesting quadratic voting mechanism to address these asymmetries. 

## What it does

TerrainNet is the combination of a decentralised web app for quadratic voting coupled with a cryptographic proof system to verify the quadratic voting system in a privacy preserving manner using zero knowledge proofs. 

Quadratic voting is a collective decision-making procedure where individuals allocate votes to express the degree of their preferences, rather than just the direction of their preferences. By doing so, quadratic voting helps enable users to address issues of voting paradox and majority rule. Quadratic voting works by allowing users to "pay" for additional votes on a given matter to express their support for given issues more strongly, resulting in voting outcomes that are aligned with the highest willingness to pay outcome, rather than just the outcome preferred by the majority regardless of the intensity of individual preferences. 

The payment for votes may be through either artificial or real currencies (e.g. with tokens distributed equally among voting members or with real money). Quadratic voting is a variant of cumulative voting in the class of cardinal voting. It differs from cumulative voting by altering "the cost" and "the vote" relation from linear to quadratic.

## How I built it

I have developed quadratic voting smart contracts using Ethereum Blockchain Protocol. I have developed cryptographic primitives known as zero knowledge proofs to verify quadratic votes in a minimal anti collusion manner using a framework known as MACI. 

## Challenges I ran into

Customising quadratic voting verifiers for the climate change consensus. 

## Accomplishments that I'm proud of

Integration of quadratic voting verification proofs into quadratic voting smart contracts. 

## What I learned

I learned about the UNFCC election process and the inefficiencies in this process. 

## What's next for TerrainNet

Deployment of quadratic voting proofs and platforms for climate change decision making process in the cities. 

