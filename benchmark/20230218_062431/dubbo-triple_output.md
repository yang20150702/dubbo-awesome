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
# Warmup Iteration   1: 0.967 ops/ms
# Warmup Iteration   2: 1.891 ops/ms
# Warmup Iteration   3: 4.160 ops/ms
Iteration   1: 5.025 ops/ms
Iteration   2: 5.367 ops/ms
Iteration   3: 5.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.309 ±(99.9%) 4.752 ops/ms [Average]
  (min, avg, max) = (5.025, 5.309, 5.537), stdev = 0.260
  CI (99.9%): [0.557, 10.062] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.531 ops/ms
# Warmup Iteration   2: 4.359 ops/ms
# Warmup Iteration   3: 5.469 ops/ms
Iteration   1: 5.651 ops/ms
Iteration   2: 5.701 ops/ms
Iteration   3: 5.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.612 ±(99.9%) 2.044 ops/ms [Average]
  (min, avg, max) = (5.486, 5.612, 5.701), stdev = 0.112
  CI (99.9%): [3.568, 7.657] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.485 ops/ms
# Warmup Iteration   2: 3.913 ops/ms
# Warmup Iteration   3: 5.361 ops/ms
Iteration   1: 5.310 ops/ms
Iteration   2: 5.506 ops/ms
Iteration   3: 5.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.458 ±(99.9%) 2.385 ops/ms [Average]
  (min, avg, max) = (5.310, 5.458, 5.557), stdev = 0.131
  CI (99.9%): [3.073, 7.842] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.395 ops/ms
# Warmup Iteration   2: 3.639 ops/ms
# Warmup Iteration   3: 4.587 ops/ms
Iteration   1: 4.770 ops/ms
Iteration   2: 4.893 ops/ms
Iteration   3: 4.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.816 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (4.770, 4.816, 4.893), stdev = 0.068
  CI (99.9%): [3.581, 6.050] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 21.319 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.906 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.033 ±(99.9%) 0.008 ms/op
Iteration   1: 5.967 ±(99.9%) 0.008 ms/op
Iteration   2: 5.780 ±(99.9%) 0.011 ms/op
Iteration   3: 5.762 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.837 ±(99.9%) 2.071 ms/op [Average]
  (min, avg, max) = (5.762, 5.837, 5.967), stdev = 0.114
  CI (99.9%): [3.766, 7.907] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 20.100 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.942 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.027 ±(99.9%) 0.009 ms/op
Iteration   1: 5.747 ±(99.9%) 0.009 ms/op
Iteration   2: 5.763 ±(99.9%) 0.006 ms/op
Iteration   3: 5.682 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.731 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (5.682, 5.731, 5.763), stdev = 0.043
  CI (99.9%): [4.950, 6.512] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.504 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.490 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.004 ±(99.9%) 0.007 ms/op
Iteration   1: 5.812 ±(99.9%) 0.007 ms/op
Iteration   2: 6.088 ±(99.9%) 0.008 ms/op
Iteration   3: 5.735 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.878 ±(99.9%) 3.382 ms/op [Average]
  (min, avg, max) = (5.735, 5.878, 6.088), stdev = 0.185
  CI (99.9%): [2.496, 9.260] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 23.373 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.779 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.002 ±(99.9%) 0.014 ms/op
Iteration   1: 6.704 ±(99.9%) 0.012 ms/op
Iteration   2: 6.701 ±(99.9%) 0.018 ms/op
Iteration   3: 6.815 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.740 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (6.701, 6.740, 6.815), stdev = 0.065
  CI (99.9%): [5.549, 7.931] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.406 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 7.469 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.499 ±(99.9%) 0.031 ms/op
Iteration   1: 5.926 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.463 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   11.698 ms/op
                 createUser·p0.999:  27.010 ms/op
                 createUser·p0.9999: 33.181 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   2: 5.796 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   7.315 ms/op
                 createUser·p0.95:   8.454 ms/op
                 createUser·p0.99:   11.555 ms/op
                 createUser·p0.999:  28.172 ms/op
                 createUser·p0.9999: 31.407 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   3: 5.937 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.504 ms/op
                 createUser·p0.95:   8.765 ms/op
                 createUser·p0.99:   12.337 ms/op
                 createUser·p0.999:  34.275 ms/op
                 createUser·p0.9999: 37.093 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163068
  mean =      5.886 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 34024 
    [ 5.000,  7.500) = 113446 
    [ 7.500, 10.000) = 11940 
    [10.000, 12.500) = 2445 
    [12.500, 15.000) = 722 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     28.475 ms/op
     p(99.9900) =     36.811 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.966 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 6.380 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.819 ±(99.9%) 0.023 ms/op
Iteration   1: 5.659 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.535 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   6.824 ms/op
                 existUser·p0.95:   8.126 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  27.591 ms/op
                 existUser·p0.9999: 30.707 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   2: 5.586 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.630 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 29.935 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   3: 5.660 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.531 ms/op
                 existUser·p0.50:   5.358 ms/op
                 existUser·p0.90:   6.914 ms/op
                 existUser·p0.95:   7.881 ms/op
                 existUser·p0.99:   10.999 ms/op
                 existUser·p0.999:  29.821 ms/op
                 existUser·p0.9999: 34.561 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170282
  mean =      5.635 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 43447 
    [ 5.000,  7.500) = 116068 
    [ 7.500, 10.000) = 8260 
    [10.000, 12.500) = 1736 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.531 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     32.864 ms/op
     p(99.9990) =     35.278 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.357 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 7.786 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.917 ±(99.9%) 0.024 ms/op
Iteration   1: 5.862 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   11.934 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 28.565 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 5.974 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   5.538 ms/op
                 getUser·p0.90:   7.594 ms/op
                 getUser·p0.95:   8.929 ms/op
                 getUser·p0.99:   12.648 ms/op
                 getUser·p0.999:  28.327 ms/op
                 getUser·p0.9999: 31.642 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   3: 5.976 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.843 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   7.455 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.108 ms/op
                 getUser·p0.999:  30.857 ms/op
                 getUser·p0.9999: 35.432 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 161663
  mean =      5.937 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 29983 
    [ 5.000,  7.500) = 116209 
    [ 7.500, 10.000) = 11626 
    [10.000, 12.500) = 2602 
    [12.500, 15.000) = 772 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      5.562 ms/op
     p(90.0000) =      7.422 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     26.433 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.722 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 21.656 ±(99.9%) 0.508 ms/op
# Warmup Iteration   2: 8.845 ±(99.9%) 0.068 ms/op
# Warmup Iteration   3: 7.074 ±(99.9%) 0.033 ms/op
Iteration   1: 7.114 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.310 ms/op
                 listUser·p0.50:   6.619 ms/op
                 listUser·p0.90:   8.946 ms/op
                 listUser·p0.95:   10.863 ms/op
                 listUser·p0.99:   14.959 ms/op
                 listUser·p0.999:  27.364 ms/op
                 listUser·p0.9999: 29.786 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 6.834 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   8.602 ms/op
                 listUser·p0.95:   10.355 ms/op
                 listUser·p0.99:   13.697 ms/op
                 listUser·p0.999:  31.031 ms/op
                 listUser·p0.9999: 35.759 ms/op
                 listUser·p1.00:   39.977 ms/op

Iteration   3: 6.941 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   10.535 ms/op
                 listUser·p0.99:   14.644 ms/op
                 listUser·p0.999:  32.560 ms/op
                 listUser·p0.9999: 38.430 ms/op
                 listUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137867
  mean =      6.961 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 2638 
    [ 5.000,  7.500) = 107665 
    [ 7.500, 10.000) = 18934 
    [10.000, 12.500) = 5662 
    [12.500, 15.000) = 1781 
    [15.000, 17.500) = 647 
    [17.500, 20.000) = 185 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      6.447 ms/op
     p(90.0000) =      8.749 ms/op
     p(95.0000) =     10.568 ms/op
     p(99.0000) =     14.434 ms/op
     p(99.9000) =     29.725 ms/op
     p(99.9900) =     37.828 ms/op
     p(99.9990) =     39.878 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.309 ± 4.752  ops/ms
ClientPb.existUser                       thrpt       3   5.612 ± 2.044  ops/ms
ClientPb.getUser                         thrpt       3   5.458 ± 2.385  ops/ms
ClientPb.listUser                        thrpt       3   4.816 ± 1.234  ops/ms
ClientPb.createUser                       avgt       3   5.837 ± 2.071   ms/op
ClientPb.existUser                        avgt       3   5.731 ± 0.781   ms/op
ClientPb.getUser                          avgt       3   5.878 ± 3.382   ms/op
ClientPb.listUser                         avgt       3   6.740 ± 1.191   ms/op
ClientPb.createUser                     sample  163068   5.886 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.618           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.684           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.796           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.475           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.811           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  170282   5.635 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.824           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.873           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.813           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.104           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.864           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  161663   5.937 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.504           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.716           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.731           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.554           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045           ms/op
ClientPb.listUser                       sample  137867   6.961 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.447           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.434           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.828           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.977           ms/op
