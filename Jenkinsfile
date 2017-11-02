@Library('paf-jenkins@v0.3.109') import com.paf.pipeline.docker.*

Configuration config = Configuration.builder()
                                    .useEmptyBranchAsMaster()
                                    .build()

DockerImagePipeline.defaultPipeline(this, config).execute()

