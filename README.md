# 💸 Hidden Cloud Costs & Optimization Calculators (2026)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

Cloud providers often hide their most expensive pricing tiers, bandwidth taxes, and overage fees in the fine print. This open-source repository exposes the real compute and bandwidth costs of popular Developer Tools, CI/CD runners, and Cloud platforms.

Below is a curated collection of interactive calculators and data to help you optimize your infrastructure and stop overpaying.

---

## 🚀 1. Frontend Hosting & Bandwidth Traps
Platforms like Vercel and Netlify are amazing for developer experience, but their bandwidth overage costs can kill a startup's runway.

| Provider | Base Pro Plan | Overage Bandwidth Cost | Alternative (VPS/PaaS) |
| :--- | :--- | :--- | :--- |
| **Vercel** | $20/mo | $40 per 100GB | ~$0.01 per GB |
| **Netlify** | $19/mo | $55 per 100GB | ~$0.01 per GB |

👉 **Calculate your exact hosting bill:** [Vercel vs Netlify Cost Calculator](https://www.githubactionscost.online/vercel-vs-netlify-cost)

---

## ⚙️ 2. CI/CD Pipeline Costs
Are you burning through your free CI/CD minutes? Compare runner costs before scaling your team.

| CI/CD Tool | Free Tier | Cost after Free Tier (Linux) |
| :--- | :--- | :--- |
| **GitHub Actions** | 2,000 mins/mo | $0.008/min |
| **GitLab CI** | 400 mins/mo | $0.008/min |
| **CircleCI** | 6,000 mins/mo | Varies by compute credits |

**Interactive Cost Calculators:**
* 🧮 [GitHub Actions Cost Calculator](https://www.githubactionscost.online/github-actions-cost-calculator)
* ⏱️ [GitHub Actions Free Minutes Calculator](https://www.githubactionscost.online/github-actions-free-minutes-calculator)
* 🦊 [GitLab CI Cost Calculator](https://www.githubactionscost.online/gitlab-ci-cost-calculator)
* 🔄 [CircleCI Cost Calculator](https://www.githubactionscost.online/circleci-cost-calculator)
* 🏗️ [AWS CodeBuild Cost Calculator](https://www.githubactionscost.online/aws-codebuild-cost-calculator)
* 📊 [Overall CI/CD Cost Comparison](https://www.githubactionscost.online/cicd-cost-comparison)

---

## ⚡ 3. Serverless Compute & API Rate Limits
Scaling serverless functions can lead to massive bill shocks if not optimized with proper caching and API rate limiting.

* 🌩️ [AWS Lambda Cost Calculator](https://www.githubactionscost.online/aws-lambda-cost-calculator)
* 🚦 [API Rate Limit Calculator](https://www.githubactionscost.online/api-rate-limit-calculator)

---

## 🗄️ 4. Databases & Infrastructure Setup
Choosing between Backend-as-a-Service (BaaS) and setting up your own Dockerized environments. 

* 🔥 [Supabase vs Firebase Cost](https://www.githubactionscost.online/supabase-vs-firebase-cost)
* 🐳 [Docker Hub Pull Rate Calculator](https://www.githubactionscost.online/docker-hub-pull-rate-calculator)
* 🏗️ [Full Tech Stack Cost Calculator](https://www.githubactionscost.online/tech-stack-cost-calculator)

---

## 🤝 Contributing
Found a hidden cost or want to update the pricing formulas? PRs are highly welcome! Let's help the developer community save money.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewCalculator`)
3. Commit your Changes (`git commit -m 'Add some NewCalculator'`)
4. Push to the Branch (`git push origin feature/NewCalculator`)
5. Open a Pull Request

## 📝 License
Distributed under the MIT License. See `LICENSE` for more information.
