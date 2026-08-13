# Mark Klass

Platform and DevOps engineer in Singapore. Eight years, mostly Linux,
cloud infrastructure and CI/CD. At work that currently means AWS,
mostly EKS and EC2.

There's two repos here that I'm kinda proud of:

**[kopilog](https://github.com/ChristianKlass/kopilog)** publishes a tech
news site with nobody at the wheel. RSS in, TF-IDF clustering, LLM
synthesis, Astro out. A Kubernetes CronJob runs it three times a week and
it publishes by committing to git, so every article in the history is a
bot commit you can read. 121 of them since June.

![The kopilog front page, styled like a green-phosphor terminal: an ls ~/latest listing of article cards with cover images, category tags, and dates](https://raw.githubusercontent.com/ChristianKlass/kopilog/main/docs/kopilog-home.png)

**[pvewatch](https://github.com/ChristianKlass/pvewatch)** tells you when
a Proxmox backup fails. One container, SQLite, a read-only API token,
alerts to email or Discord.

![The pvewatch dashboard: totals for backed-up and failed guests, a per-guest backup history table with one failed row, and storage usage bars](https://raw.githubusercontent.com/ChristianKlass/pvewatch/main/docs/screenshot.png)

At home I run a Proxmox box with 14 guests and a two-node kubeadm
cluster. Terraform builds it, Flux keeps it that way, SOPS keeps
secrets out of git.

Frigate does the cameras, detection on a Coral EdgeTPU and Plex
transcoding on QuickSync. I rebuilt the box around a Core Ultra 5
245K, which let me drop the 2060 and cut the power draw. Backups run
four tiers deep into Cloudflare R2.

Most of what I build here has an LLM in the loop, this README
included. I'd rather get good at directing that than pretend
otherwise.

Active development lives on a self-hosted GitLab; GitHub is the public
slice of it. Resume at [resume.markklass.dev](https://resume.markklass.dev).
