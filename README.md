# On-Premises Architecture with Redis, Kafka, and PostgreSQL

This repository contains:

- Architecture diagram and documentation (Mermaid) in docs/architecture.md
- Ansible Day-2 operations playbook for PostgreSQL in ansible/postgres_day2.yml
- Ansible playbook for Kafka topic creation in ansible/kafka_create_topics.yml
- Sample inventory and vars in ansible/inventory.ini and ansible/vars.yml

Next steps to publish to GitHub:

1. Initialize git (if not already):

git init
git add .
git commit -m "feat: add architecture docs and postgres Day-2 Ansible playbook"
git branch -M master
git remote add origin <your-git-remote-url>
git push -u origin master

2. Create feature branch and push:

git checkout -b feature/1.0.0
git push -u origin feature/1.0.0

3. Open a Pull Request to master using the GitHub UI or gh CLI:

gh pr create --base master --head feature/1.0.0 --title "Feature: v1.0.0 architecture + playbook" --body "Adds architecture docs and PostgreSQL Day-2 Ansible playbook"
gh pr merge --merge
