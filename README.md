make 'NVCC =/usr/local/cuda-11.8/bin/nvcc -I/usr/local/cuda-11.8/targets/x86_64-linux/include/' 'CXX = mpic++ -I/usr/local/cuda-11.8/targets/x86_64-linux/include -L/usr/local/cuda-12.5/targets/x86_64-linux/lib/' 'gpu = true' -k -j
# sponge
