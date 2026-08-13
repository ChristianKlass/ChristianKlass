# Mark Klass

Platform and DevOps engineer in Singapore. Eight years, mostly Linux,
cloud infrastructure and CI/CD. At work that currently means EKS.

At home I run a Proxmox box with 14 guests and a small kubeadm cluster,
both managed with Terraform and Flux. Secrets are SOPS-encrypted. Access
goes through Authentik and Cloudflare Tunnels. Frigate handles the
cameras, running inference on a Coral EdgeTPU instead of a GPU. Backups
go four tiers deep and end up in Cloudflare R2.

Two repos here worth opening:

**[kopilog](https://github.com/ChristianKlass/kopilog)** publishes a tech
news site with nobody at the wheel. RSS in, TF-IDF clustering, LLM
synthesis, Astro out. A Kubernetes CronJob runs it three times a week and
it publishes by committing to git, so every article in the history is a
bot commit you can read. 121 of them since June.

**[pvewatch](https://github.com/ChristianKlass/pvewatch)** tells you when
a Proxmox backup fails. One container, SQLite, a read-only API token,
alerts to email or Discord. No Prometheus, no Grafana, no hook scripts.

Active development lives on a self-hosted GitLab. GitHub is the public
slice of it.

[resume.markklass.dev](https://resume.markklass.dev)
