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
# Warmup Iteration   1: 4.853 ops/ms
# Warmup Iteration   2: 11.875 ops/ms
# Warmup Iteration   3: 12.316 ops/ms
Iteration   1: 12.623 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.780 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (12.623, 12.780, 12.971), stdev = 0.177
  CI (99.9%): [9.557, 16.003] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.052 ops/ms
# Warmup Iteration   2: 13.030 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 12.930 ops/ms
Iteration   2: 13.126 ops/ms
Iteration   3: 13.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.023 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (12.930, 13.023, 13.126), stdev = 0.098
  CI (99.9%): [11.227, 14.819] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.130 ops/ms
# Warmup Iteration   2: 12.702 ops/ms
# Warmup Iteration   3: 12.781 ops/ms
Iteration   1: 13.049 ops/ms
Iteration   2: 12.979 ops/ms
Iteration   3: 12.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.001 ±(99.9%) 0.765 ops/ms [Average]
  (min, avg, max) = (12.974, 13.001, 13.049), stdev = 0.042
  CI (99.9%): [12.236, 13.766] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.663 ops/ms
# Warmup Iteration   2: 10.572 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.736 ops/ms
Iteration   2: 10.774 ops/ms
Iteration   3: 10.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.767 ±(99.9%) 0.513 ops/ms [Average]
  (min, avg, max) = (10.736, 10.767, 10.790), stdev = 0.028
  CI (99.9%): [10.253, 11.280] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.516 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (2.490, 2.516, 2.537), stdev = 0.024
  CI (99.9%): [2.084, 2.947] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
Iteration   3: 2.482 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.493 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.482, 2.493, 2.505), stdev = 0.012
  CI (99.9%): [2.282, 2.704] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.454, 2.467, 2.481), stdev = 0.013
  CI (99.9%): [2.223, 2.711] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.743 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
Iteration   3: 2.981 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.981, 2.991, 3.008), stdev = 0.015
  CI (99.9%): [2.723, 3.259] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.709 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  11.639 ms/op
                 createUser·p0.9999: 13.515 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.598 ms/op
                 createUser·p0.999:  10.048 ms/op
                 createUser·p0.9999: 12.321 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  7.793 ms/op
                 createUser·p0.9999: 11.207 ms/op
                 createUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378604
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 182175 
    [ 2.500,  3.750) = 192616 
    [ 3.750,  5.000) = 3058 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.997 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.692 ms/op
                 existUser·p0.999:  8.658 ms/op
                 existUser·p0.9999: 14.684 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  5.921 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.816 ms/op
                 existUser·p0.999:  9.297 ms/op
                 existUser·p0.9999: 16.517 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386383
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 189855 
    [ 2.500,  3.750) = 192810 
    [ 3.750,  5.000) = 2577 
    [ 5.000,  6.250) = 630 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.752 ms/op
     p(99.9900) =     15.145 ms/op
     p(99.9990) =     17.385 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.701 ms/op
                 getUser·p0.999:  8.490 ms/op
                 getUser·p0.9999: 15.160 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  7.100 ms/op
                 getUser·p0.9999: 14.157 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  8.039 ms/op
                 getUser·p0.9999: 10.802 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386017
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 192174 
    [ 2.500,  3.750) = 189787 
    [ 3.750,  5.000) = 3166 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      7.100 ms/op
     p(99.9900) =     14.277 ms/op
     p(99.9990) =     15.443 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.480 ms/op
                 listUser·p0.9999: 9.732 ms/op
                 listUser·p1.00:   10.322 ms/op

Iteration   2: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.879 ms/op
                 listUser·p0.9999: 12.209 ms/op
                 listUser·p1.00:   13.255 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.572 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321395
  mean =      2.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 97675 
    [ 2.500,  3.750) = 186766 
    [ 3.750,  5.000) = 29959 
    [ 5.000,  6.250) = 5593 
    [ 6.250,  7.500) = 642 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 227 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      8.972 ms/op
     p(99.9900) =     11.734 ms/op
     p(99.9990) =     12.756 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.780 ± 3.223  ops/ms
ClientPb.existUser                       thrpt       3  13.023 ± 1.796  ops/ms
ClientPb.getUser                         thrpt       3  13.001 ± 0.765  ops/ms
ClientPb.listUser                        thrpt       3  10.767 ± 0.513  ops/ms
ClientPb.createUser                       avgt       3   2.516 ± 0.432   ms/op
ClientPb.existUser                        avgt       3   2.493 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.244   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.268   ms/op
ClientPb.createUser                     sample  378604   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.997           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  386383   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.752           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.145           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.629           ms/op
ClientPb.getUser                        sample  386017   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.563           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.100           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.277           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.729           ms/op
ClientPb.listUser                       sample  321395   2.984 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.898           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.972           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.734           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
