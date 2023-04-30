# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.303 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.991 ops/ms
Iteration   2: 10.769 ops/ms
Iteration   3: 10.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.862 ±(99.9%) 2.099 ops/ms [Average]
  (min, avg, max) = (10.769, 10.862, 10.991), stdev = 0.115
  CI (99.9%): [8.763, 12.961] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.624 ops/ms
# Warmup Iteration   2: 10.670 ops/ms
# Warmup Iteration   3: 11.181 ops/ms
Iteration   1: 11.154 ops/ms
Iteration   2: 11.248 ops/ms
Iteration   3: 11.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.235 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (11.154, 11.235, 11.303), stdev = 0.075
  CI (99.9%): [9.867, 12.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.220 ops/ms
# Warmup Iteration   2: 10.180 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.603 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 2.283 ops/ms [Average]
  (min, avg, max) = (10.356, 10.491, 10.603), stdev = 0.125
  CI (99.9%): [8.208, 12.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.603 ops/ms
# Warmup Iteration   2: 8.001 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 8.145 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.087 ±(99.9%) 1.056 ops/ms [Average]
  (min, avg, max) = (8.030, 8.087, 8.145), stdev = 0.058
  CI (99.9%): [7.031, 9.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (2.982, 3.016, 3.048), stdev = 0.033
  CI (99.9%): [2.417, 3.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.002 ms/op
Iteration   1: 2.900 ±(99.9%) 0.002 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (2.888, 2.914, 2.953), stdev = 0.035
  CI (99.9%): [2.274, 3.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 2.976 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (2.976, 3.007, 3.044), stdev = 0.035
  CI (99.9%): [2.376, 3.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.414 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.013 ms/op
Iteration   1: 3.905 ±(99.9%) 0.008 ms/op
Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
Iteration   3: 3.922 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.909 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.899, 3.909, 3.922), stdev = 0.012
  CI (99.9%): [3.690, 4.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.796 ms/op
                 createUser·p0.999:  10.883 ms/op
                 createUser·p0.9999: 20.351 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.088 ms/op
                 createUser·p0.9999: 16.695 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.997 ms/op
                 createUser·p0.9999: 16.646 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313760
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21862 
    [ 2.500,  5.000) = 289755 
    [ 5.000,  7.500) = 1544 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     19.452 ms/op
     p(99.9990) =     20.639 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.813 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.635 ms/op
                 existUser·p0.9999: 12.683 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.653 ms/op
                 existUser·p0.9999: 16.286 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 20.748 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328695
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40583 
    [ 2.500,  5.000) = 286931 
    [ 5.000,  7.500) = 727 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     21.117 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.119 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.029 ms/op
                 getUser·p0.9999: 13.813 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.597 ms/op
                 getUser·p0.999:  6.964 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323276
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23862 
    [ 2.500,  5.000) = 298066 
    [ 5.000,  7.500) = 1126 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =     22.551 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.340 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
Iteration   1: 3.752 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.739 ms/op
                 listUser·p0.999:  14.931 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 17.227 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249319
  mean =      3.849 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4118 
    [ 2.500,  5.000) = 225334 
    [ 5.000,  7.500) = 18679 
    [ 7.500, 10.000) = 689 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.232 ms/op
     p(99.9900) =     24.054 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.862 ± 2.099  ops/ms
ClientGrpc.existUser                       thrpt       3  11.235 ± 1.368  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 2.283  ops/ms
ClientGrpc.listUser                        thrpt       3   8.087 ± 1.056  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.599   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.640   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.631   ms/op
ClientGrpc.listUser                         avgt       3   3.909 ± 0.219   ms/op
ClientGrpc.createUser                     sample  313760   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.777           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.011           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.452           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.709           ms/op
ClientGrpc.existUser                      sample  328695   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.077           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.318           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  323276   2.968 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.718           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.400           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.551           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.771           ms/op
ClientGrpc.listUser                       sample  249319   3.849 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.232           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.054           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
