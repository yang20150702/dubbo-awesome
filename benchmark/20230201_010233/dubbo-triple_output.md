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
# Warmup Iteration   1: 1.536 ops/ms
# Warmup Iteration   2: 3.431 ops/ms
# Warmup Iteration   3: 7.127 ops/ms
Iteration   1: 7.527 ops/ms
Iteration   2: 7.792 ops/ms
Iteration   3: 7.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.724 ±(99.9%) 3.176 ops/ms [Average]
  (min, avg, max) = (7.527, 7.724, 7.855), stdev = 0.174
  CI (99.9%): [4.548, 10.901] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.938 ops/ms
# Warmup Iteration   2: 6.394 ops/ms
# Warmup Iteration   3: 8.043 ops/ms
Iteration   1: 8.297 ops/ms
Iteration   2: 8.621 ops/ms
Iteration   3: 8.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.475 ±(99.9%) 2.992 ops/ms [Average]
  (min, avg, max) = (8.297, 8.475, 8.621), stdev = 0.164
  CI (99.9%): [5.483, 11.466] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.016 ops/ms
# Warmup Iteration   2: 6.539 ops/ms
# Warmup Iteration   3: 7.975 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.155 ±(99.9%) 3.235 ops/ms [Average]
  (min, avg, max) = (8.026, 8.155, 8.358), stdev = 0.177
  CI (99.9%): [4.921, 11.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.865 ops/ms
# Warmup Iteration   2: 5.684 ops/ms
# Warmup Iteration   3: 6.394 ops/ms
Iteration   1: 6.390 ops/ms
Iteration   2: 6.936 ops/ms
Iteration   3: 6.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.706 ±(99.9%) 5.163 ops/ms [Average]
  (min, avg, max) = (6.390, 6.706, 6.936), stdev = 0.283
  CI (99.9%): [1.543, 11.869] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.253 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.008 ms/op
Iteration   1: 4.031 ±(99.9%) 0.009 ms/op
Iteration   2: 4.044 ±(99.9%) 0.007 ms/op
Iteration   3: 4.184 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.086 ±(99.9%) 1.544 ms/op [Average]
  (min, avg, max) = (4.031, 4.086, 4.184), stdev = 0.085
  CI (99.9%): [2.542, 5.631] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.559 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.005 ms/op
Iteration   1: 3.961 ±(99.9%) 0.003 ms/op
Iteration   2: 3.808 ±(99.9%) 0.003 ms/op
Iteration   3: 3.782 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.850 ±(99.9%) 1.768 ms/op [Average]
  (min, avg, max) = (3.782, 3.850, 3.961), stdev = 0.097
  CI (99.9%): [2.082, 5.618] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.579 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.897 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.004 ms/op
Iteration   1: 4.052 ±(99.9%) 0.008 ms/op
Iteration   2: 3.973 ±(99.9%) 0.005 ms/op
Iteration   3: 3.968 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.998 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (3.968, 3.998, 4.052), stdev = 0.047
  CI (99.9%): [3.138, 4.857] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.072 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.420 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.873 ±(99.9%) 0.006 ms/op
Iteration   1: 4.561 ±(99.9%) 0.012 ms/op
Iteration   2: 4.702 ±(99.9%) 0.011 ms/op
Iteration   3: 4.644 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.636 ±(99.9%) 1.290 ms/op [Average]
  (min, avg, max) = (4.561, 4.636, 4.702), stdev = 0.071
  CI (99.9%): [3.346, 5.925] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.931 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.767 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.477 ±(99.9%) 0.018 ms/op
Iteration   1: 3.957 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 22.673 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.877 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.015 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  22.595 ms/op
                 createUser·p0.9999: 25.125 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.713 ms/op
                 createUser·p0.999:  25.133 ms/op
                 createUser·p0.9999: 29.017 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244899
  mean =      3.918 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177 
    [ 2.500,  5.000) = 235210 
    [ 5.000,  7.500) = 7942 
    [ 7.500, 10.000) = 1065 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     20.713 ms/op
     p(99.9900) =     28.230 ms/op
     p(99.9990) =     29.611 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.688 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.014 ms/op
Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  11.476 ms/op
                 existUser·p0.9999: 25.923 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 3.940 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  16.331 ms/op
                 existUser·p0.9999: 27.230 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.808 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  26.434 ms/op
                 existUser·p0.9999: 30.743 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249825
  mean =      3.843 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 466 
    [ 2.500,  5.000) = 240066 
    [ 5.000,  7.500) = 6819 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     17.444 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.599 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.012 ms/op
Iteration   1: 4.037 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   8.094 ms/op
                 getUser·p0.999:  22.151 ms/op
                 getUser·p0.9999: 26.025 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   2: 4.053 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.079 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  11.193 ms/op
                 getUser·p0.9999: 27.496 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   3: 3.894 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  26.436 ms/op
                 getUser·p0.9999: 29.610 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240281
  mean =      3.994 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 230884 
    [ 5.000,  7.500) = 6583 
    [ 7.500, 10.000) = 1991 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     22.198 ms/op
     p(99.9900) =     28.244 ms/op
     p(99.9990) =     30.257 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.219 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.457 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.837 ±(99.9%) 0.016 ms/op
Iteration   1: 4.985 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  28.234 ms/op
                 listUser·p0.9999: 33.811 ms/op
                 listUser·p1.00:   36.307 ms/op

Iteration   2: 4.859 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  20.251 ms/op
                 listUser·p0.9999: 25.370 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.654 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  16.502 ms/op
                 listUser·p0.9999: 19.517 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198841
  mean =      4.829 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 163686 
    [ 5.000,  7.500) = 28589 
    [ 7.500, 10.000) = 5498 
    [10.000, 12.500) = 511 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     20.916 ms/op
     p(99.9900) =     32.903 ms/op
     p(99.9990) =     35.659 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.724 ± 3.176  ops/ms
ClientPb.existUser                       thrpt       3   8.475 ± 2.992  ops/ms
ClientPb.getUser                         thrpt       3   8.155 ± 3.235  ops/ms
ClientPb.listUser                        thrpt       3   6.706 ± 5.163  ops/ms
ClientPb.createUser                       avgt       3   4.086 ± 1.544   ms/op
ClientPb.existUser                        avgt       3   3.850 ± 1.768   ms/op
ClientPb.getUser                          avgt       3   3.998 ± 0.859   ms/op
ClientPb.listUser                         avgt       3   4.636 ± 1.290   ms/op
ClientPb.createUser                     sample  244899   3.918 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.581           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.881           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  249825   3.843 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.489           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.487           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.444           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.655           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.588           ms/op
ClientPb.getUser                        sample  240281   3.994 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.198           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  198841   4.829 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.659           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.029           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.916           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.307           ms/op
