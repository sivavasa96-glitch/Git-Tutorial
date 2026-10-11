What is GitLab

. GitLab is a web-based complete DevOps platform, that spans the entire software
development lifecycle and helps teams to accelerate DevOps adoption.

. Enables professionals to perform all tasks in a project - project planning, source code
management, monitoring and security.

. GitLab is not a monolithic application; it believes a software module should do only one
particular thing, and do it well.

. Provides a Git-repository manager for issue-tracking, continuous integration and deployment.

. Supports both public and private development branches with free and paid options.

. Was created by Dmitriy Zaporozhets a web programmer in Ukraine in the year 2011.

. Is updated every twenty-second day of the month since then.

. It's an open-core project under which core software systems are released as an open-source
license but have various paid versions with enhanced features.

Pipeline

. Pipelines are the top-level component of continuous integration, delivery, and deployment.


. Pipeline comprises of two things: Jobs and Stages.

. Job defines what to do. Ex. A job to test the code, or to compile the code.

. Stages are collection of jobs. It defines the order of jobs.

. If all jobs in a stage succeed, the pipeline moves on to the next stage.

. If any job in a stage fails, the next stage is not (usually) executed and the pipeline ends early.

. Pipelines are executed automatically and require no intervention once created.

. GitLab also allows you to manually interact with a pipeline.

. Four usual stages of a CI/CD pipeline are test, build, stage and prod.

. Multiple types of pipelines can be built - Basic pipeline, DAG pipeline, Parent-child
pipeline, Multi-project pipelines etc.