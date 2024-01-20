# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.336 ops/ms
# Warmup Iteration   2: 12.252 ops/ms
# Warmup Iteration   3: 12.496 ops/ms
Iteration   1: 12.806 ops/ms
Iteration   2: 12.873 ops/ms
Iteration   3: 12.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.862 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (12.806, 12.862, 12.906), stdev = 0.051
  CI (99.9%): [11.924, 13.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.073 ops/ms
# Warmup Iteration   2: 13.039 ops/ms
# Warmup Iteration   3: 13.108 ops/ms
Iteration   1: 13.175 ops/ms
Iteration   2: 13.217 ops/ms
Iteration   3: 13.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.199 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (13.175, 13.199, 13.217), stdev = 0.022
  CI (99.9%): [12.799, 13.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ops/ms
# Warmup Iteration   2: 12.919 ops/ms
# Warmup Iteration   3: 13.207 ops/ms
Iteration   1: 13.109 ops/ms
Iteration   2: 13.066 ops/ms
Iteration   3: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.094 ±(99.9%) 0.444 ops/ms [Average]
  (min, avg, max) = (13.066, 13.094, 13.109), stdev = 0.024
  CI (99.9%): [12.650, 13.538] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.978 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.713 ops/ms
Iteration   3: 10.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.740 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (10.713, 10.740, 10.759), stdev = 0.024
  CI (99.9%): [10.302, 11.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.490, 2.508, 2.533), stdev = 0.023
  CI (99.9%): [2.094, 2.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.003 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.420, 2.427, 2.436), stdev = 0.008
  CI (99.9%): [2.287, 2.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.437 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.429, 2.437, 2.449), stdev = 0.011
  CI (99.9%): [2.237, 2.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 2.984 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.984, 2.991, 3.001), stdev = 0.009
  CI (99.9%): [2.834, 3.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  6.360 ms/op
                 createUser·p0.9999: 13.276 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.917 ms/op
                 createUser·p0.9999: 11.579 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.700 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 11.443 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386917
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 188812 
    [ 2.500,  3.750) = 194279 
    [ 3.750,  5.000) = 2988 
    [ 5.000,  6.250) = 318 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      9.406 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.509 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.254 ms/op
                 existUser·p0.9999: 13.285 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  8.553 ms/op
                 existUser·p0.9999: 12.836 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  8.222 ms/op
                 existUser·p0.9999: 11.079 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393441
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 194316 
    [ 2.500,  3.750) = 195004 
    [ 3.750,  5.000) = 3206 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.161 ms/op
     p(99.9900) =     12.921 ms/op
     p(99.9990) =     13.698 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  10.049 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  9.054 ms/op
                 getUser·p0.9999: 12.943 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 11.161 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383068
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 190003 
    [ 2.500,  3.750) = 189179 
    [ 3.750,  5.000) = 2899 
    [ 5.000,  6.250) = 560 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      7.477 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.782 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.009 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.594 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.517 ms/op
                 listUser·p0.999:  9.461 ms/op
                 listUser·p0.9999: 12.181 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.006 ms/op
                 listUser·p0.9999: 10.407 ms/op
                 listUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322749
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 98180 
    [ 2.500,  3.750) = 187367 
    [ 3.750,  5.000) = 29864 
    [ 5.000,  6.250) = 5793 
    [ 6.250,  7.500) = 669 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.628 ms/op
     p(99.9990) =     12.540 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.862 ± 0.938  ops/ms
ClientPb.existUser                       thrpt       3  13.199 ± 0.400  ops/ms
ClientPb.getUser                         thrpt       3  13.094 ± 0.444  ops/ms
ClientPb.listUser                        thrpt       3  10.740 ± 0.438  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.414   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.140   ms/op
ClientPb.getUser                          avgt       3   2.437 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.157   ms/op
ClientPb.createUser                     sample  386917   2.479 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.756           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.406           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.631           ms/op
ClientPb.existUser                      sample  393441   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.161           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.921           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.926           ms/op
ClientPb.getUser                        sample  383068   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.834           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.477           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.287           ms/op
ClientPb.listUser                       sample  322749   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.719           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.845           ms/op
