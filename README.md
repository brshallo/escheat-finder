# escheat-finder

An effort to actively reunite people with **unclaimed property** — money held by state governments after a forgotten or unchecked account, refund, or deposit is turned over to the state ("escheatment").

The goal is simple and narrow: review records of unclaimed property, try and find up-to-date contact information from public sources and websites associated with those records, and send a message pointing the (hopefully) correctly identified owners to the **official, free** state portal to claim it.

This project does **not** charge fees, file claims on the behalf of others, or sell personal information.

> ⚠️ **Status: early testing.** Currently this is an exploratory side project. I'm sending a small number of outreach notes initially and learning as I go. The approach may change substantially (or be abandoned depending on the response I get). More details likely to be added to this repo later.

## Background

Before starting this project I successfully filed my own unclaimed property claim through a free state run portal.

One reason I decided to set this up is that many people are unaware these funds exist or that property transferred to a state unclaimed property program is typically converted to its cash value and no longer benefits from future appreciation. If you're new to unclaimed property and escheatment, NPR's Planet Money has a good overview:
https://www.npr.org/2025/03/19/1239428617/escheat-unclaimed-property-forgotten-money

You can search across states for your own name as well as file a claim for free at the National Association of Unclaimed Property Administrators (NAUPA) managed website [missingmoney.com](https://missingmoney.com/). Each state also typically runs their own unclaimed property websites, California's is [claimit.ca.gov](https://claimit.ca.gov). (I have occasionally found slight differences in which records show up when looking at the national vs state level sites.)

## Where I am currently focused

- I'm starting with **California's** unclaimed property data,
- Prioritize records that are likely to be matched accurately and are meaningful enough to justify outreach,
- For a given record, use public information to identify the person associated with a name and try to find current contact information,
- Only contact individuals with records where I have **reasonably high confidence** in the identity and contact information.

When I do reach out, it's a plain note that:
- explains where I found their contact information,
- explains where I saw the public unclaimed property record and shows it,
- links people to an **official free portal**, in CA that's [claimit.ca.gov](https://claimit.ca.gov).

You can see a sample template of the email I send [sample-email.md](sample-email.md).

## What I do *not* do

- charge a fee-for-service,
- file claims for people or offer legal/recovery services,
- sell personal information as a product.

**Asset-recovery finders in CA typically charge rates of 10%. A point here is to nudge people toward the free official process.**

## How I connect records

At a high level...

* I start with initial filters on records that keep only those records that are likely to have a high degree of uniqueness
* I next triage those records with initial searches to see if the potential individuals have sufficient public records to warrant a deeper search
* After the initial triage phase, the remaining records each get a deep-dive where up-to-date identifying information is gathered from public sources
* Based on this search the confidence in the identified information is estimated
* For records with reasonably high confidence, send a message (this is typically a small percentage of the records the search started with)

Even though every step currently uses only public information, some of the techniques for linking a record to a person with actionable contact information could be misused by bad actors. Hence, while I'm not doing anything too fancy, I'm still working out how much detail would be safe and useful to share here. Therefore this repo is currently mostly a public facing placeholder and only describes the project at a high level. I intend to publish more on the methodology later. 

