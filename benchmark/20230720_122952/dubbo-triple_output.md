# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.877 ops/ms
# Warmup Iteration   2: 2.142 ops/ms
# Warmup Iteration   3: 4.736 ops/ms
Iteration   1: 5.521 ops/ms
Iteration   2: 5.590 ops/ms
Iteration   3: 5.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.634 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (5.521, 5.634, 5.792), stdev = 0.141
  CI (99.9%): [3.062, 8.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.483 ops/ms
# Warmup Iteration   2: 4.574 ops/ms
# Warmup Iteration   3: 5.672 ops/ms
Iteration   1: 6.028 ops/ms
Iteration   2: 5.938 ops/ms
Iteration   3: 5.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.960 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (5.915, 5.960, 6.028), stdev = 0.060
  CI (99.9%): [4.872, 7.049] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 4.554 ops/ms
# Warmup Iteration   3: 5.672 ops/ms
Iteration   1: 5.827 ops/ms
Iteration   2: 5.415 ops/ms
Iteration   3: 5.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.595 ±(99.9%) 3.843 ops/ms [Average]
  (min, avg, max) = (5.415, 5.595, 5.827), stdev = 0.211
  CI (99.9%): [1.753, 9.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.506 ops/ms
# Warmup Iteration   2: 3.977 ops/ms
# Warmup Iteration   3: 4.977 ops/ms
Iteration   1: 5.023 ops/ms
Iteration   2: 4.996 ops/ms
Iteration   3: 5.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.056 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (4.996, 5.056, 5.150), stdev = 0.082
  CI (99.9%): [3.555, 6.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 20.360 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.030 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.914 ±(99.9%) 0.012 ms/op
Iteration   1: 5.565 ±(99.9%) 0.018 ms/op
Iteration   2: 5.740 ±(99.9%) 0.015 ms/op
Iteration   3: 5.525 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.610 ±(99.9%) 2.080 ms/op [Average]
  (min, avg, max) = (5.525, 5.610, 5.740), stdev = 0.114
  CI (99.9%): [3.530, 7.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 20.356 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.907 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.013 ms/op
Iteration   1: 5.377 ±(99.9%) 0.013 ms/op
Iteration   2: 5.415 ±(99.9%) 0.008 ms/op
Iteration   3: 5.506 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.433 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (5.377, 5.433, 5.506), stdev = 0.066
  CI (99.9%): [4.231, 6.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.452 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.633 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.614 ±(99.9%) 0.017 ms/op
Iteration   1: 5.644 ±(99.9%) 0.008 ms/op
Iteration   2: 5.495 ±(99.9%) 0.012 ms/op
Iteration   3: 5.573 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.571 ±(99.9%) 1.358 ms/op [Average]
  (min, avg, max) = (5.495, 5.571, 5.644), stdev = 0.074
  CI (99.9%): [4.212, 6.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.885 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 8.229 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.593 ±(99.9%) 0.012 ms/op
Iteration   1: 6.485 ±(99.9%) 0.012 ms/op
Iteration   2: 6.645 ±(99.9%) 0.016 ms/op
Iteration   3: 6.307 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.479 ±(99.9%) 3.080 ms/op [Average]
  (min, avg, max) = (6.307, 6.479, 6.645), stdev = 0.169
  CI (99.9%): [3.399, 9.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.358 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 7.367 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.881 ±(99.9%) 0.027 ms/op
Iteration   1: 5.348 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.568 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.426 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  25.133 ms/op
                 createUser·p0.9999: 28.837 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 5.645 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.250 ms/op
                 createUser·p0.95:   8.110 ms/op
                 createUser·p0.99:   10.781 ms/op
                 createUser·p0.999:  26.224 ms/op
                 createUser·p0.9999: 29.371 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   3: 5.463 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.668 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  27.541 ms/op
                 createUser·p0.9999: 30.441 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174995
  mean =      5.483 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 79623 
    [ 5.000,  7.500) = 84508 
    [ 7.500, 10.000) = 8613 
    [10.000, 12.500) = 1428 
    [12.500, 15.000) = 413 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     30.130 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.538 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.634 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.393 ±(99.9%) 0.023 ms/op
Iteration   1: 5.516 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.250 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  23.526 ms/op
                 existUser·p0.9999: 28.128 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   2: 5.281 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.742 ms/op
                 existUser·p0.95:   7.709 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  24.819 ms/op
                 existUser·p0.9999: 28.508 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 5.401 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   7.905 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  28.148 ms/op
                 existUser·p0.9999: 30.780 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177776
  mean =      5.398 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 87812 
    [ 5.000,  7.500) = 77654 
    [ 7.500, 10.000) = 9812 
    [10.000, 12.500) = 1682 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.963 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     24.125 ms/op
     p(99.9900) =     29.801 ms/op
     p(99.9990) =     32.124 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.977 ±(99.9%) 0.353 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.845 ±(99.9%) 0.024 ms/op
Iteration   1: 5.714 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   7.284 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   12.091 ms/op
                 getUser·p0.999:  24.281 ms/op
                 getUser·p0.9999: 27.276 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 5.678 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   7.209 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  20.570 ms/op
                 getUser·p0.9999: 31.519 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 5.626 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.266 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  30.414 ms/op
                 getUser·p0.9999: 36.831 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169090
  mean =      5.672 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 63840 
    [ 5.000,  7.500) = 90795 
    [ 7.500, 10.000) = 11022 
    [10.000, 12.500) = 2337 
    [12.500, 15.000) = 619 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     34.341 ms/op
     p(99.9990) =     37.023 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.565 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 8.297 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.827 ±(99.9%) 0.035 ms/op
Iteration   1: 6.384 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.119 ms/op
                 listUser·p0.999:  25.817 ms/op
                 listUser·p0.9999: 31.322 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   2: 6.319 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 27.881 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   3: 6.330 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  23.539 ms/op
                 listUser·p0.9999: 37.549 ms/op
                 listUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151344
  mean =      6.344 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 8661 
    [ 5.000,  7.500) = 123500 
    [ 7.500, 10.000) = 15195 
    [10.000, 12.500) = 2764 
    [12.500, 15.000) = 706 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.840 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     25.023 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     37.584 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.634 ± 2.573  ops/ms
ClientPb.existUser                       thrpt       3   5.960 ± 1.088  ops/ms
ClientPb.getUser                         thrpt       3   5.595 ± 3.843  ops/ms
ClientPb.listUser                        thrpt       3   5.056 ± 1.501  ops/ms
ClientPb.createUser                       avgt       3   5.610 ± 2.080   ms/op
ClientPb.existUser                        avgt       3   5.433 ± 1.201   ms/op
ClientPb.getUser                          avgt       3   5.571 ± 1.358   ms/op
ClientPb.listUser                         avgt       3   6.479 ± 3.080   ms/op
ClientPb.createUser                     sample  174995   5.483 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.758           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.657           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.130           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  177776   5.398 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.740           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.963           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.617           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.125           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.801           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  169090   5.672 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.479           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.364           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.534           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.183           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.341           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.159           ms/op
ClientPb.listUser                       sample  151344   6.344 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.154           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.840           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.042           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.023           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.700           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
