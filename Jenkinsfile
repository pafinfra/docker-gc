@Library('paf-jenkins@docker-pipeline-publish-only-master') import com.paf.pipeline.docker.*

Configuration config = Configuration.builder()
                                    .useEmptyBranchAsMaster()
                                    .build()

DockerImagePipeline.defaultPipeline(this, config).execute()

