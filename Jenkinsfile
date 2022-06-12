@Library('shared-libraries@master')_

def env_config =[
  app_name: "Molema.com"
  mvn_build_command: "mvn clean install"
  docker_build_command: "docker build -t sample-app-java-springboot:latest ."
]

ci_pipeline_v1(env_config)
