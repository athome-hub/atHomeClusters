# Issues

## High CPU Load Spikes

![CPULoad](./images/CPULoad-individualNodes.png)

I'm unsure what is causing the periodic load on the system, even though there is very light usage, especially during work hours. 

This could be a combination of Longhorn, keeping the storage in sync, the recurring task for Nextcloud, ["Nextcloud Background Jobs"](https://docs.nextcloud.com/server/latest/admin_manual/configuration_server/background_jobs_configuration.html) (which runs as a single process despite the plural), or the Postgres databases staying in sync.  

Haven't looked into this issue too much, as I think I'm kneecapping the system by using the older 6th gen i5 Intel CPU, which is slower and smaller in terms of available threads (4 threads). The 8th gen i5 with 6 threads is doing better.  

For now, the system is good enough, I have not felt it slow and I am using it sporadically throughout the day.  
That being said, I've decided that I will eventually replace these with some [HP EliteDesk 800 G6 Mini](https://www.servethehome.com/hp-elitedesk-800-g6-mini-65w-review-tmm-more-power/). These have a faster 10th gen i5 with 6 cores and 12 threads, but as it sits right now, I do not need to perform this upgrade.  
