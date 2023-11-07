# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.163 ops/ms
# Warmup Iteration   2: 11.771 ops/ms
# Warmup Iteration   3: 12.135 ops/ms
Iteration   1: 12.397 ops/ms
Iteration   2: 12.406 ops/ms
Iteration   3: 12.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.362 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (12.284, 12.362, 12.406), stdev = 0.068
  CI (99.9%): [11.124, 13.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.114 ops/ms
# Warmup Iteration   2: 12.813 ops/ms
# Warmup Iteration   3: 12.929 ops/ms
Iteration   1: 12.868 ops/ms
Iteration   2: 12.977 ops/ms
Iteration   3: 13.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.953 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (12.868, 12.953, 13.014), stdev = 0.076
  CI (99.9%): [11.567, 14.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ops/ms
# Warmup Iteration   2: 12.678 ops/ms
# Warmup Iteration   3: 12.601 ops/ms
Iteration   1: 12.696 ops/ms
Iteration   2: 12.578 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.647 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (12.578, 12.647, 12.696), stdev = 0.061
  CI (99.9%): [11.530, 13.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.530 ops/ms
# Warmup Iteration   2: 10.417 ops/ms
# Warmup Iteration   3: 10.518 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.639 ±(99.9%) 0.931 ops/ms [Average]
  (min, avg, max) = (10.601, 10.639, 10.697), stdev = 0.051
  CI (99.9%): [9.708, 11.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.572 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.531, 2.549, 2.572), stdev = 0.021
  CI (99.9%): [2.162, 2.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.003 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.456, 2.478, 2.492), stdev = 0.020
  CI (99.9%): [2.117, 2.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
Iteration   3: 2.551 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.548 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.543, 2.548, 2.551), stdev = 0.004
  CI (99.9%): [2.467, 2.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.866 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.000, 3.022, 3.041), stdev = 0.021
  CI (99.9%): [2.637, 3.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.303 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  11.301 ms/op
                 createUser·p0.9999: 14.239 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  9.722 ms/op
                 createUser·p0.9999: 12.757 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.616 ms/op
                 createUser·p0.9999: 12.411 ms/op
                 createUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374468
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 177627 
    [ 2.500,  3.750) = 191140 
    [ 3.750,  5.000) = 4217 
    [ 5.000,  6.250) = 954 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.361 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.697 ms/op
                 existUser·p0.999:  5.884 ms/op
                 existUser·p0.9999: 14.060 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  8.587 ms/op
                 existUser·p0.9999: 15.368 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  8.651 ms/op
                 existUser·p0.9999: 13.135 ms/op
                 existUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385080
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 187196 
    [ 2.500,  3.750) = 193828 
    [ 3.750,  5.000) = 2776 
    [ 5.000,  6.250) = 803 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      7.270 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     16.129 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.836 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.553 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  12.215 ms/op
                 getUser·p0.9999: 14.082 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 13.804 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  8.762 ms/op
                 getUser·p0.9999: 11.762 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375862
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 180794 
    [ 2.500,  3.750) = 188352 
    [ 3.750,  5.000) = 5263 
    [ 5.000,  6.250) = 954 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      8.948 ms/op
     p(99.9900) =     13.786 ms/op
     p(99.9990) =     14.417 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.009 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  10.322 ms/op
                 listUser·p0.9999: 11.570 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 13.011 ms/op
                 listUser·p1.00:   13.599 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.910 ms/op
                 listUser·p0.9999: 11.380 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311763
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 82381 
    [ 2.500,  3.750) = 185813 
    [ 3.750,  5.000) = 35155 
    [ 5.000,  6.250) = 6761 
    [ 6.250,  7.500) = 860 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 236 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.998 ms/op
     p(99.9900) =     11.499 ms/op
     p(99.9990) =     13.384 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.362 ± 1.238  ops/ms
ClientPb.existUser                       thrpt       3  12.953 ± 1.386  ops/ms
ClientPb.getUser                         thrpt       3  12.647 ± 1.116  ops/ms
ClientPb.listUser                        thrpt       3  10.639 ± 0.931  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.387   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.361   ms/op
ClientPb.getUser                          avgt       3   2.548 ± 0.081   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.386   ms/op
ClientPb.createUser                     sample  374468   2.561 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.807           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  385080   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.847           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.270           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.123           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.220           ms/op
ClientPb.getUser                        sample  375862   2.552 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.894           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.948           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  311763   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.998           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.499           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.599           ms/op
