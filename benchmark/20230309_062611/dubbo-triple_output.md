# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 6.172 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.642 ops/ms
Iteration   2: 10.171 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.921 ±(99.9%) 4.845 ops/ms [Average]
  (min, avg, max) = (9.642, 9.921, 10.171), stdev = 0.266
  CI (99.9%): [5.075, 14.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 9.907 ops/ms
Iteration   1: 10.093 ops/ms
Iteration   2: 10.489 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.437 ±(99.9%) 5.871 ops/ms [Average]
  (min, avg, max) = (10.093, 10.437, 10.730), stdev = 0.322
  CI (99.9%): [4.567, 16.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.256 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.088 ops/ms
Iteration   3: 9.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.196 ±(99.9%) 5.929 ops/ms [Average]
  (min, avg, max) = (9.939, 10.196, 10.561), stdev = 0.325
  CI (99.9%): [4.267, 16.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.649 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.680 ops/ms
Iteration   3: 8.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.707 ±(99.9%) 1.320 ops/ms [Average]
  (min, avg, max) = (8.651, 8.707, 8.789), stdev = 0.072
  CI (99.9%): [7.387, 10.027] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.968 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.006 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
Iteration   3: 3.275 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.168 ±(99.9%) 1.760 ms/op [Average]
  (min, avg, max) = (3.086, 3.168, 3.275), stdev = 0.096
  CI (99.9%): [1.408, 4.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.008 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.081 ±(99.9%) 0.003 ms/op
Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
Iteration   3: 2.924 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.038 ±(99.9%) 1.823 ms/op [Average]
  (min, avg, max) = (2.924, 3.038, 3.110), stdev = 0.100
  CI (99.9%): [1.215, 4.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.754 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.008 ms/op
Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
Iteration   3: 3.125 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.114 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.098, 3.114, 3.125), stdev = 0.014
  CI (99.9%): [2.861, 3.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.832 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.006 ms/op
Iteration   1: 3.639 ±(99.9%) 0.010 ms/op
Iteration   2: 3.687 ±(99.9%) 0.007 ms/op
Iteration   3: 3.657 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.661 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.639, 3.661, 3.687), stdev = 0.024
  CI (99.9%): [3.225, 4.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
Iteration   1: 3.158 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  17.785 ms/op
                 createUser·p0.9999: 23.781 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.511 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  17.205 ms/op
                 createUser·p0.9999: 30.596 ms/op
                 createUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295083
  mean =      3.249 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17972 
    [ 2.500,  5.000) = 266384 
    [ 5.000,  7.500) = 9275 
    [ 7.500, 10.000) = 957 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     28.982 ms/op
     p(99.9990) =     37.621 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.961 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  16.752 ms/op
                 existUser·p0.9999: 22.224 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 23.466 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311838
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26347 
    [ 2.500,  5.000) = 280808 
    [ 5.000,  7.500) = 4028 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     15.780 ms/op
     p(99.9900) =     22.604 ms/op
     p(99.9990) =     23.982 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.738 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.010 ms/op
Iteration   1: 3.156 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 19.404 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  16.570 ms/op
                 getUser·p0.9999: 20.015 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  10.682 ms/op
                 getUser·p0.9999: 20.972 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303600
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14536 
    [ 2.500,  5.000) = 281941 
    [ 5.000,  7.500) = 6075 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 194 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     22.444 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.010 ms/op
Iteration   1: 3.664 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.047 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  16.068 ms/op
                 listUser·p0.9999: 29.041 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   2: 3.850 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.106 ms/op
                 listUser·p0.999:  13.665 ms/op
                 listUser·p0.9999: 15.465 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.624 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.092 ms/op
                 listUser·p0.99:   6.078 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 14.273 ms/op
                 listUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258706
  mean =      3.710 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 252583 
    [ 5.000,  7.500) = 4582 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.919 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     28.025 ms/op
     p(99.9990) =     31.321 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.921 ± 4.845  ops/ms
ClientPb.existUser                       thrpt       3  10.437 ± 5.871  ops/ms
ClientPb.getUser                         thrpt       3  10.196 ± 5.929  ops/ms
ClientPb.listUser                        thrpt       3   8.707 ± 1.320  ops/ms
ClientPb.createUser                       avgt       3   3.168 ± 1.760   ms/op
ClientPb.existUser                        avgt       3   3.038 ± 1.823   ms/op
ClientPb.getUser                          avgt       3   3.114 ± 0.253   ms/op
ClientPb.listUser                         avgt       3   3.661 ± 0.437   ms/op
ClientPb.createUser                     sample  295083   3.249 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.564           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  311838   3.076 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.604           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  303600   3.161 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.964           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.054           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.512           ms/op
ClientPb.listUser                       sample  258706   3.710 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.025           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.359           ms/op
