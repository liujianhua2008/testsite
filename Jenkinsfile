pipeline {
    agent any

    stages {
        stage('拉取代码 ') {
            steps {
                echo '拉取代码完成'
            }
        }
        stage('maven编译打包') {
            steps {
                echo 'maven编译打包完成'
            }
        }
        stage('部署到测试环境') {
            steps {
                echo '部署到测试环境完成'
            }
        }
        stage('自动化测试') {
            steps {
                echo '自动化测试完成'
            }
        }
        stage('制作镜像') {
            steps {
                echo '制作镜像完成'
            }
        }
        stage('上传harbor') {
            steps {
                echo '上传harbor完成'
            }
        }
    }
}
