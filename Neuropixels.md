---
title: Neuropixels methodology
---

We need to get Neuropixels working at setup2 and setup7.

# Spike sorting

- [X] Decide on pipeline
- [ ] Fix scripts
  - [ ] Transfer scripts (one for setup, one for ephys)
  - [ ] Prep script
  - [ ] Sorting script
  - [ ] Export script
- [ ] Verify spike alignment
- [ ] Get abstraction on YP.

# Setup 2

- [ ] Verify I can feel dura in Fengel (1 day)
- [ ] Put a dummy probe in Fengel (1 day)
- [ ] Put a real probe in Fengel (1 day)

# Setup 7

- [ ] JRR free reaching restored
  - [ ] Consistent lack of bias during instructed reaching

Consider reducing the reward size according to reach time (penalize slow reaches so the nearer limb would be used).
Consider moving the screen back so he cannot reach across midline.

# Pipeline

- Transfer s/f-files to conception:/data. This should be mounted on the abstraction server, too.
- Transfer ephys files to abstraction:/ephys_data (maybe rename this)
- Sort.
- Backups to an external drive.
