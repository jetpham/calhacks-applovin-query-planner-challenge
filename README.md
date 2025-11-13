# Query Planner Challenge

This repository contains the **Query Planner Challenge** from Calhacks x AppLovin. This challenge was given to college students from the Calhacks hackathon in October of 2025.

## Goal

The goal of the challenge was to create a database system that can query a given dataset as fast as possible.

## Leaderboard

From Calhacks 2025, the leaderboard was as follows:
1. **@Keven Liu** - 76 ms ([Github](https://github.com/KevinL10/applovin-query))
2. **@Dan Wu** - 168 ms ([GitHub](https://github.com/KevinL10/applovin-query))
3. **@George Ishaq** - 269 ms ([GitHub](https://github.com/georgelshaq/Calhacks_AppLovin_Challenge))
4. **@Suprad Parashar** - 370 ms ([GitHub](https://github.com/suprad-parashar/Calhacks-12.0-Query-Planner-Challenge))
5. **@Tom Binford** - 1,134 ms
6. **@Karthik Rachamolla** - 2,010 ms ([GitHub](https://github.com/kee5625/QP_fast))
7. **@Jet** - 2,117 ms ([GitHub](https://github.com/jetpham/calhacks25))

> **Note:** These benchmarks were run on the contestants' machines and not the M2 MacBook as listed in the challenge due to network issues at Calhacks that prevented judges from downloading contestants' projects. Some projects include query optimization and some do not. The preprocessing time of each project varies but was capped to about 40 minutes.

## Benchmark

The contestants were given a 20GB dataset and a set of 5 queries in [queries.json](queries.json) to initially test their solution. These queries could be converted to sql as demonstarted in [assembler.py](baseline/assembler.py).

After they developped their solutions, on judging day, they were given a new set of 19 queries in [judges.json](judges.json).

## Getting Started

### Setup Instructions

1. **Download the data zip file from Google Drive:**
   - Visit: <https://drive.google.com/file/d/1Opr1G6buA4Y-PCTJmUO4iLm6n9Rxypuu/>
   - Download `data.zip` to the repository's root directory

2. **Extract the files:**

   ```bash
   unzip data.zip -d .
   ```

3. **Clean up (optional):**

   ```bash
   rm data.zip
   ```

   This will extract the data files into the current directory.

## Challenge Details

For the complete details of the challenge as was given to contestants, see [CHALLENGE.md](CHALLENGE.md).
