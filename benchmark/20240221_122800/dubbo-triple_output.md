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
# Warmup Iteration   1: 5.103 ops/ms
# Warmup Iteration   2: 12.277 ops/ms
# Warmup Iteration   3: 12.276 ops/ms
Iteration   1: 12.791 ops/ms
Iteration   2: 12.889 ops/ms
Iteration   3: 12.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.796 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (12.710, 12.796, 12.889), stdev = 0.090
  CI (99.9%): [11.161, 14.432] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.940 ops/ms
# Warmup Iteration   2: 13.287 ops/ms
# Warmup Iteration   3: 13.242 ops/ms
Iteration   1: 13.194 ops/ms
Iteration   2: 13.138 ops/ms
Iteration   3: 13.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.224 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (13.138, 13.224, 13.340), stdev = 0.105
  CI (99.9%): [11.314, 15.134] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.923 ops/ms
# Warmup Iteration   2: 12.726 ops/ms
# Warmup Iteration   3: 12.948 ops/ms
Iteration   1: 13.076 ops/ms
Iteration   2: 13.116 ops/ms
Iteration   3: 13.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.107 ±(99.9%) 0.502 ops/ms [Average]
  (min, avg, max) = (13.076, 13.107, 13.128), stdev = 0.028
  CI (99.9%): [12.605, 13.609] (assumes normal distribution)


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
# Warmup Iteration   1: 6.795 ops/ms
# Warmup Iteration   2: 10.724 ops/ms
# Warmup Iteration   3: 10.805 ops/ms
Iteration   1: 10.965 ops/ms
Iteration   2: 10.920 ops/ms
Iteration   3: 10.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.922 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (10.880, 10.922, 10.965), stdev = 0.042
  CI (99.9%): [10.147, 11.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.476, 2.495, 2.513), stdev = 0.019
  CI (99.9%): [2.155, 2.835] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.537 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.003 ms/op
Iteration   1: 2.401 ±(99.9%) 0.004 ms/op
Iteration   2: 2.391 ±(99.9%) 0.003 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.404 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.391, 2.404, 2.419), stdev = 0.015
  CI (99.9%): [2.137, 2.670] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.003 ms/op
Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.432 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.414, 2.432, 2.441), stdev = 0.015
  CI (99.9%): [2.152, 2.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.570 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.004 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
Iteration   3: 2.948 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.948, 2.964, 2.980), stdev = 0.016
  CI (99.9%): [2.667, 3.262] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  5.846 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  9.087 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 11.451 ms/op
                 createUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385820
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 187927 
    [ 2.500,  3.750) = 193729 
    [ 3.750,  5.000) = 3304 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.916 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.338 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.387 ±(99.9%) 0.005 ms/op
Iteration   1: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  7.874 ms/op
                 existUser·p0.9999: 13.696 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.136 ms/op
                 existUser·p0.9999: 12.325 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  7.373 ms/op
                 existUser·p0.9999: 11.518 ms/op
                 existUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399966
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 211054 
    [ 2.500,  3.750) = 185264 
    [ 3.750,  5.000) = 2679 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      7.398 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  11.511 ms/op
                 getUser·p0.9999: 14.146 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  8.739 ms/op
                 getUser·p0.9999: 13.747 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  5.955 ms/op
                 getUser·p0.9999: 11.829 ms/op
                 getUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387767
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 194002 
    [ 2.500,  3.750) = 189229 
    [ 3.750,  5.000) = 3507 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.354 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.712 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
Iteration   1: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.820 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 10.813 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  10.317 ms/op
                 listUser·p0.9999: 11.936 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.590 ms/op
                 listUser·p0.9999: 11.444 ms/op
                 listUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323874
  mean =      2.961 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 99100 
    [ 2.500,  3.750) = 188763 
    [ 3.750,  5.000) = 29417 
    [ 5.000,  6.250) = 5222 
    [ 6.250,  7.500) = 512 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 236 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     11.564 ms/op
     p(99.9990) =     12.838 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.796 ± 1.635  ops/ms
ClientPb.existUser                       thrpt       3  13.224 ± 1.910  ops/ms
ClientPb.getUser                         thrpt       3  13.107 ± 0.502  ops/ms
ClientPb.listUser                        thrpt       3  10.922 ± 0.774  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.340   ms/op
ClientPb.existUser                        avgt       3   2.404 ± 0.267   ms/op
ClientPb.getUser                          avgt       3   2.432 ± 0.280   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.297   ms/op
ClientPb.createUser                     sample  385820   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.630           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.916           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  399966   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.873           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.877           ms/op
ClientPb.getUser                        sample  387767   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.682           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.684           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.681           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  323874   2.961 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.814           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.564           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.009           ms/op
