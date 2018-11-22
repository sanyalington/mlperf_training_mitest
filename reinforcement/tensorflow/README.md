# Docker commands

## Build from tf-cpu container
docker build -t mlperf_mitest/rl_tfcpu -f Dockerfile.tfcpu .

## Build from tf-gpu container
docker build -t mlperf_mitest/rl_tfgpu -f Dockerfile.tfgpu .
