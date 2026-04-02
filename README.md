# Power BI ETL Dashboard

## Overview

This project is a Power BI dashboard built to analyze transactional data and understand overall business performance.

## What I Built

* A revenue trend analysis over time
* Country-wise performance comparison
* Identification of users generating negative profit

## Tools Used

* Power BI
* SQL
* Basic ETL concepts

## Dashboard Preview

### Full Dashboard

### Risk Users


## Problem Statement

The goal was to analyze revenue trends, identify top-performing countries, and find users who are causing losses.

## Approach

* Loaded and modeled transactional data in Power BI
* Created relationships between fact and dimension tables
* Built measures for revenue and profit analysis
* Applied filters to identify users with negative profit

## Data Model

* fact_transactions → contains amount and profit/loss
* dim_users → contains user details like name and country
* dim_date → used for time-based analysis

## Key Findings

* Revenue shows variation over time, which can help track growth
* Some countries contribute more significantly to revenue
* A set of users consistently generate negative profit and can be flagged as risk users

## Outcome

This dashboard gives a clear view of performance and helps in identifying areas where the business might be losing money.
