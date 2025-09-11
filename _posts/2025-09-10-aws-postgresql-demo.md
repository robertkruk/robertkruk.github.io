---
title: AWS PostgreSQL Demo with Terraform
date: 2025-09-11 11:00:00 +1000
tags: [project, aws, postgresql, aurora, serverless, pgaudit, cdk, security, compliance]
pin: false
---

# AWS PostgreSQL Demo Project

## The Problem: "Who Accessed The Database?"

![Who accessed the database?](https://robertkruk.github.io/aws-pgsql-demo/docs/spiderman.gif)
*When your database audit trail looks like this...*

I built an AWS PostgreSQL demonstration that solves the critical question: **"Who accessed what data and when?"** This project addresses the common issue of shared database credentials where multiple engineers use the same login, making it impossible to trace individual database actions or maintain proper audit trails.

## 🚀 Full Project Details

**[View the complete project →](https://robertkruk.github.io/aws-pgsql-demo/)**

The project page includes:
- 🎬 **Live demo videos** showing PII masking and audit trails
- 📊 **Architecture diagrams** with detailed explanations  
- 🔧 **Step-by-step setup** instructions
- 💡 **Security best practices** and recommendations
- 📝 **Complete documentation** for replication

## Quick Overview

**What it demonstrates:**
- AWS Aurora PostgreSQL Serverless with PGaudit logging
- Individual accountability through unique database logins
- PII data masking for internal engineers
- Complete audit trails streamed to CloudWatch
- Infrastructure as Code using AWS CDK

**Key benefits:**
- ✅ Track who accessed what data and when
- ✅ Enhanced security and compliance posture
- ✅ Individual engineer accountability
- ✅ Automated infrastructure deployment
- ✅ Cost-effective serverless architecture

## Repository

**[GitHub Repository →](https://github.com/robertkruk/aws-pgsql-demo)**

> **Note**: Remember to run `npx cdk destroy` after testing to avoid ongoing AWS charges!
{: .prompt-warning }