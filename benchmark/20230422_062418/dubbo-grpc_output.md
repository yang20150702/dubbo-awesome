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
# Warmup Iteration   1: 4.379 ops/ms
# Warmup Iteration   2: 9.078 ops/ms
# Warmup Iteration   3: 10.287 ops/ms
Iteration   1: 10.512 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.655 ±(99.9%) 3.957 ops/ms [Average]
  (min, avg, max) = (10.512, 10.655, 10.904), stdev = 0.217
  CI (99.9%): [6.698, 14.611] (assumes normal distribution)


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
# Warmup Iteration   1: 7.769 ops/ms
# Warmup Iteration   2: 10.717 ops/ms
# Warmup Iteration   3: 11.041 ops/ms
Iteration   1: 11.069 ops/ms
Iteration   2: 11.131 ops/ms
Iteration   3: 11.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.163 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (11.069, 11.163, 11.289), stdev = 0.113
  CI (99.9%): [9.094, 13.232] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.020 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.612 ±(99.9%) 0.595 ops/ms [Average]
  (min, avg, max) = (10.591, 10.612, 10.650), stdev = 0.033
  CI (99.9%): [10.017, 11.208] (assumes normal distribution)


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
# Warmup Iteration   1: 5.422 ops/ms
# Warmup Iteration   2: 7.784 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.055 ops/ms
Iteration   2: 8.214 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.127 ±(99.9%) 1.471 ops/ms [Average]
  (min, avg, max) = (8.055, 8.127, 8.214), stdev = 0.081
  CI (99.9%): [6.656, 9.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.004 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.040 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.022, 3.032, 3.040), stdev = 0.010
  CI (99.9%): [2.858, 3.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.002 ms/op
Iteration   1: 2.897 ±(99.9%) 0.003 ms/op
Iteration   2: 2.901 ±(99.9%) 0.003 ms/op
Iteration   3: 2.879 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (2.879, 2.892, 2.901), stdev = 0.012
  CI (99.9%): [2.676, 3.109] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.986 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.967, 2.986, 3.005), stdev = 0.019
  CI (99.9%): [2.637, 3.335] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.024 ms/op
Iteration   1: 3.901 ±(99.9%) 0.015 ms/op
Iteration   2: 3.911 ±(99.9%) 0.012 ms/op
Iteration   3: 3.965 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.901, 3.925, 3.965), stdev = 0.034
  CI (99.9%): [3.303, 4.548] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.563 ms/op
                 createUser·p0.9999: 13.369 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  7.823 ms/op
                 createUser·p0.9999: 14.929 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.720 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320659
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35139 
    [ 2.500,  5.000) = 283496 
    [ 5.000,  7.500) = 1582 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.905 ms/op
     p(99.9900) =     23.506 ms/op
     p(99.9990) =     26.365 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.005 ms/op
Iteration   1: 2.902 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  7.369 ms/op
                 existUser·p0.9999: 12.484 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   2: 2.838 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  9.792 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.811 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.656 ms/op
                 existUser·p0.9999: 15.478 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336717
  mean =      2.850 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2938 
    [ 1.250,  2.500) = 48954 
    [ 2.500,  3.750) = 276350 
    [ 3.750,  5.000) = 7341 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 240 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     16.223 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
Iteration   1: 3.054 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.116 ms/op
                 getUser·p0.9999: 13.476 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  10.232 ms/op
                 getUser·p0.9999: 13.621 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.145 ms/op
                 getUser·p0.9999: 27.155 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317693
  mean =      3.019 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20381 
    [ 2.500,  5.000) = 295604 
    [ 5.000,  7.500) = 1240 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.531 ms/op
     p(99.9000) =      8.623 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.618 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.011 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.922 ms/op
                 listUser·p0.9999: 18.867 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.975 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 25.815 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   3: 3.887 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.733 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 20.891 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243068
  mean =      3.948 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3316 
    [ 2.500,  5.000) = 216721 
    [ 5.000,  7.500) = 21759 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     16.235 ms/op
     p(99.9900) =     24.715 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.655 ± 3.957  ops/ms
ClientGrpc.existUser                       thrpt       3  11.163 ± 2.069  ops/ms
ClientGrpc.getUser                         thrpt       3  10.612 ± 0.595  ops/ms
ClientGrpc.listUser                        thrpt       3   8.127 ± 1.471  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.174   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.216   ms/op
ClientGrpc.getUser                          avgt       3   2.986 ± 0.349   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.623   ms/op
ClientGrpc.createUser                     sample  320659   2.993 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.529           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.905           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.506           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  336717   2.850 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.705           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.847           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.434           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.368           ms/op
ClientGrpc.getUser                        sample  317693   3.019 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.531           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.623           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.313           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.754           ms/op
ClientGrpc.listUser                       sample  243068   3.948 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.819           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.235           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.715           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.934           ms/op
