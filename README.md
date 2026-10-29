### Hi, I'm Ruben

I build production AI agents at [Laava](https://laava.nl). In the open, I work on computer vision and medical-imaging tooling, mostly on evaluation: metrics that hold up, benchmarks that can be reproduced, and checks that show what a model actually learned.

Most of my day-to-day commits go to private client repositories.

#### Open source contributions

- **[roboflow/supervision](https://github.com/roboflow/supervision/pulls?q=is%3Apr+author%3ARubenHaisma+is%3Amerged)** (11 merged): fixed mAP false-positive counting on background images, `from_tensorflow` box scaling, Pascal VOC export mutating its input, and crashes on malformed Gemini/Qwen output; vectorized `mask_to_xyxy` and `KeyPoints.as_detections` with bit-identical results.
- **[roboflow/trackers](https://github.com/roboflow/trackers/pulls?q=is%3Apr+author%3ARubenHaisma)** (5 merged): opt-in camera motion compensation for OC-SORT, a vectorized HOTA evaluator, TrackEval parity for MOT17 distractor classes, and BoT-SORT and IoU fixes. Hybrid-SORT is in review in [#608](https://github.com/roboflow/trackers/pull/608).
- **[roboflow/rf-detr](https://github.com/roboflow/rf-detr/pulls?q=is%3Apr+author%3ARubenHaisma+is%3Amerged)** (2 merged): the matcher now uses the configured `focal_alpha`, and `predict()` always runs in eval mode.
- **[unslothai/unsloth](https://github.com/unslothai/unsloth/pull/10852)**: `audit_supervision`, a pre-flight report of what an SFT dataset actually supervises.
- **[wasserth/TotalSegmentator](https://github.com/wasserth/TotalSegmentator/pull/579)**: CLI capability discovery, run reports and cohort statistics.
- **[openenv/OpenEnv](https://github.com/openenv/OpenEnv/pulls?q=is%3Apr+author%3ARubenHaisma+is%3Amerged)** (2 merged): env-client proxy race and provider health-poll fixes.
- **[cBioPortal/cbioportal-mcp](https://github.com/cBioPortal/cbioportal-mcp/pulls?q=is%3Apr+author%3ARubenHaisma)** (2 merged): study-lookup and install fixes.

[All merged pull requests](https://github.com/search?q=is%3Apr+author%3ARubenHaisma+is%3Amerged+is%3Apublic+-user%3ARubenHaisma+-org%3Alaava-ai&type=pullrequests)

#### Projects

| Project | What it does |
| :-- | :-- |
| [segauge](https://github.com/RubenHaisma/segauge) | DICOM-native evaluation for medical image segmentation: surface-distance metrics, per-lesion detection and a confidence interval on every number. `pip install segauge` |
| [sitecheck](https://github.com/RubenHaisma/sitecheck) | Checks whether a medical-ML result measures biology or the lab that produced the data. |
| [fiftyone-shortcut-risk](https://github.com/RubenHaisma/fiftyone-shortcut-risk) | The same shortcut check as a FiftyOne plugin: which metadata fields (site, scanner, batch) your embeddings can read and your labels correlate with. |
| [todo-for-agents](https://github.com/RubenHaisma/todo-for-agents) | A to-do list you share with Claude Code and Codex: GitHub issues, a small CLI, and a macOS window that shows which agent works on what. |
| [gitquake](https://github.com/RubenHaisma/gitquake) | Your GitHub history as a seismograph, with AI model releases as fault lines. One stdlib-only Python file. |
| [vitalocal-garmin](https://github.com/RubenHaisma/vitalocal-garmin) | A private AI health dashboard for Garmin data that runs entirely on your own laptop. |
