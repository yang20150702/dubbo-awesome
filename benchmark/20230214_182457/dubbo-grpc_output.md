# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.528 ops/ms
# Warmup Iteration   2: 9.216 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.425 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.561 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (10.425, 10.561, 10.754), stdev = 0.172
  CI (99.9%): [7.421, 13.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.850 ops/ms
# Warmup Iteration   2: 10.567 ops/ms
# Warmup Iteration   3: 10.732 ops/ms
Iteration   1: 10.930 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.786 ±(99.9%) 2.482 ops/ms [Average]
  (min, avg, max) = (10.659, 10.786, 10.930), stdev = 0.136
  CI (99.9%): [8.305, 13.268] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.858 ops/ms
# Warmup Iteration   2: 10.208 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.753 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.635 ±(99.9%) 4.021 ops/ms [Average]
  (min, avg, max) = (10.381, 10.635, 10.772), stdev = 0.220
  CI (99.9%): [6.614, 14.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.052 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 7.900 ops/ms
Iteration   1: 8.093 ops/ms
Iteration   2: 8.259 ops/ms
Iteration   3: 8.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.259 ±(99.9%) 3.025 ops/ms [Average]
  (min, avg, max) = (8.093, 8.259, 8.424), stdev = 0.166
  CI (99.9%): [5.234, 11.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.001 ms/op
Iteration   2: 3.151 ±(99.9%) 0.001 ms/op
Iteration   3: 3.133 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.115 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.061, 3.115, 3.151), stdev = 0.048
  CI (99.9%): [2.239, 3.990] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 2.934 ±(99.9%) 0.003 ms/op
Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
Iteration   3: 2.939 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.915, 2.929, 2.939), stdev = 0.013
  CI (99.9%): [2.696, 3.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 3.119 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.095 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.065, 3.095, 3.119), stdev = 0.028
  CI (99.9%): [2.589, 3.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.034 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.024 ms/op
Iteration   1: 3.844 ±(99.9%) 0.044 ms/op
Iteration   2: 3.877 ±(99.9%) 0.016 ms/op
Iteration   3: 4.049 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 2.009 ms/op [Average]
  (min, avg, max) = (3.844, 3.923, 4.049), stdev = 0.110
  CI (99.9%): [1.914, 5.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 2.946 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.966 ms/op
                 createUser·p0.9999: 17.470 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.247 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 15.417 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.615 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315732
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2702 
    [ 1.250,  2.500) = 32715 
    [ 2.500,  3.750) = 252715 
    [ 3.750,  5.000) = 26415 
    [ 5.000,  6.250) = 584 
    [ 6.250,  7.500) = 186 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.706 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     17.709 ms/op
     p(99.9990) =     19.061 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.726 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.750 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.546 ms/op
                 existUser·p0.9999: 14.592 ms/op
                 existUser·p1.00:   16.548 ms/op

Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  8.168 ms/op
                 existUser·p0.9999: 13.614 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  11.582 ms/op
                 existUser·p0.9999: 22.443 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323397
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47330 
    [ 2.500,  5.000) = 275148 
    [ 5.000,  7.500) = 548 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.903 ms/op
     p(99.9900) =     19.944 ms/op
     p(99.9990) =     22.758 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.194 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 19.702 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 2.941 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.357 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.333 ms/op
                 getUser·p0.999:  8.529 ms/op
                 getUser·p0.9999: 24.183 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  5.768 ms/op
                 getUser·p0.9999: 19.085 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321893
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33492 
    [ 2.500,  5.000) = 287343 
    [ 5.000,  7.500) = 785 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     23.080 ms/op
     p(99.9990) =     24.423 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.470 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.310 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  12.839 ms/op
                 listUser·p0.9999: 15.026 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   2: 3.910 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  16.023 ms/op
                 listUser·p0.9999: 20.877 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.709 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  15.195 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242747
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7256 
    [ 2.500,  5.000) = 205682 
    [ 5.000,  7.500) = 28717 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     27.848 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.561 ± 3.139  ops/ms
ClientGrpc.existUser                       thrpt       3  10.786 ± 2.482  ops/ms
ClientGrpc.getUser                         thrpt       3  10.635 ± 4.021  ops/ms
ClientGrpc.listUser                        thrpt       3   8.259 ± 3.025  ops/ms
ClientGrpc.createUser                       avgt       3   3.115 ± 0.875   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.233   ms/op
ClientGrpc.getUser                          avgt       3   3.095 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 2.009   ms/op
ClientGrpc.createUser                     sample  315732   3.043 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.247           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.706           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.405           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.709           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  323397   2.967 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.903           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.944           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.839           ms/op
ClientGrpc.getUser                        sample  321893   2.982 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.357           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.080           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.543           ms/op
ClientGrpc.listUser                       sample  242747   3.954 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.310           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.336           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.019           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
