# One is none
As the saying goes, "one is none" when it comes to backups. If you have data you can't bear to lose, you need to back it up somewhere. End of discussion.

# Local backups
I have a Synology DS218play at home. It's a very entry-level NAS (network-attached storage) model from Synology. I have two drives installed (the max this model supports) for a couple terabytes of storage. The drives use a replication strategy, though it would be more effective with more drives, and in retrospect I wish I'd picked a model with dual ethernet ports as well, but it does okay.

When I am finished with files, I move them to the NAS. I can access the NAS from anywhere, and it runs some basic apps like Photos that I can use to share photos and back up my phone photos.

My new (to me) Mac can use Time Machine to back up to the NAS. I haven't set that up, but am going to in the near future. Time Machine is intended to back up to a local device, so either you need a USB hard drive, a NAS, or an application to mount cloud storage locally.

## Other uses for a NAS
A NAS can also run other applications, like a media server (via Emby, or Jellyfin, or Plex). Some Synology models (not including mine) can run arbitrary Docker containers, allowing you to run almost anything.

# Off-site backups
I use Synology's Hyper Backup application to upload to Backblaze B2 cloud storage. It costs around $9/month at present for a few terabytes of backups. I haven't had occasion to use the off-site backups yet, but it gives me peace of mind to know they're there.

For my Linux laptop, I use Duplicacy to back up straight to Backblaze.
