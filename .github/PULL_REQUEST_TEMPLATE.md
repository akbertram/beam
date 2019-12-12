**Please** add a meaningful description for your change here

------------------------

Thank you for your contribution! Follow this checklist to help us incorporate your contribution quickly and easily:

 - [ ] [**Choose reviewer(s)**](https://beam.apache.org/contribute/#make-your-change) and mention them in a comment (`R: @username`).
 - [ ] Format the pull request title like `[BEAM-XXX] Fixes bug in ApproximateQuantiles`, where you replace `BEAM-XXX` with the appropriate JIRA issue, if applicable. This will automatically link the pull request to the issue.
 - [ ] If this contribution is large, please file an Apache [Individual Contributor License Agreement](https://www.apache.org/licenses/icla.pdf).

See the [Contributor Guide](https://beam.apache.org/contribute) for more tips on [how to make review process smoother](https://beam.apache.org/contribute/#make-reviewers-job-easier).

Post-Commit Tests Status (on master branch)
------------------------------------------------------------------------------------------------

Lang | SDK | Apex | Dataflow | Flink | Gearpump | Samza | Spark
--- | --- | --- | --- | --- | --- | --- | ---
Go | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Go/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Go/lastCompletedBuild/) | --- | --- | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Go_VR_Flink/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Go_VR_Flink/lastCompletedBuild/) | --- | --- | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Go_VR_Spark/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Go_VR_Spark/lastCompletedBuild/)
Java | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Apex/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Apex/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Dataflow/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Dataflow/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Flink/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Flink/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_PVR_Flink_Batch/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_PVR_Flink_Batch/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_PVR_Flink_Streaming/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_PVR_Flink_Streaming/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Gearpump/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Gearpump/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Samza/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Samza/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Spark/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_Spark/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_PVR_Spark_Batch/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_PVR_Spark_Batch/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_SparkStructuredStreaming/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Java_ValidatesRunner_SparkStructuredStreaming/lastCompletedBuild/)
Python | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Python2/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Python2/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Python35/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Python35/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Python36/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Python36/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Python37/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Python37/lastCompletedBuild/) | --- | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Py_VR_Dataflow/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Py_VR_Dataflow/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Py_ValCont/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Py_ValCont/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PreCommit_Python2_PVR_Flink_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_Python2_PVR_Flink_Cron/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PostCommit_Python35_VR_Flink/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Python35_VR_Flink/lastCompletedBuild/) | --- | --- | [![Build Status](https://builds.apache.org/job/beam_PostCommit_Python_VR_Spark/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_Python_VR_Spark/lastCompletedBuild/)
XLang | --- | --- | --- | [![Build Status](https://builds.apache.org/job/beam_PostCommit_XVR_Flink/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PostCommit_XVR_Flink/lastCompletedBuild/) | --- | --- | ---

Pre-Commit Tests Status (on master branch)
------------------------------------------------------------------------------------------------

--- |Java | Python | Go | Website
--- | --- | --- | --- | ---
Non-portable | [![Build Status](https://builds.apache.org/job/beam_PreCommit_Java_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_Java_Cron/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PreCommit_Python_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_Python_Cron/lastCompletedBuild/)<br>[![Build Status](https://builds.apache.org/job/beam_PreCommit_PythonLint_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_PythonLint_Cron/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PreCommit_Go_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_Go_Cron/lastCompletedBuild/) | [![Build Status](https://builds.apache.org/job/beam_PreCommit_Website_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_Website_Cron/lastCompletedBuild/) 
Portable | --- | [![Build Status](https://builds.apache.org/job/beam_PreCommit_Portable_Python_Cron/lastCompletedBuild/badge/icon)](https://builds.apache.org/job/beam_PreCommit_Portable_Python_Cron/lastCompletedBuild/) | --- | ---

See [.test-infra/jenkins/README](https://github.com/apache/beam/blob/master/.test-infra/jenkins/README.md) for trigger phrase, status and link of all Jenkins jobs.