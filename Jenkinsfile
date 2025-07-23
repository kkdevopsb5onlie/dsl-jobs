pipelineJob('my-scm-pipeline') {
    description('Pipeline from Git repo')
    definition {
        cpsScm {
            scm {
                git {
                    remote {
                        url('https://github.com/your-org/your-repo.git')
                    }
                    branches('main')
                }
            }
        }
    }
}
